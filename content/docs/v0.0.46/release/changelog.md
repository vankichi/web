---
title: "Changelog_content/Docs/V0.0.46/Release"
date: 2020-07-21T18:17:27+09:00
draft: true
weight: 0
menu:
  release:
    parent: Release
---

# CHANGELOG

## v0.0.46

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.46`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.46`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.46`
gateway | `docker pull vdaas/vald-gateway:v0.0.46`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.46`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.46`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.46`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.46`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.46`
index manager | `docker pull vdaas/vald-manager-index:v0.0.46`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.46`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.46)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.46/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.46/charts/vald-helm-operator/README)

### Changes
- Test/internal/tcp ([#501](https://github.com/vdaas/vald/pull/501))
- :white_check_mark: add internal/cache/gache test ([#583](https://github.com/vdaas/vald/pull/583))
- :white_check_mark: add cache test ([#576](https://github.com/vdaas/vald/pull/576))
- :white_check_mark: add internal/cache/gache/option test ([#575](https://github.com/vdaas/vald/pull/575))
- :bug: :white_check_mark: fix: fails test ([#578](https://github.com/vdaas/vald/pull/578))
- :white_check_mark: Add test for `internal/file/watch` ([#526](https://github.com/vdaas/vald/pull/526))
- :art: update k8s manifests only on publish tags ([#574](https://github.com/vdaas/vald/pull/574))
- :robot: Automatically update k8s manifests ([#572](https://github.com/vdaas/vald/pull/572))
- :robot: Automatically update k8s manifests ([#571](https://github.com/vdaas/vald/pull/571))
- :robot: Automatically update PULL_REQUEST_TEMPLATE and ISSUE_TEMPLATE ([#570](https://github.com/vdaas/vald/pull/570))


## v0.0.45

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.45`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.45`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.45`
gateway | `docker pull vdaas/vald-gateway:v0.0.45`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.45`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.45`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.45`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.45`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.45`
index manager | `docker pull vdaas/vald-manager-index:v0.0.45`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.45`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.45)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.45/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.45/charts/vald-helm-operator/README)

