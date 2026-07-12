# IAM Security Basics

## Objective
Set up a secure AWS account foundation by applying IAM best practices instead of relying on the root user for daily operations following the principle of least privilege.

## What I did
- [ ] Enabled MFA (Multi-Factor Authentication) on the root account
- [ ] Created a new IAM user for daily administrative tasks (instead of using root)
- [ ] Enabled MFA on the IAM user
- [ ] Created an IAM group (e.g. `Admins` or `S3ReadOnlyGroup`)
- [ ] Wrote and attached a custom IAM policy (least privilege principle)
- [ ] Tested access to confirm the policy behaves as expected
- [ ] Reviewed IAM Access Analyzer / Credential Report

## What I learned
- The difference between the **root user** and **IAM users**
- Why the root account should never be used for daily tasks
- How IAM policies are structured (Effect, Action, Resource, Condition)
- The principle of **least privilege**: only grant the permissions strictly needed; VERY IMPORTANT
- How groups simplify permission management for multiple users


