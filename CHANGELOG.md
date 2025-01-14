# Changelog

## [v1.4.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.4.0) (2022-11-18)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v1.3.1...v1.4.0)

**Implemented enhancements:**

- Allow to configure cpus, memory and gpus [\#99](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/99)
- Add support for security\_opt and devices [\#97](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/97)

**Fixed bugs:**

- Configuration touched in check mode [\#87](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/87)
- Fix issues with newly introduced parameter gpu, memory and cpus [\#101](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/101) ([tobiashuste](https://github.com/tobiashuste))
- Specify version explicitly in Debian apt pinning [\#92](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/92) ([tobiashuste](https://github.com/tobiashuste))

**Merged pull requests:**

- Allow to configure cpus, memory and gpus [\#100](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/100) ([tobiashuste](https://github.com/tobiashuste))
- Allow to configure docker devices and security\_opts [\#98](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/98) ([tobiashuste](https://github.com/tobiashuste))
- Bump ansible-lint from 6.8.2 to 6.8.6 [\#95](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/95) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump molecule from 4.0.2 to 4.0.3 [\#93](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/93) ([dependabot[bot]](https://github.com/apps/dependabot))
- Use setup-python action version 4 [\#91](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/91) ([tobiashuste](https://github.com/tobiashuste))

## [v1.3.1](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.3.1) (2022-10-19)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v1.3.0...v1.3.1)

**Fixed bugs:**

- Fix touching the runner configuration in check mode [\#88](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/88) ([tobiashuste](https://github.com/tobiashuste))

**Merged pull requests:**

- Prepare release of version 1.3.1 [\#89](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/89) ([tobiashuste](https://github.com/tobiashuste))

## [v1.3.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.3.0) (2022-10-19)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v1.2.0...v1.3.0)

**Implemented enhancements:**

- Allow to configure the listen\_address option [\#82](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/82)

**Merged pull requests:**

- Prepare release of version 1.3.0 [\#85](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/85) ([tobiashuste](https://github.com/tobiashuste))
- Bump molecule from 4.0.1 to 4.0.2 [\#84](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/84) ([dependabot[bot]](https://github.com/apps/dependabot))
- Allow to configure the listen\_address [\#83](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/83) ([tobiashuste](https://github.com/tobiashuste))
- Bump ansible-lint from 6.8.1 to 6.8.2 [\#81](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/81) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 6.4.0 to 6.5.0 [\#80](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/80) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.7.0 to 6.8.1 [\#79](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/79) ([dependabot[bot]](https://github.com/apps/dependabot))
- Add codeowners [\#77](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/77) ([tobiashuste](https://github.com/tobiashuste))

## [v1.2.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.2.0) (2022-10-05)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v1.1.0...v1.2.0)

**Fixed bugs:**

- Use template module instead of copy [\#66](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/66) ([tobiashuste](https://github.com/tobiashuste))

**Merged pull requests:**

- Prepare release of version 1.2.0 [\#74](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/74) ([tobiashuste](https://github.com/tobiashuste))
- Fix GitHub Actions tests [\#72](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/72) ([tobiashuste](https://github.com/tobiashuste))
- Bump molecule-podman from 2.0.2 to 2.0.3 [\#70](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/70) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.6.0 to 6.7.0 [\#69](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/69) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.5.2 to 6.6.0 [\#65](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/65) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 6.3.0 to 6.4.0 [\#64](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/64) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump yamllint from 1.27.1 to 1.28.0 [\#63](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/63) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.5.1 to 6.5.2 [\#62](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/62) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.4.0 to 6.5.1 [\#61](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/61) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 6.2.0 to 6.3.0 [\#60](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/60) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 6.1.0 to 6.2.0 [\#58](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/58) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.3.0 to 6.4.0 [\#57](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/57) ([dependabot[bot]](https://github.com/apps/dependabot))
- Specify molecule-podman dependency explicitly [\#56](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/56) ([tobiashuste](https://github.com/tobiashuste))
- Bump molecule from 4.0.0 to 4.0.1 [\#55](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/55) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 5.9.0 to 6.1.0 [\#54](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/54) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump yamllint from 1.26.3 to 1.27.1 [\#53](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/53) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.1.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.1.0) (2022-07-01)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v1.0.0...v1.1.0)

**Implemented enhancements:**

- Support configuration of shm\_size parameter [\#50](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/50)

**Merged pull requests:**

- Release version 1.1.0 [\#52](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/52) ([tobiashuste](https://github.com/tobiashuste))
- Always use the latest version of geerlingguy.docker dependency [\#49](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/49) ([Normo](https://github.com/Normo))

## [v1.0.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v1.0.0) (2022-06-29)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.6.0...v1.0.0)

**Implemented enhancements:**

- Switch from molecule-docker to molecule-podman [\#36](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/36)
- Add support for Debian 11 [\#42](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/42)
- Add support for Ubuntu 22.04 [\#40](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/40)
- Add support for Debian 11 [\#43](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/43) ([tobiashuste](https://github.com/tobiashuste))
- Add support for Ubuntu 22.04 [\#41](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/41) ([tobiashuste](https://github.com/tobiashuste))
- Use molecule-podman instead of molecule-docker [\#37](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/37) ([tobiashuste](https://github.com/tobiashuste))

**Closed issues:**

- Do not install docker dependency automatically [\#47](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/47)
- Release version 1.0.0 [\#45](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/45)

**Merged pull requests:**

- Release version 1.0.0 [\#46](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/46) ([tobiashuste](https://github.com/tobiashuste))
- Install docker-machine version 0.16.2-gitlab.15 [\#44](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/44) ([tobiashuste](https://github.com/tobiashuste))
- Install container-linux-config-transpiler v0.9.3 [\#39](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/39) ([tobiashuste](https://github.com/tobiashuste))

## [v0.6.0](https://github.com/hifis-net/ansible-role-gitlab-runner/tree/v0.6.0) (2022-06-17)

[Full Changelog](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.5.1...v0.6.0)

**Implemented enhancements:**

- Link issue\_tracker URL to GitHub [\#31](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/31)
- Add badges to README [\#11](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/11)
- Implement a daily scheduled run of the CI pipeline [\#6](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/6)
- Update dependencies via Dependabot [\#5](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/5)
- Migrate changelog to github-changelog-generator [\#21](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/21) ([tobiashuste](https://github.com/tobiashuste))
- Skip runner registration in molecule test run [\#14](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/14) ([tobiashuste](https://github.com/tobiashuste))
- Add badges to README [\#12](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/12) ([tobiashuste](https://github.com/tobiashuste))
- Use caching feature of setup-python action [\#10](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/10) ([tobiashuste](https://github.com/tobiashuste))

**Fixed bugs:**

- CI pipeline in forks fails [\#9](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/9)

**Closed issues:**

- Release version 0.6.0 [\#23](https://github.com/hifis-net/ansible-role-gitlab-runner/issues/23)

**Merged pull requests:**

- Bump ansible from 5.8.0 to 5.9.0 [\#34](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/34) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump molecule from 3.6.1 to 4.0.0 [\#33](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/33) ([dependabot[bot]](https://github.com/apps/dependabot))
- Update issue tracker link in the Galaxy meta information [\#32](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/32) ([tobiashuste](https://github.com/tobiashuste))
- Release version 0.6.0 [\#30](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/30) ([tobiashuste](https://github.com/tobiashuste))
- Bump ansible-lint from 6.2.1 to 6.3.0 [\#29](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/29) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump robertdebock/galaxy-action from 1.2.0 to 1.2.1 [\#27](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/27) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump reuse from 0.14.0 to 1.0.0 [\#26](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/26) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 5.7.1 to 5.8.0 [\#25](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/25) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 6.0.2 to 6.2.1 [\#24](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/24) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 5.7.0 to 5.7.1 [\#19](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/19) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 5.6.0 to 5.7.0 [\#18](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/18) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump molecule from 3.5.2 to 3.6.1 [\#17](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/17) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-lint from 5.3.1 to 6.0.2 [\#16](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/16) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 5.1.0 to 5.6.0 [\#15](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/15) ([dependabot[bot]](https://github.com/apps/dependabot))
- fixes\(\#5\): added dependabot.yml [\#8](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/8) ([tharun634](https://github.com/tharun634))
- fixes\(\#6\): CI daily run [\#7](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/7) ([tharun634](https://github.com/tharun634))
- Implement full lint and test workflow via GitHub Actions [\#1](https://github.com/hifis-net/ansible-role-gitlab-runner/pull/1) ([tobiashuste](https://github.com/tobiashuste))

## [0.5.1](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.5.1) - 2022-03-17

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.5.0...v0.5.1)

### Fixed

* Fix install from deb file if version is older than installed
  ([!55](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/55)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.5.0](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.5.0) - 2022-03-16

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.4.0...v0.5.0)

### Added

* Add support for optionally installing gitlab-runner via a `.deb` file
  ([!53](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/53)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.4.0](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.4.0) - 2022-03-03

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.3.0...v0.4.0)

### Changed

* Allow to update the installed GPG keys
  ([!52](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/52)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.3.0](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.3.0) - 2022-01-11

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.2.2...v0.3.0)

### Added

* Add support for docker `tls_verify` parameter
  ([!46](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/46)
  by [Normo](https://gitlab.com/Normo)).

### Changed

* Bump geerlingguy.docker to version 4.1.1
  ([!48](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/48)
  by [Normo](https://gitlab.com/Normo)).
* Bump container linux config transpiler to v0.9.2
  ([!47](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/47)
  by [Normo](https://gitlab.com/Normo)).
* Bump Python dependencies to the latest version
  ([!50](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/50)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

### Fixed

* Fix debian docker issue in GitLab CI and bump runner version in tests
  ([!49](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/49)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.2.2](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.2.2) - 2021-07-30

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.2.1...v0.2.2)

### Fixed

* Fix failing binfmt-init.service for multiarch support
  ([!44](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/44)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.2.1](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.2.1) - 2021-07-30

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.2.0...v0.2.1)

### Fixed

* Correctly configure MTU and registry mirror for Docker-in-Docker
  ([!43](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/43)
  by [tobiashuste](https://gitlab.com/tobiashuste)).
* Fix bug when `cache_type` is undefined
  ([!42](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/42)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.2.0](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.2.0) - 2021-07-28

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/v0.1.0...v0.2.0)

### Added
* Allow to configure autoscaling parameters
  ([!36](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/36)
  by [tobiashuste](https://gitlab.com/tobiashuste)).
* Create a test machine via docker-machine once
  ([!39](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/39)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

### Changed
* Reference latest version of gitlab-runner throughout the role
  ([!38](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/38)
  by [tobiashuste](https://gitlab.com/tobiashuste)).
* Skip ignition check tasks if flatcar config is unchanged
  ([!37](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/37)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

### Fixed
* Document the `limit` parameter
  ([!40](https://gitlab.com/hifis/ansible/gitlab-ci-openstack/-/merge_requests/40)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.1.0](https://github.com/hifis-net/ansible-role-gitlab-runner/releases/v0.1.0) - 2021-07-20

[List of commits](https://github.com/hifis-net/ansible-role-gitlab-runner/compare/359ac4d5e6371452d5488fcf7daa3a43d935ddc1...v0.1.0)

### Added
Initial release of the Ansible GitLab-Runner Role.


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
