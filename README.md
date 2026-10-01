# Safety Testing Command Center — UI Mockup

Design mockup for Action Elevator's safety-testing workflow.

Live canvas: https://claude.ai/artifact/DYs88EXyfUpYZwkuKxkbah

## Screens
1. **Open Cases** (`screens/Main.dc.html`) — queue grouped by due month and priority, status badges, overdue QEI report alerts.
2. **Coverage & Approval** (`screens/Coverage.dc.html`) — auto-derived contract coverage; billable jobs locked until customer approval email is attached.
3. **Dispatch** (`screens/Dispatch.dc.html`) — area-based technician matching and automated FIELDBOSS service activity creation.
4. **Dual-Signal Reconciliation** (`screens/Reconcile.dc.html`) — mechanic result vs. QEI report side by side; blocks closing when they disagree.
5. **Reinspection** (`screens/Reinspection.dc.html`) — pass/fail dispositions and a violation remediation tracker.

## Notes
- All customers, technicians and case numbers are sample data.
- `.dc.html` files are Design Component source for the Claude design canvas; they need its runtime to render.
