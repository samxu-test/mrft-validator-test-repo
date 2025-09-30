# Branch Reference Pattern Intelligence Test

This test checks that JIRA-like patterns in square brackets are ignored.

The enhanced pattern filtering should NOT trigger MRFT errors for patterns like:
- [DMF-8.9.x] (version branch pattern)
- [FOO-1.2.3] (version pattern)
- [ATLAS-1.0] (release pattern)

This content should pass MRFT validation without errors.

Fixes: TEST123
