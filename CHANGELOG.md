# Changelog

All notable changes to this project will be documented in this file.

## [1.2.1](https://github.com/terraform-aws-modules/terraform-aws-opensearch/compare/v1.2.0...v1.2.1) (2024-06-28)


### Bug Fixes

* Create a domain policy that implicitly depends_on domain ([#15](https://github.com/terraform-aws-modules/terraform-aws-opensearch/issues/15)) ([473ba5d](https://github.com/terraform-aws-modules/terraform-aws-opensearch/commit/473ba5df25e8b1b480c7dc661361b39c2ac8ce6d))

## [1.2.0](https://github.com/terraform-aws-modules/terraform-aws-opensearch/compare/v1.1.2...v1.2.0) (2024-06-19)


### Features

* Opensearch Domain `ip_address_type`, Cloudwatch `log_group_class`, and `skip_destroy` ([#13](https://github.com/terraform-aws-modules/terraform-aws-opensearch/issues/13)) ([b7ab787](https://github.com/terraform-aws-modules/terraform-aws-opensearch/commit/b7ab7872ba8e4508b7e9879fe0608745ce369af0))

## [1.1.2](https://github.com/terraform-aws-modules/terraform-aws-opensearch/compare/v1.1.1...v1.1.2) (2024-04-09)


### Bug Fixes

* Do not create default zone_awareness_config if it not set ([#3](https://github.com/terraform-aws-modules/terraform-aws-opensearch/issues/3)) ([3a1f79f](https://github.com/terraform-aws-modules/terraform-aws-opensearch/commit/3a1f79f1fa06a660091af7fa1843303f47f54c0f))

## [1.1.1](https://github.com/terraform-aws-modules/terraform-aws-opensearch/compare/v1.1.0...v1.1.1) (2024-04-09)


### Bug Fixes

* Fix the condition of the logical operators of `master_user_name` and `master_user_password` ([#4](https://github.com/terraform-aws-modules/terraform-aws-opensearch/issues/4)) ([fa811d2](https://github.com/terraform-aws-modules/terraform-aws-opensearch/commit/fa811d29e80f1658b8af148c8d0697b29fbc6593))

## [1.1.0](https://github.com/terraform-aws-modules/terraform-aws-opensearch/compare/v1.0.0...v1.1.0) (2024-03-22)


### Features

* Add `standby_replicas` to serverless collection and `auto_tune_options.use_off_peak_window` to domain ([#2](https://github.com/terraform-aws-modules/terraform-aws-opensearch/issues/2)) ([dff3f63](https://github.com/terraform-aws-modules/terraform-aws-opensearch/commit/dff3f6357cbe92f582527267499f82cf90d6027e))
