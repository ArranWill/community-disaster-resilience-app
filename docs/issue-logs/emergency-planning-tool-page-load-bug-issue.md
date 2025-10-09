# Emergency Planning Tool Page Load Bug

## Priority
Medium

## Assigned To
- Software Engineer

## Reported By
Reported by the QA Specialist during a system test verifying navigation from the dashboard to the Emergency Planning Tool pages under Work Package 3.3a.

## Date Reported
2025-09-22 09:18

## Date Resolved
Pending

## Description
The Emergency Planning Tool (EPT) page intermittently fails to load after navigation, producing a blank screen.

## Comments
- Issue identified during system test in Phase 3.3a.
- Root cause: race condition in UI route guards affecting user flow for disaster plan editing.
- Decision made 22 Sep 11:30 to delay heavy data prefetch and introduce route-loading gates.

## Resolution
Fix scheduled for Sprint 4.
