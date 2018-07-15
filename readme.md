inject
======

This repo is the same as facebook's, except that you can specify inject.Value instances to be 'Mock'. If they're mocks, they'll populate before non-mocks. This helps you test an existing dependency-injection graph in situ because you can swap out implementations for mocks per-test. For example; prior to running a lengthy application test case we could swap out external web service and date/time dependencies with mocks.

Documentation: https://godoc.org/github.com/facebookgo/inject
