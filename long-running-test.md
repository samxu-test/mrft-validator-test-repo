# Long-running test with Do Not Merge label

This file will trigger a long-running test to demonstrate MRFT validation skip behavior.

The test should take ~5 minutes to complete, during which time:
1. MRFT validation should be SKIPPED (due to Do Not Merge label)
2. Aggregated check should show IN_PROGRESS (waiting for test)
3. After 5 minutes, should show FAIL due to Do Not Merge label only

Test trigger content:
- Long integration test
- Performance benchmarks  
- Extended validation suite



## 🕒 Workflow Update - 4-minute timing test now active!

The GitHub workflow with 4-minute extended test is now enabled.
This update will trigger the timing test to demonstrate MRFT skip behavior.

Updated at: Mon Sep 29 17:31:09 PDT 2025

