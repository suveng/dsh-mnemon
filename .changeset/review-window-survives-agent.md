---
"dsh-mnemon": patch
---

The review window now belongs to the conversation instead of the Agent object: DSH replaces a conversation's Agent on resume, clear and compaction, and the window used to be dropped with it, so a session that never scored its threshold in a single turn never collected one. A recreated Agent keeps the collected turns and only restarts the failure streak.
