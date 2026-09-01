**Topic: Debugging + Testbench**


Given a 4-bit counter RTL, identify and fix its bugs.

**Required behavior:**

Reset → 0,
Enable = 1 → increment,
Enable = 0 → hold,
15 → 0,
Reset has priority,

**Testbench requirements**

**Verify:
Reset,
Counting,
Hold,
15 → 0,
Reset while counting,
