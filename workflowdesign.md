```plaintext
ENTRY
  ↓
[DispatchNode]
  ↓
 ┌────────────────────────────┐
 │  Parallel: 6 Evaluators    │
 └────────┬───────────────────┘
          ↓
     [Praetor Node]
          ↓
    [HumanInterrupt Y/N?]
      ↙           ↘
    YES           NO
     ↓             ↓
(loop again)     [Output Final Results]
```
