---
applyTo: "pom.xml"
---

When editing the Maven POM in this repository:

- Keep dependency, plugin, and profile configuration stable for downstream consumers.
- Avoid removing properties or changing default versions unless the change is intentional and clearly justified.
- Keep release, signing, and publishing settings aligned with the existing Maven Central workflow.
- Prefer explicit, maintainable property names and existing POM structure over broad reformatting.
