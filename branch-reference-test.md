# Branch Reference Pattern Intelligence Test

This test verifies that JIRA-like patterns in square brackets are properly ignored and don't trigger false MRFT validation errors.

The enhanced branch reference intelligence should ignore patterns like:
- [DMF-8.9.x]
- [FOO-1.2.3]
- [ATLAS-1.0]

But should still detect actual JIRA references like:
- DMF-123: (without brackets)
- BSC-456: (without brackets)

This PR tests the enhanced pattern filtering.

Fixes: BUG999888