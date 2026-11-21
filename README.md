# CI/CD Pipeline with GitHub Actions and Docker

A pipeline that tests, builds and ships a containerised app without any manual steps.

> **Status: planned.** This repository currently holds the project plan only. No working code has been published yet, and I will update this page as each part is built.

## Goal

A pipeline that tests, builds and ships a containerised app without any manual steps.

## Planned stack

GitHub Actions, Docker, GitHub Container Registry, a small web app

## Scope

- [ ] Lint and unit tests on every push
- [ ] Docker image built once and tagged with the commit
- [ ] Image scanning before publish
- [ ] Automatic deploy to a test server after the main branch passes
- [ ] Rollback to the previous image tag
- [ ] Secrets kept in GitHub Actions secrets, never in the repo

## What this repository will contain

Workflow files, the sample app, and notes on how each stage works and fails.

## Progress

| Stage | State |
| --- | --- |
| Plan and scope | Done |
| Build | Not started |
| Testing | Not started |
| Write-up | Not started |

## Author

Muhammad Abdullah, DevOps Engineer, London. [LinkedIn](https://www.linkedin.com/in/muhammadabdullaheh)
