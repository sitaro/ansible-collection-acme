# Changelog

## [3.0.1](https://github.com/telekom-mms/ansible-collection-acme/tree/3.0.1) (2023-08-09)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/3.0.0...3.0.1)

**Merged pull requests:**

- update test matrix and do not ansible-lint .github [\#100](https://github.com/telekom-mms/ansible-collection-acme/pull/100) ([rndmh3ro](https://github.com/rndmh3ro))
- rename challenge-var to include role\_prefix [\#99](https://github.com/telekom-mms/ansible-collection-acme/pull/99) ([rndmh3ro](https://github.com/rndmh3ro))

## [3.0.0](https://github.com/telekom-mms/ansible-collection-acme/tree/3.0.0) (2023-06-27)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.6...3.0.0)

**Merged pull requests:**

- Move organization [\#98](https://github.com/telekom-mms/ansible-collection-acme/pull/98) ([avalor1](https://github.com/avalor1))
- run CI-tests only once peer week [\#97](https://github.com/telekom-mms/ansible-collection-acme/pull/97) ([rndmh3ro](https://github.com/rndmh3ro))
- chore\(deps\): update actions/checkout action to v3.5.3 [\#96](https://github.com/telekom-mms/ansible-collection-acme/pull/96) ([renovate[bot]](https://github.com/apps/renovate))
- add spellchecking with codespell [\#94](https://github.com/telekom-mms/ansible-collection-acme/pull/94) ([schurzi](https://github.com/schurzi))
- linting with ansible-lint [\#93](https://github.com/telekom-mms/ansible-collection-acme/pull/93) ([rndmh3ro](https://github.com/rndmh3ro))
- chore\(deps\): update actions/checkout action to v3.5.2 [\#92](https://github.com/telekom-mms/ansible-collection-acme/pull/92) ([renovate[bot]](https://github.com/apps/renovate))
- use reusable workflow [\#80](https://github.com/telekom-mms/ansible-collection-acme/pull/80) ([rndmh3ro](https://github.com/rndmh3ro))

## [2.3.6](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.6) (2023-03-29)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.5...2.3.6)

**Fixed bugs:**

- Fix azure dns challenge bug [\#91](https://github.com/telekom-mms/ansible-collection-acme/pull/91) ([avalor1](https://github.com/avalor1))

**Merged pull requests:**

- chore\(deps\): update actions/checkout action to v3.5.0 [\#90](https://github.com/telekom-mms/ansible-collection-acme/pull/90) ([renovate[bot]](https://github.com/apps/renovate))

## [2.3.5](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.5) (2023-03-23)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.4...2.3.5)

**Merged pull requests:**

- Add Azure blob storage provider [\#89](https://github.com/telekom-mms/ansible-collection-acme/pull/89) ([avalor1](https://github.com/avalor1))
- update README.md [\#88](https://github.com/telekom-mms/ansible-collection-acme/pull/88) ([beechesII](https://github.com/beechesII))
- update links to providers [\#86](https://github.com/telekom-mms/ansible-collection-acme/pull/86) ([rndmh3ro](https://github.com/rndmh3ro))
- chore\(deps\): update actions/checkout action to v3.3.0 [\#84](https://github.com/telekom-mms/ansible-collection-acme/pull/84) ([renovate[bot]](https://github.com/apps/renovate))
- chore\(deps\): update actions/checkout action to v3.2.0 [\#82](https://github.com/telekom-mms/ansible-collection-acme/pull/82) ([renovate[bot]](https://github.com/apps/renovate))
- chore\(deps\): update actions/checkout action to v3.1.0 [\#78](https://github.com/telekom-mms/ansible-collection-acme/pull/78) ([renovate[bot]](https://github.com/apps/renovate))
- when pushing, run action only on master [\#77](https://github.com/telekom-mms/ansible-collection-acme/pull/77) ([rndmh3ro](https://github.com/rndmh3ro))

## [2.3.4](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.4) (2022-11-30)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.3...2.3.4)

**Fixed bugs:**

- Fix wrong module name in roles/acme/tasks/challenge/http-01/s3.yml [\#81](https://github.com/telekom-mms/ansible-collection-acme/pull/81) ([beechesII](https://github.com/beechesII))

**Closed issues:**

- Requirements missing [\#50](https://github.com/telekom-mms/ansible-collection-acme/issues/50)

**Merged pull requests:**

- fix linting [\#79](https://github.com/telekom-mms/ansible-collection-acme/pull/79) ([rndmh3ro](https://github.com/rndmh3ro))
- fix linting - uppercase first letter of task-names [\#76](https://github.com/telekom-mms/ansible-collection-acme/pull/76) ([rndmh3ro](https://github.com/rndmh3ro))
- update used versions in tests [\#75](https://github.com/telekom-mms/ansible-collection-acme/pull/75) ([rndmh3ro](https://github.com/rndmh3ro))

## [2.3.3](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.3) (2022-07-04)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.2...2.3.3)

**Fixed bugs:**

- autodns: remove TXT RRs when validation fails [\#74](https://github.com/telekom-mms/ansible-collection-acme/pull/74) ([z-bsod](https://github.com/z-bsod))

**Merged pull requests:**

- Update actions/setup-python action to v4 [\#73](https://github.com/telekom-mms/ansible-collection-acme/pull/73) ([renovate[bot]](https://github.com/apps/renovate))
- Update actions/checkout action to v3 [\#72](https://github.com/telekom-mms/ansible-collection-acme/pull/72) ([renovate[bot]](https://github.com/apps/renovate))

## [2.3.2](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.2) (2022-06-09)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.1...2.3.2)

**Fixed bugs:**

- fix ansible-lint errors [\#67](https://github.com/telekom-mms/ansible-collection-acme/pull/67) ([rndmh3ro](https://github.com/rndmh3ro))

**Closed issues:**

- Test against recent ansible versions  [\#64](https://github.com/telekom-mms/ansible-collection-acme/issues/64)

**Merged pull requests:**

- Update github-actions-x/commit action to v2.9 [\#71](https://github.com/telekom-mms/ansible-collection-acme/pull/71) ([renovate[bot]](https://github.com/apps/renovate))
- Update charmixer/auto-changelog-action action to v1.4 [\#69](https://github.com/telekom-mms/ansible-collection-acme/pull/69) ([renovate[bot]](https://github.com/apps/renovate))
- Update actions/checkout action to v2.4.2 [\#68](https://github.com/telekom-mms/ansible-collection-acme/pull/68) ([renovate[bot]](https://github.com/apps/renovate))
- Configure Renovate [\#66](https://github.com/telekom-mms/ansible-collection-acme/pull/66) ([renovate[bot]](https://github.com/apps/renovate))
- Test against recent ansible versions [\#65](https://github.com/telekom-mms/ansible-collection-acme/pull/65) ([avalor1](https://github.com/avalor1))

## [2.3.1](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.1) (2021-08-19)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.3.0...2.3.1)

**Implemented enhancements:**

- pfx convert has no full chain [\#59](https://github.com/telekom-mms/ansible-collection-acme/issues/59)

**Fixed bugs:**

- Remove delegate\_to when creating directories for certificate [\#63](https://github.com/telekom-mms/ansible-collection-acme/pull/63) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- Use temp-dir for creation of certificates? [\#5](https://github.com/telekom-mms/ansible-collection-acme/issues/5)

## [2.3.0](https://github.com/telekom-mms/ansible-collection-acme/tree/2.3.0) (2021-08-02)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.2.0...2.3.0)

**Implemented enhancements:**

- all chains should be included after convert [\#60](https://github.com/telekom-mms/ansible-collection-acme/pull/60) ([michaelamattes](https://github.com/michaelamattes))

## [2.2.0](https://github.com/telekom-mms/ansible-collection-acme/tree/2.2.0) (2021-07-09)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.1.0...2.2.0)

**Implemented enhancements:**

- enhancement: new variables for letting the user set subject fields [\#57](https://github.com/telekom-mms/ansible-collection-acme/pull/57) ([Zephyr82](https://github.com/Zephyr82))

**Closed issues:**

- Test collection with other acme providers [\#55](https://github.com/telekom-mms/ansible-collection-acme/issues/55)

## [2.1.0](https://github.com/telekom-mms/ansible-collection-acme/tree/2.1.0) (2021-05-30)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.0.1...2.1.0)

**Implemented enhancements:**

- add hetzner dns tests [\#54](https://github.com/telekom-mms/ansible-collection-acme/pull/54) ([rndmh3ro](https://github.com/rndmh3ro))
- add possibility to keep and purge challenge record in Azure [\#52](https://github.com/telekom-mms/ansible-collection-acme/pull/52) ([michaelamattes](https://github.com/michaelamattes))

**Closed issues:**

- add possibility azure dns challenge purge entry [\#51](https://github.com/telekom-mms/ansible-collection-acme/issues/51)

## [2.0.1](https://github.com/telekom-mms/ansible-collection-acme/tree/2.0.1) (2021-05-18)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/2.0.0...2.0.1)

**Fixed bugs:**

- Lookup ZoneID and fix challenge record format. [\#53](https://github.com/telekom-mms/ansible-collection-acme/pull/53) ([smapjb](https://github.com/smapjb))

## [2.0.0](https://github.com/telekom-mms/ansible-collection-acme/tree/2.0.0) (2021-03-26)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/1.0.2...2.0.0)

**Breaking changes:**

- Unify variables [\#44](https://github.com/telekom-mms/ansible-collection-acme/issues/44)
- Rename collection | simplify provider selection | unify variables  [\#46](https://github.com/telekom-mms/ansible-collection-acme/pull/46) ([avalor1](https://github.com/avalor1))

**Implemented enhancements:**

- add possibility to define owner/group for local validation path and local challenge files [\#48](https://github.com/telekom-mms/ansible-collection-acme/pull/48) ([beechesII](https://github.com/beechesII))

**Closed issues:**

- Rename collection to avoid LE trademark [\#43](https://github.com/telekom-mms/ansible-collection-acme/issues/43)
- Simplify challenge provider selection [\#42](https://github.com/telekom-mms/ansible-collection-acme/issues/42)

**Merged pull requests:**

- Adjust collection name for galaxy [\#49](https://github.com/telekom-mms/ansible-collection-acme/pull/49) ([avalor1](https://github.com/avalor1))

## [1.0.2](https://github.com/telekom-mms/ansible-collection-acme/tree/1.0.2) (2021-03-17)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/1.0.1...1.0.2)

**Fixed bugs:**

- Improve Release Action [\#47](https://github.com/telekom-mms/ansible-collection-acme/pull/47) ([schurzi](https://github.com/schurzi))

## [1.0.1](https://github.com/telekom-mms/ansible-collection-acme/tree/1.0.1) (2021-02-05)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/1.0.0...1.0.1)

**Merged pull requests:**

- Add README.md link in role [\#41](https://github.com/telekom-mms/ansible-collection-acme/pull/41) ([avalor1](https://github.com/avalor1))

## [1.0.0](https://github.com/telekom-mms/ansible-collection-acme/tree/1.0.0) (2021-02-05)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.1.0...1.0.0)

**Implemented enhancements:**

- unify challenge provider logic [\#35](https://github.com/telekom-mms/ansible-collection-acme/pull/35) ([schurzi](https://github.com/schurzi))
- Account key content as variable [\#33](https://github.com/telekom-mms/ansible-collection-acme/pull/33) ([Nemental](https://github.com/Nemental))
- Add "local" provider for http-challenge [\#30](https://github.com/telekom-mms/ansible-collection-acme/pull/30) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- Documentation restructuring [\#32](https://github.com/telekom-mms/ansible-collection-acme/issues/32)

**Merged pull requests:**

- Release 1.0 [\#40](https://github.com/telekom-mms/ansible-collection-acme/pull/40) ([avalor1](https://github.com/avalor1))
- use more labels for version-generation [\#39](https://github.com/telekom-mms/ansible-collection-acme/pull/39) ([rndmh3ro](https://github.com/rndmh3ro))
- Documentation restructuring [\#37](https://github.com/telekom-mms/ansible-collection-acme/pull/37) ([avalor1](https://github.com/avalor1))
- use ternary to simplify tasks for directory usage, remove comments [\#36](https://github.com/telekom-mms/ansible-collection-acme/pull/36) ([rndmh3ro](https://github.com/rndmh3ro))
- use version for github action, short sha is no longer supported [\#34](https://github.com/telekom-mms/ansible-collection-acme/pull/34) ([schurzi](https://github.com/schurzi))

## [0.1.0](https://github.com/telekom-mms/ansible-collection-acme/tree/0.1.0) (2021-01-25)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.8...0.1.0)

**Implemented enhancements:**

- Feature / dns challenge otc openstack [\#31](https://github.com/telekom-mms/ansible-collection-acme/pull/31) ([Nemental](https://github.com/Nemental))

**Merged pull requests:**

- update documentation [\#28](https://github.com/telekom-mms/ansible-collection-acme/pull/28) ([avalor1](https://github.com/avalor1))

## [0.0.8](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.8) (2021-01-11)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.7...0.0.8)

**Closed issues:**

- Integration Tests for role [\#3](https://github.com/telekom-mms/ansible-collection-acme/issues/3)

**Merged pull requests:**

- fix galaxy-release action [\#29](https://github.com/telekom-mms/ansible-collection-acme/pull/29) ([rndmh3ro](https://github.com/rndmh3ro))
- adjust variable naming in example files and readme [\#27](https://github.com/telekom-mms/ansible-collection-acme/pull/27) ([avalor1](https://github.com/avalor1))
- Create runtime.yml [\#26](https://github.com/telekom-mms/ansible-collection-acme/pull/26) ([rndmh3ro](https://github.com/rndmh3ro))
- Create LICENSE [\#25](https://github.com/telekom-mms/ansible-collection-acme/pull/25) ([rndmh3ro](https://github.com/rndmh3ro))
- run tests on a schedule [\#24](https://github.com/telekom-mms/ansible-collection-acme/pull/24) ([rndmh3ro](https://github.com/rndmh3ro))
- build integration tests [\#23](https://github.com/telekom-mms/ansible-collection-acme/pull/23) ([rndmh3ro](https://github.com/rndmh3ro))

## [0.0.7](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.7) (2020-12-15)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.6...0.0.7)

**Fixed bugs:**

- fix broken AutoDNS wildcard creation \#20 [\#21](https://github.com/telekom-mms/ansible-collection-acme/pull/21) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- creation of wildcard certificates with autodns challenge not working with release 0.0.5 [\#20](https://github.com/telekom-mms/ansible-collection-acme/issues/20)

## [0.0.6](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.6) (2020-12-15)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.5...0.0.6)

**Implemented enhancements:**

- Add Hetzner DNS as letsencrypt\_dns\_provider [\#22](https://github.com/telekom-mms/ansible-collection-acme/pull/22) ([stndrf](https://github.com/stndrf))

## [0.0.5](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.5) (2020-12-09)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.4...0.0.5)

**Implemented enhancements:**

- Push to Galaxy Fails [\#13](https://github.com/telekom-mms/ansible-collection-acme/issues/13)
- add second checkout to solve race condition \(version gets updated but… [\#15](https://github.com/telekom-mms/ansible-collection-acme/pull/15) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- subject\_alt\_name not optional [\#9](https://github.com/telekom-mms/ansible-collection-acme/issues/9)

**Merged pull requests:**

- fix ansible error if group is empty [\#19](https://github.com/telekom-mms/ansible-collection-acme/pull/19) ([avalor1](https://github.com/avalor1))
- remove common\_name variable [\#18](https://github.com/telekom-mms/ansible-collection-acme/pull/18) ([avalor1](https://github.com/avalor1))
- remove letsencrypt\_create\_private\_keys variable from examples [\#17](https://github.com/telekom-mms/ansible-collection-acme/pull/17) ([avalor1](https://github.com/avalor1))

## [0.0.4](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.4) (2020-11-12)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.3...0.0.4)

**Implemented enhancements:**

- add description of force\_renewal variable [\#12](https://github.com/telekom-mms/ansible-collection-acme/pull/12) ([avalor1](https://github.com/avalor1))

**Merged pull requests:**

- update checkout version for release workflow [\#11](https://github.com/telekom-mms/ansible-collection-acme/pull/11) ([avalor1](https://github.com/avalor1))
- update checkout version in galaxy push workflow [\#10](https://github.com/telekom-mms/ansible-collection-acme/pull/10) ([avalor1](https://github.com/avalor1))

## [0.0.3](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.3) (2020-11-12)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.2...0.0.3)

**Closed issues:**

- Remove unwanted files from release-tarball  [\#4](https://github.com/telekom-mms/ansible-collection-acme/issues/4)

**Merged pull requests:**

- Add Azure dns provider challenge [\#8](https://github.com/telekom-mms/ansible-collection-acme/pull/8) ([michaelamattes](https://github.com/michaelamattes))

## [0.0.2](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.2) (2020-11-06)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/0.0.1...0.0.2)

**Merged pull requests:**

- remove variable letsencrypt\_create\_private\_keys [\#7](https://github.com/telekom-mms/ansible-collection-acme/pull/7) ([avalor1](https://github.com/avalor1))
- add build\_ignore to filter unwanted files from release-tarball [\#6](https://github.com/telekom-mms/ansible-collection-acme/pull/6) ([avalor1](https://github.com/avalor1))

## [0.0.1](https://github.com/telekom-mms/ansible-collection-acme/tree/0.0.1) (2020-11-04)

[Full Changelog](https://github.com/telekom-mms/ansible-collection-acme/compare/6c0445f6769360d1b8ea12df58483ac4a8b602f3...0.0.1)

**Merged pull requests:**

- Workflows [\#2](https://github.com/telekom-mms/ansible-collection-acme/pull/2) ([avalor1](https://github.com/avalor1))
- add Workflows [\#1](https://github.com/telekom-mms/ansible-collection-acme/pull/1) ([avalor1](https://github.com/avalor1))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