### Changes
- bugfix gateway & internal/net/grpc ([#569](https://github.com/vdaas/vald/pull/569))
- fix update-k8s workflow & update sample manifests ([#567](https://github.com/vdaas/vald/pull/567))
- :white_check_mark: Add test for `internal/config/mysql.go` ([#563](https://github.com/vdaas/vald/pull/563))
- :bug: :white_check_mark: fix failed test ([#561](https://github.com/vdaas/vald/pull/561))
- :white_check_mark: internal/tls test ([#485](https://github.com/vdaas/vald/pull/485))
- pass tparse by tee command ([#562](https://github.com/vdaas/vald/pull/562))
- fix global cache ([#560](https://github.com/vdaas/vald/pull/560))
- :white_check_mark: add internal/config/ngt test ([#554](https://github.com/vdaas/vald/pull/554))
- :white_check_mark: internal/cache/cacher test ([#553](https://github.com/vdaas/vald/pull/553))
- :white_check_mark: Add test case for `internal/file` ([#550](https://github.com/vdaas/vald/pull/550))
- :white_check_mark: add internal/singleflight test ([#542](https://github.com/vdaas/vald/pull/542))
- not to force rebuild gotests ([#548](https://github.com/vdaas/vald/pull/548))
- :pencil: Add use case document ([#482](https://github.com/vdaas/vald/pull/482))
- :white_check_mark: add internal/log/mock/retry test ([#549](https://github.com/vdaas/vald/pull/549))
- feat: options test ([#518](https://github.com/vdaas/vald/pull/518))
- :white_check_mark: add log/mock/logger test ([#538](https://github.com/vdaas/vald/pull/538))
- :bug: Fix condition check of chatops ([#544](https://github.com/vdaas/vald/pull/544))
- exclude hack codes ([#543](https://github.com/vdaas/vald/pull/543))


## v0.0.44

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.44`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.44`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.44`
gateway | `docker pull vdaas/vald-gateway:v0.0.44`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.44`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.44`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.44`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.44`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.44`
index manager | `docker pull vdaas/vald-manager-index:v0.0.44`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.44`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.44)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.44/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.44/charts/vald-helm-operator/README)

### Changes
- use Len and InsertVCacheLen method for IndexInfo / add mutex for (Create|Save)Index ([#536](https://github.com/vdaas/vald/pull/536))
- documentation: tutorial/agent-on-docker ([#516](https://github.com/vdaas/vald/pull/516))
- Revise log messages along with the coding guideline ([#504](https://github.com/vdaas/vald/pull/504))
- :art: Add images of usecase ([#537](https://github.com/vdaas/vald/pull/537))
- :white_check_mark: add internal/config/tls test ([#534](https://github.com/vdaas/vald/pull/534))
- :bug: Add cancel hook for file watcher ([#535](https://github.com/vdaas/vald/pull/535))
- :green_heart: Add test workflow ([#531](https://github.com/vdaas/vald/pull/531))
- added internal/config/log test ([#530](https://github.com/vdaas/vald/pull/530))
- add codeql config ([#532](https://github.com/vdaas/vald/pull/532))
- Added test case for `internal/info` pacakge. ([#514](https://github.com/vdaas/vald/pull/514))
- Add `internal/runner` test ([#505](https://github.com/vdaas/vald/pull/505))
- Added test case for `internal/unit` pacakge ([#515](https://github.com/vdaas/vald/pull/515))


## v0.0.43

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.43`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.43`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.43`
gateway | `docker pull vdaas/vald-gateway:v0.0.43`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.43`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.43`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.43`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.43`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.43`
index manager | `docker pull vdaas/vald-manager-index:v0.0.43`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.43`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.43)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.43/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.43/charts/vald-helm-operator/README)

### Changes
- Revise S3 reader/writer: compatible with IBM Cloud Object Storage ([#509](https://github.com/vdaas/vald/pull/509))
- :bug: Close [#502](https://github.com/vdaas/vald/pull/502) / Fix roundtrip error handling (#508)
- Feature/drawio ([#500](https://github.com/vdaas/vald/pull/500))
- Added test case for `internal/errorgroup`  ([#494](https://github.com/vdaas/vald/pull/494))
- Update Helm Chart info ([#496](https://github.com/vdaas/vald/pull/496))
- Revise triggers of workflow run & Fix reading changelogs from PR comments ([#495](https://github.com/vdaas/vald/pull/495))


## v0.0.42

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.42`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.42`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.42`
gateway | `docker pull vdaas/vald-gateway:v0.0.42`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.42`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.42`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.42`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.42`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.42`
index manager | `docker pull vdaas/vald-manager-index:v0.0.42`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.42`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.42)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.42/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.42/charts/vald-helm-operator/README)

### Changes
- ✨ Add Stackdriver Monitoring, Tracing and Profiler support ([#479](https://github.com/vdaas/vald/pull/479))
- :green_heart: Add CodeQL workflow instead of LGTM.com ([#486](https://github.com/vdaas/vald/pull/486))
- Add `internal/params` pacakge test ([#474](https://github.com/vdaas/vald/pull/474))
- :sparkles: aws region can be specified with empty string ([#477](https://github.com/vdaas/vald/pull/477))
- Fix failed test case of internal/safety package ([#464](https://github.com/vdaas/vald/pull/464))
- send a request to GoProxy after a new version is published ([#475](https://github.com/vdaas/vald/pull/475))
- internal/db/storage/blob/s3: remove ctx from struct ([#473](https://github.com/vdaas/vald/pull/473))


## v0.0.41

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.41`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.41`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.41`
gateway | `docker pull vdaas/vald-gateway:v0.0.41`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.41`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.41`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.41`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.41`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.41`
index manager | `docker pull vdaas/vald-manager-index:v0.0.41`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.41`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.41)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.41/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.41/charts/vald-helm-operator/README)

### Changes
- Refactor agent-sidecar: fix S3 reader & add backoff logic ([#467](https://github.com/vdaas/vald/pull/467))
- :bug: :pencil: fix link ([#471](https://github.com/vdaas/vald/pull/471))
- Fix /changelog command format ([#470](https://github.com/vdaas/vald/pull/470))
- fix: failing test ([#469](https://github.com/vdaas/vald/pull/469))
- fix: failing test ([#468](https://github.com/vdaas/vald/pull/468))
- ✨ Add options for AWS client ([#460](https://github.com/vdaas/vald/pull/460))
- Fix /format command ([#466](https://github.com/vdaas/vald/pull/466))
- Fix /format command ([#465](https://github.com/vdaas/vald/pull/465))
- Fix `internal/log/retry` pacakge ([#458](https://github.com/vdaas/vald/pull/458))
- [ImgBot] Optimize images ([#461](https://github.com/vdaas/vald/pull/461))
- :art: trim white margin at data flow images ([#459](https://github.com/vdaas/vald/pull/459))


## v0.0.40

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.40`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.40`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.40`
gateway | `docker pull vdaas/vald-gateway:v0.0.40`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.40`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.40`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.40`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.40`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.40`
index manager | `docker pull vdaas/vald-manager-index:v0.0.40`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.40`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.40)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.40/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.40/charts/vald-helm-operator/README)

### Changes
- Documentation: add concept section to the architecture document ([#438](https://github.com/vdaas/vald/pull/438))
- feat: level pacakge test ([#455](https://github.com/vdaas/vald/pull/455))
- [ImgBot] Optimize images ([#457](https://github.com/vdaas/vald/pull/457))
- fix document and added png images ([#456](https://github.com/vdaas/vald/pull/456))
- Fix test template bug ([#452](https://github.com/vdaas/vald/pull/452))
- Add WithOperation func to loadtest usecase ([#454](https://github.com/vdaas/vald/pull/454))
- :bug: Fix k8s manifests for loadtest jobs ([#453](https://github.com/vdaas/vald/pull/453))
- bugfix change final stage of loadtest ([#451](https://github.com/vdaas/vald/pull/451))
- :bug: Fix bug on /changelog command ([#450](https://github.com/vdaas/vald/pull/450))
- add loadtest job and container ([#449](https://github.com/vdaas/vald/pull/449))
- 🐛 Fix bug on changelog command ([#448](https://github.com/vdaas/vald/pull/448))


## v0.0.39

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.39`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.39`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.39`
gateway | `docker pull vdaas/vald-gateway:v0.0.39`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.39`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.39`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.39`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.39`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.39`
index manager | `docker pull vdaas/vald-manager-index:v0.0.39`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.39`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.39)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.39/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.39/charts/vald-helm-operator/README)

### Changes
- [patch] fix doc file path ([#444](https://github.com/vdaas/vald/pull/444))
- Add changelog command (ChatOps) ([#447](https://github.com/vdaas/vald/pull/447))
- Fix inconsistent wording ([#442](https://github.com/vdaas/vald/pull/442))
- [ImgBot] Optimize images ([#443](https://github.com/vdaas/vald/pull/443))
- [Document] Apply design template to flow diagram ([#441](https://github.com/vdaas/vald/pull/441))
- Document to deploy standalone agent ([#407](https://github.com/vdaas/vald/pull/407))
- implement load tester prototype ([#363](https://github.com/vdaas/vald/pull/363))
- 🐛  Add gRPC interceptor to recover panic in handlers ([#440](https://github.com/vdaas/vald/pull/440))
- tensorflow test ([#378](https://github.com/vdaas/vald/pull/378))
- :bento: update architecture overview svg to add agent sidecar ([#437](https://github.com/vdaas/vald/pull/437))
- Example program: Add indexing interval description & fix logging message ([#405](https://github.com/vdaas/vald/pull/405))
- :pencil2: Fix typo ([#436](https://github.com/vdaas/vald/pull/436))


## v0.0.38

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.38`
agent sidecar | `docker pull vdaas/vald-agent-sidecar:v0.0.38`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.38`
gateway | `docker pull vdaas/vald-gateway:v0.0.38`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.38`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.38`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.38`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.38`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.38`
index manager | `docker pull vdaas/vald-manager-index:v0.0.38`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.38`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.38)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.38/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.38/charts/vald-helm-operator/README)

### Changes
- send PR when K8s manifests are updated ([#435](https://github.com/vdaas/vald/pull/435))
- Implementation of agent-sidecar storage backup logic ([#409](https://github.com/vdaas/vald/pull/409))
- Fix structure of grpc java package ([#431](https://github.com/vdaas/vald/pull/431))
- Remove AUTHORS/CONTRIBUTORS file ([#428](https://github.com/vdaas/vald/pull/428))
- Contribute document ([#390](https://github.com/vdaas/vald/pull/390))
- Separate the component section from architecture doc ([#430](https://github.com/vdaas/vald/pull/430))
- fix: delete fch channel because fch causes channel blocking ([#429](https://github.com/vdaas/vald/pull/429))
- Update Operator SDK version ([#412](https://github.com/vdaas/vald/pull/412))
- Documentation: About vald ([#374](https://github.com/vdaas/vald/pull/374))
- Vald architecture document ([#366](https://github.com/vdaas/vald/pull/366))
- Add JSON schema for Vald Helm Chart ([#365](https://github.com/vdaas/vald/pull/365))
- Revise ChatOps not to add go.mod & go.sum when /format runs ([#406](https://github.com/vdaas/vald/pull/406))
- add agent sidecar flame for implementation ([#404](https://github.com/vdaas/vald/pull/404))
- Upgrade Operator SDK version / Remove useless GO111MODULE=off ([#402](https://github.com/vdaas/vald/pull/402))
- Upgrade tools version ([#399](https://github.com/vdaas/vald/pull/399))
- Add app.kubernetes.io/xxx labels to all resources ([#397](https://github.com/vdaas/vald/pull/397))
- Vald contacts document ([#373](https://github.com/vdaas/vald/pull/373))
- add trace spans and metrics for agent-ngt and index-manager ([#389](https://github.com/vdaas/vald/pull/389))
- Add gen-test command for chatops ([#379](https://github.com/vdaas/vald/pull/379))
- Add internal/db/storage/blob ([#388](https://github.com/vdaas/vald/pull/388))


## v0.0.37

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.37`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.37`
gateway | `docker pull vdaas/vald-gateway:v0.0.37`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.37`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.37`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.37`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.37`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.37`
index manager | `docker pull vdaas/vald-manager-index:v0.0.37`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.37`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.37)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.37/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.37/charts/vald-helm-operator/README)

### Changes
- add agent auto save indexing feature ([#385](https://github.com/vdaas/vald/pull/385))
- :bug: fix ngt `distance_type` ([#384](https://github.com/vdaas/vald/pull/384))
- Add topology spread constraints ([#383](https://github.com/vdaas/vald/pull/383))


## v0.0.36

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.36`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.36`
gateway | `docker pull vdaas/vald-gateway:v0.0.36`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.36`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.36`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.36`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.36`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.36`
index manager | `docker pull vdaas/vald-manager-index:v0.0.36`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.36`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.36)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.36/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.36/charts/vald-helm-operator/README)

### Changes
- update dependencies version ([#381](https://github.com/vdaas/vald/pull/381))
- Fix missing value on compressor health servers ([#377](https://github.com/vdaas/vald/pull/377))
- Fix compressor readiness shutdown_duration / Fix cassandra … ([#376](https://github.com/vdaas/vald/pull/376))
- Bump gopkg.in/yaml.v2 from 2.2.8 to 2.3.0 ([#375](https://github.com/vdaas/vald/pull/375))
- Fix`internal/log/format` to match the test template ([#369](https://github.com/vdaas/vald/pull/369))
- Fix `internal/log/logger` to match the test template ([#371](https://github.com/vdaas/vald/pull/371))
- Fix failing tests of `internal/log` and modified to match the test template  ([#368](https://github.com/vdaas/vald/pull/368))
- Add enabled flag to each component in Helm chart ([#372](https://github.com/vdaas/vald/pull/372))
- Add configurations ([#356](https://github.com/vdaas/vald/pull/356))


## v0.0.35

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.35`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.35`
gateway | `docker pull vdaas/vald-gateway:v0.0.35`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.35`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.35`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.35`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.35`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.35`
index manager | `docker pull vdaas/vald-manager-index:v0.0.35`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.35`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.35)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.35/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.35/charts/vald-helm-operator/README)

### Changes
- add storage backup option to agent ([#367](https://github.com/vdaas/vald/pull/367))
- Add client-node dispatcher ([#370](https://github.com/vdaas/vald/pull/370))
- Bump github.com/tensorflow/tensorflow ([#364](https://github.com/vdaas/vald/pull/364))
- change fmt.Errorf to errors.Errorf ([#361](https://github.com/vdaas/vald/pull/361))
- add goleak ([#359](https://github.com/vdaas/vald/pull/359))


## v0.0.34

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.34`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.34`
gateway | `docker pull vdaas/vald-gateway:v0.0.34`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.34`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.34`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.34`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.34`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.34`
index manager | `docker pull vdaas/vald-manager-index:v0.0.34`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.34`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.34)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.34/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.34/charts/vald-helm-operator/README)

### Changes
- feature/internal/cassandra/add option ([#358](https://github.com/vdaas/vald/pull/358))
- update helm docs when version is published ([#355](https://github.com/vdaas/vald/pull/355))
- upgrade tools ([#354](https://github.com/vdaas/vald/pull/354))
- bugfix protoc-gen-validate resolve failure ([#353](https://github.com/vdaas/vald/pull/353))
- Fix conflicts between formatter and helm template ([#350](https://github.com/vdaas/vald/pull/350))
- Add more options and remove valdhelmoperatorrelease, valdrelease from vald-helm-operator chart ([#334](https://github.com/vdaas/vald/pull/334))


## v0.0.33

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.33`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.33`
gateway | `docker pull vdaas/vald-gateway:v0.0.33`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.33`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.33`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.33`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.33`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.33`
index manager | `docker pull vdaas/vald-manager-index:v0.0.33`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.33`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.33)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.33/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.33/charts/vald-helm-operator/README)

### Changes
- update k8s dependencies ([#349](https://github.com/vdaas/vald/pull/349))
- create missing test files by the our original test template ([#348](https://github.com/vdaas/vald/pull/348))
- create test template for using gotests ([#327](https://github.com/vdaas/vald/pull/327))
- Revise coverage CI settings ([#347](https://github.com/vdaas/vald/pull/347))
- fix tensorflow.go, option.go ([#261](https://github.com/vdaas/vald/pull/261))


## v0.0.32

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.32`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.32`
gateway | `docker pull vdaas/vald-gateway:v0.0.32`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.32`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.32`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.32`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.32`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.32`
index manager | `docker pull vdaas/vald-manager-index:v0.0.32`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.32`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.32)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.32/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.32/charts/vald-helm-operator/README)

### Changes
- bugfix ip discoverer disconnection too slow ([#344](https://github.com/vdaas/vald/pull/344))
- Compressor: backup vectors in queue using PostStop function ([#345](https://github.com/vdaas/vald/pull/345))
- Revise backup/meta Cassandra default values ([#336](https://github.com/vdaas/vald/pull/336))


## v0.0.31

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.31`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.31`
gateway | `docker pull vdaas/vald-gateway:v0.0.31`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.31`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.31`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.31`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.31`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.31`
index manager | `docker pull vdaas/vald-manager-index:v0.0.31`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.31`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.31)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.31/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.31/charts/vald-helm-operator/README)

### Changes
- Resolve busy-loop on worker ([#339](https://github.com/vdaas/vald/pull/339))


## v0.0.30

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.30`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.30`
gateway | `docker pull vdaas/vald-gateway:v0.0.30`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.30`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.30`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.30`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.30`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.30`
index manager | `docker pull vdaas/vald-manager-index:v0.0.30`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.30`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.30)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.30/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.30/charts/vald-helm-operator/README)

### Changes
- async compressor
- optimized gRPC pool connection
- update helm chart API version
- internal gRPC client for Vald
- Cassandra NewConvictionPolicy
- dicoverer now returns clone object
- new internal/singleflight package
- new internal/net package
- coding guideline


## v0.0.26

### Docker images

component | docker pull
--------- | -----------
agent NGT | `docker pull vdaas/vald-agent-ngt:v0.0.26`
discoverer K8s | `docker pull vdaas/vald-discoverer-k8s:v0.0.26`
gateway | `docker pull vdaas/vald-gateway:v0.0.26`
backup manager MySQL | `docker pull vdaas/vald-manager-backup-mysql:v0.0.26`
backup manager Cassandra | `docker pull vdaas/vald-manager-backup-cassandra:v0.0.26`
compressor | `docker pull vdaas/vald-manager-compressor:v0.0.26`
meta Redis | `docker pull vdaas/vald-meta-redis:v0.0.26`
meta Cassandra | `docker pull vdaas/vald-meta-cassandra:v0.0.26`
index manager | `docker pull vdaas/vald-manager-index:v0.0.26`
Helm operator | `docker pull vdaas/vald-helm-operator:v0.0.26`

### Documents
- [GoDoc](https://pkg.go.dev/github.com/vdaas/vald@v0.0.26)
- [Helm Chart Reference](https://github.com/vdaas/vald/blob/v0.0.26/charts/vald/README)
- [Helm Operator Chart Reference](https://github.com/vdaas/vald/blob/v0.0.26/charts/vald-helm-operator/README)

### Changes
- added helm operator
- added telepresence
- improved meta-Cassandra performance
- added doc users/get-started
- fixed some bugs
