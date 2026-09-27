# Documentation lifecycle

Every module has CONTENT, UPDATE, TEST, and STABLE directories.

1. Record the current architecture and decisions in CONTENT.
2. Draft proposed changes in UPDATE without affecting production.
3. Record checks and outcomes in TEST.
4. After PASS, review and merge the documentation baseline into STABLE.

A failed test means STOP + REPORT; retain the previous STABLE baseline. STABLE here describes documentation only, never a claim about deployment health. MUBA remains the production source of truth. Do not put real credentials, secrets, or tokens here.
