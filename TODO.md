# TODO

- [ ] Confirm SonarCloud organization/project configuration is present in repository (sonar-project.properties, workflow, scanner args).
- [x] Inspect repository Sonar-related files.
- [ ] Apply hardening change to CI workflow: pass `-Dsonar.organization=ezra12363` in `.github/workflows/sonar.yml`.
- [ ] Run lint + tests locally to ensure CI still passes.
- [ ] (After push) Verify scan results in SonarCloud: organization `ezra12363`, project `Ezra12363_smart-maintenance`.

