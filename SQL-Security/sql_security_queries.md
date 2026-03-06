# SQL Security Investigation

## Objective
Identify suspicious login attempts in system logs.

## Example Query

SELECT username, login_time
FROM login_logs
WHERE status = 'failed';

## Result

The query returns failed login attempts which may indicate brute-force attacks.

## Security Action

- Monitor repeated login failures
- Lock accounts after multiple attempts