# ci-triage-drill-17

Live example repository for onboarding: triaging a red CI build.

Drill workflow: `.github/workflows/drill.yml` — manual trigger, single job `drill-job`,
prints `DRILL-FAIL` and exits non-zero so the run always ends in failure.
