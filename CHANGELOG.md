# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.5] - 2020-08-04

### Added

- Add `vault-token-reviewer` service account and cluster-role binding.

### Changed

- Avoid using the 'plan' option in the vault VM in Azure when CoreOS is still in use.

## [1.0.4] - 2020-08-03

### Fixed

- Wait longer for `calico-node` pods being ready.

## [1.0.3] - 2020-08-03

- Improve max-pod-limit for kubelet on AWS platform to work with AWS CNI limitations.

## [1.0.2] - 2020-07-27

### Added

- Run `node-exporter` on bastions.

## [1.0.1] - 2020-07-23

### Added

- Export `giantnetes-terraform` release version into `/etc/gs-release-version` file on master/worker filesystem.

### Fixed

- Fix ingress controller resource rename from daemonset to deployment. 

## [1.0.0] - 2020-07-20

### Added

- Add github release workflows.

[Unreleased]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.5...HEAD
[1.0.5]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/giantswarm/giantnetes-terraform/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/giantswarm/giantnetes-terraform/releases/tag/v1.0.0