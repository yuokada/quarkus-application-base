# GitHub Copilot Instructions

Follow these repository instructions when working in this project.

## General guidance

- Keep changes focused and consistent with this single-module Quarkus base POM repository.
- Write new or updated repository instructions, comments, and documentation in English.
- Avoid local absolute paths, machine-specific assumptions, and committed secrets.
- Preserve compatibility for downstream projects that inherit this base POM.
- Prefer small, reviewable changes and avoid altering defaults without a clear reason.

## Project context

- The root `pom.xml` defines the reusable parent/base POM for Quarkus applications.
- Release, publish, and CI automation live under `.github/workflows/`.
- The repository is configuration-focused and does not contain a runnable Quarkus application.

## Validation

- Prefer `./mvnw -q verify` when parent POM or plugin behavior changes.
- Clearly distinguish between checks you ran and checks you did not run.
