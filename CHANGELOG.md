# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/google-cloud-bigquery-datatransfer/#history

## [3.1.0](https://www.github.com/googleapis/python-bigquery-datatransfer/compare/v3.0.1...v3.1.0) (2021-03-22)


### Features

* add `client_cert_source_for_mtls` parameter to grpc transport ([#114](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/114)) ([9c7ed28](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/9c7ed285203cd44917911e78c2c313d3ad50afda))

### [3.0.1](https://www.github.com/googleapis/python-bigquery-datatransfer/compare/v3.0.0...v3.0.1) (2021-03-03)


### Bug Fixes

* remove recv msg limit, add enums to `types` ([#84](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/84)) ([3e2bbef](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/3e2bbef292ddda6a736be397be4e5a0fb213eeff))


### Documentation

* add sample for dataset copy ([#76](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/76)) ([f6d2c5b](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/f6d2c5b8f3c75426881dfce90ab713535416950e))
* add scheduled query samples ([#83](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/83)) ([cd51970](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/cd519709228cda3bbcf2fd978d37ccd04ef27c82))
* ensure minimum width for 'Parameters' / 'Returns' column ([#95](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/95)) ([5c8d7c1](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/5c8d7c1e860d1c50d892bfabc7ec936aaa40e714))
* **python:** document adding Python 3.9 support, dropping 3.5 support ([#89](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/89)) ([dd84592](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/dd8459291a3ac0f98606b61ae566cb264ce96825)), closes [#787](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/787)
* remove out-of-date sample from README ([#80](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/80)) ([af0406e](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/af0406eedac1dc8c663b5c8f67f56255caeea2fa))
* remove redundant samples ([#86](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/86)) ([093e407](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/093e407c60b117a00d2cdf8d225f22d61bc221c4))
* update contributing guide to Python 3.8 ([#105](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/105)) ([678c335](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/678c3355e1b2e8525005ad337048d60a51400fc0))

## [3.0.0](https://www.github.com/googleapis/python-bigquery-datatransfer/compare/v2.1.0...v3.0.0) (2020-12-09)


### ⚠ BREAKING CHANGES

* type is renamed to type_ to avoid conflict with built-in functions (introduced in googleapis/gapic-generator-python#595)

### Features

* add common resource path helpers ([#69](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/69)) ([e0bcedb](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/e0bcedb58109e38a58584d5b3087f03e1fa10835))


### Bug Fixes

* avoid collision with built-in functions by renaming type property to type_ ([#53](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/53)) ([b954411](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/b95441140f7c86dd3e833aef0532badd6280ef48)), closes [/github.com/googleapis/python-talent/blob/ef045e8eb348db36d7a2a611e6f26b11530d273b/samples/snippets/noxfile_config.py#L27-L32](https://www.github.com/googleapis//github.com/googleapis/python-talent/blob/ef045e8eb348db36d7a2a611e6f26b11530d273b/samples/snippets/noxfile_config.py/issues/L27-L32)


### Documentation

* update intersphinx links ([#78](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/78)) ([a78ba39](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/a78ba39bf1507cbc9e2a51fe4553d602da7f7601))

## 2.1.0

09-29-2020 09:34 PDT


### Implementation Changes

Adjust gapic namespace to `google.cloud.bigquery_datatransfer` ([#61](https://github.com/googleapis/python-bigquery-datatransfer/pull/61))

## 2.0.0

09-21-2020 08:36 PDT


### Implementation Changes

- Transition the library to microgenerator. ([#56](https://github.com/googleapis/python-bigquery-datatransfer/pull/56))
  This is a **breaking change** that introduces several **method signature changes** and **drops support
  for Python 2.7 and 3.5**. See [migration guide](https://googleapis.dev/python/bigquerydatatransfer/latest/UPGRADING.html)
  for more info.

## 1.1.1

09-16-2020 11:12 PDT


### Implementation Changes

- Change default retry policies timeouts (via synth). ([#48](https://github.com/googleapis/python-bigquery-datatransfer/pull/48))


### Documentation

- Add sample for updating transfer config. ([#46](https://github.com/googleapis/python-bigquery-datatransfer/pull/46))
- Add dataset ID in function call in samples. ([#44](https://github.com/googleapis/python-bigquery-datatransfer/pull/44))
- Move code samples from the common samples repo to this library. ([#38](https://github.com/googleapis/python-bigquery-datatransfer/pull/38))


### Internal / Testing Changes

- Update CODEOWNERS for samples and library code. ([#47](https://github.com/googleapis/python-bigquery-datatransfer/pull/47))

## [1.1.0](https://www.github.com/googleapis/python-bigquery-datatransfer/compare/v1.0.0...v1.1.0) (2020-06-20)


### Features

* add first party oauth ([#22](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/22)) ([a806b8b](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/a806b8b3d0e3213f1488563f25504a27af9a9cda))

## [1.0.0](https://www.github.com/googleapis/python-bigquery-datatransfer/compare/v0.4.1...v1.0.0) (2020-03-04)


### Features

* **bigquerydatatransfer:** add `service_account_name` option to transfer configs ([#10013](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/10013)) ([9ca090a](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/9ca090af431092bc4286fa4443dd0dc0141f6de6))
* **bigquerydatatransfer:** undeprecate resource name helper methods; add py2 deprecation warning; bump copyright year to 2020 (via synth) ([#10226](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/10226)) ([c0f9cc3](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/c0f9cc398e5558002c79a875809bb6cd1a98a8a4))
* set release_status to production/stable ([#15](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/15)) ([a9c1160](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/a9c1160475dbc327e8cc5da3b5aee3ceaa618bd3))


### Bug Fixes

* **bigquery_datatransfer:** deprecate resource name helper methods (via synth) ([#9829](https://www.github.com/googleapis/python-bigquery-datatransfer/issues/9829)) ([fc06995](https://www.github.com/googleapis/python-bigquery-datatransfer/commit/fc0699549479cc3e34e217f9e588f5128107ba89))

## 0.4.1

07-31-2019 17:50 PDT


### Dependencies
- Bump minimum version for google-api-core to 1.14.0. ([#8709](https://github.com/googleapis/google-cloud-python/pull/8709))

### Documentation
- Fix links to BigQuery Datatransfer documentation. ([#8859](https://github.com/googleapis/google-cloud-python/pull/8859))
- Link to googleapis.dev documentation in READMEs. ([#8705](https://github.com/googleapis/google-cloud-python/pull/8705))

### Internal / Testing Changes
- Update intersphinx mapping for requests. ([#8805](https://github.com/googleapis/google-cloud-python/pull/8805))

## 0.4.0

07-16-2019 17:11 PDT

### Implementation Changes

- Retry DEADLINE_EXCEEDED (via synth). ([#7920](https://github.com/googleapis/google-cloud-python/pull/7920))
- Remove classifier for Python 3.4 for end-of-life. ([#7535](https://github.com/googleapis/google-cloud-python/pull/7535))

### New Features

- Add `DatasourceServiceClient` (via synth). ([#8630](https://github.com/googleapis/google-cloud-python/pull/8630))
- Add `start_manual_transfer_runs` method (via synth). ([#8630](https://github.com/googleapis/google-cloud-python/pull/8630))
- Add `client_info`/`version_info` support (via synth). ([#8630](https://github.com/googleapis/google-cloud-python/pull/8630))
- Allow passing kwargs to `create_channel` (via synth). ([#8630](https://github.com/googleapis/google-cloud-python/pull/8630))
- Add path helpers (via synth). ([#8630](https://github.com/googleapis/google-cloud-python/pull/8630))
- Add protos as an artifact to library ([#7205](https://github.com/googleapis/google-cloud-python/pull/7205))

### Documentation

- Add compatibility check badges to READMEs. ([#8288](https://github.com/googleapis/google-cloud-python/pull/8288))
- Adjust indentation on scheduled query sample. ([#8493](https://github.com/googleapis/google-cloud-python/pull/8493))
- Add docs job to publish to googleapis.dev. ([#8464](https://github.com/googleapis/google-cloud-python/pull/8464))
- Add sample to schedule query with BQ DTS. ([#7703](https://github.com/googleapis/google-cloud-python/pull/7703))
- Add nox session `docs` (via synth). ([#7765](https://github.com/googleapis/google-cloud-python/pull/7765))
- Updated client library documentation URLs. ([#7307](https://github.com/googleapis/google-cloud-python/pull/7307))
- Pick up stub docstring fix in GAPIC generator. ([#6965](https://github.com/googleapis/google-cloud-python/pull/6965))

### Internal / Testing Changes

- Blacken noxfile.py, setup.py (via synth). ([#8116](https://github.com/googleapis/google-cloud-python/pull/8116))
- Add empty lines (via synth). ([#8050](https://github.com/googleapis/google-cloud-python/pull/8050))
- Remove unused message exports (via synth). ([#7263](https://github.com/googleapis/google-cloud-python/pull/7263))
- Protoc-generated serialization update. ([#7075](https://github.com/googleapis/google-cloud-python/pull/7075))

## 0.3.0

12-17-2018 17:59 PST


### Implementation Changes
- Pick up enum fixes in the GAPIC generator. ([#6608](https://github.com/googleapis/google-cloud-python/pull/6608))
- Pick up fixes in GAPIC generator. ([#6491](https://github.com/googleapis/google-cloud-python/pull/6491))
- Fix `client_info` bug, update docstrings. ([#6405](https://github.com/googleapis/google-cloud-python/pull/6405))
- Re-generate library using bigquery_datatransfer/synth.py ([#5973](https://github.com/googleapis/google-cloud-python/pull/5973))
- Fix stray, lint-breaking blank lines from autosynth. ([#5960](https://github.com/googleapis/google-cloud-python/pull/5960))
- Re-generate library using `bigquery_datatransfer/synth.py`. ([#5947](https://github.com/googleapis/google-cloud-python/pull/5947))

### Dependencies
- Bump minimum api_core version for all GAPIC libs to 1.4.1. ([#6391](https://github.com/googleapis/google-cloud-python/pull/6391))

### Documentation
- Document Python 2 deprecation ([#6910](https://github.com/googleapis/google-cloud-python/pull/6910))
- Fix GAX fossils ([#6264](https://github.com/googleapis/google-cloud-python/pull/6264))
- Normalize use of support level badges ([#6159](https://github.com/googleapis/google-cloud-python/pull/6159))
- Harmonize / DRY 'README.rst' / 'docs/index.rst'. ([#6013](https://github.com/googleapis/google-cloud-python/pull/6013))

### Internal / Testing Changes
- Update noxfile.
- Blacken all gen'd libs ([#6792](https://github.com/googleapis/google-cloud-python/pull/6792))
- Omit local deps ([#6701](https://github.com/googleapis/google-cloud-python/pull/6701))
- Run black at end of synth.py ([#6698](https://github.com/googleapis/google-cloud-python/pull/6698))
- Unblack bigquery gapic and protos.
- Run Black on Generated libraries ([#6666](https://github.com/googleapis/google-cloud-python/pull/6666))
- Add templates for flake8, coveragerc, noxfile, and black. ([#6642](https://github.com/googleapis/google-cloud-python/pull/6642))
- Add synth metadata. ([#6562](https://github.com/googleapis/google-cloud-python/pull/6562))
- Use new Nox ([#6175](https://github.com/googleapis/google-cloud-python/pull/6175))

## 0.2.0

### Implementation Changes
- Regenerate bigquery-datatransfer (#5793)

### Internal / Testing Changes
- Avoid overwriting '__module__' of messages from shared modules. (#5364)
- Modify system tests to use prerelease versions of grpcio (#5304)
- Add Test runs for Python 3.7 and remove 3.4 (#5295)
- Fix bad trove classifier
- Rename releases to changelog and include from CHANGELOG.md (#5191)

## 0.1.1

### Dependencies

- Update dependency range for api-core to include v1.0.0 releases (#4944)

### Documentation

- Fix package name in readme (#4670)
- BigQueryDataTransfer: update 404 link for API documentation (#4672)
- Replacing references to `stable/` docs with `latest/`. (#4638)

### Testing and internal changes

- Re-enable lint for tests, remove usage of pylint (#4921)
- Normalize all setup.py files (#4909)
- Update index.rst (#4816)
- nox unittest updates (#4646)

## 0.1.0

[![release level](https://img.shields.io/badge/release%20level-alpha-orange.svg?style&#x3D;flat)](https://cloud.google.com/terms/launch-stages)

The BigQuery Data Transfer Service automates data movement from SaaS
applications to Google BigQuery on a scheduled, managed basis. Your analytics
team can lay the foundation for a data warehouse without writing a single line
of code. BigQuery Data Transfer Service initially supports Google application
sources like Adwords, DoubleClick Campaign Manager, DoubleClick for Publishers
and YouTube.

PyPI: https://pypi.org/project/google-cloud-bigquery-datatransfer/0.1.0/
