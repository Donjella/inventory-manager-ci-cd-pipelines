# inventory-manager-ci-cd-pipelines
Complete the CI/CD process with full integration and automation.

## Cronjobs
- A time-based scheduler.
- It tells Github Actions to run your workflow at a regular interval.

- * * * * *
- First: minute (0 - 59)
- Second: hour (0 - 23)
- Third: Day of month (1 - 31)
- Fourth: Month (1- 12)
- Fifth: Day of Week (0 - 6) (Sunday - Saturday)
- *: every

0 0 * * * - midnight everyday UTC
0 12 * * 1 - every Monday at 12 PM UTC
* * * * * - every minute
*/15 * * * * - every 15 mins
0 0 1,16 * * 
0 0 * * 1-5