# CI/CD

Hands-on resources for learning how code moves from a commit to automated tests, artifacts, environments, and production deployments.

## Resources

| Resource | Description |
|---|---|
| [GitHub Skills — Hello GitHub Actions](https://github.com/skills/hello-github-actions) | Learn GitHub Actions by modifying a real repository and creating a workflow that runs automatically. |
| [GitHub Skills — Test with Actions](https://github.com/skills/test-with-actions) | Hands-on GitHub Skills course for running tests in CI, publishing coverage, and working with branch protections. |
| [GitLab CI/CD — Get Started](https://docs.gitlab.com/ci/quick_start/) | Build and run your first GitLab pipeline with jobs, stages, runners, and `.gitlab-ci.yml`. |
| [GitLab CI/CD Tutorial](https://docs.gitlab.com/ci/quick_start/tutorial/) | A guided project that progressively turns a basic pipeline into a more realistic CI/CD workflow. |

## Core concepts to understand

- continuous integration vs. continuous delivery vs. continuous deployment
- workflow triggers
- jobs, stages, and dependencies
- runners / agents
- build artifacts
- dependency and build caches
- test automation
- matrices and parallel jobs
- secrets and environment variables
- deployment environments
- approvals and protected branches
- versioning and releases
- rollback strategies
- deployment strategies such as rolling, blue/green, and canary

## A useful first project

Take one of your existing applications and make every pull request automatically:

`lint` → `build` → `unit test` → `integration test` → `package`

Then deploy only after the pipeline succeeds.

[← Back to main README](../README.md)
