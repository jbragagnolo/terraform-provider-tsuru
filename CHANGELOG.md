# Changelog

## [2.21.0](https://github.com/jbragagnolo/terraform-provider-tsuru/compare/v2.20.1...v2.21.0) (2026-11-11)


### Features

* Add import support for tsuru_certificate_issuer resource ([#67](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/67)) ([2e5b5e9](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/2e5b5e9e9d90c3b470b70da6f3a09eb84caaefea))
* add service instance support ([3439a1e](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/3439a1e83cbfe8be020bd9ccbd32a96693070a55))
* add tsuru_platform resource ([#90](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/90)) ([3a372e2](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/3a372e2c192d728455e65bbebf06589f6632ad2e))
* add tsuru_role_default resource ([#91](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/91)) ([918b5bb](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/918b5bb9b3fb02da6311f735e6f53152651218a3))
* add tsuru_service resource for managing service definitions ([#81](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/81)) ([9665bc8](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/9665bc8c39523e2413797610368c4186bf33ef5e))
* job deploy image ([#59](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/59)) ([f90fb2c](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/f90fb2c154b21553b7e9768539811f63650dcd7b))
* **job:** support manual jobs when schedule is empty ([#75](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/75)) ([1dd0ad4](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/1dd0ad4bcbb4eccb52b0914bfc8d55a5edc32b6a))
* Prometheus Autoscale ([#57](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/57)) ([4b64c23](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/4b64c238df3dd561dc07dbcdab2cfb09c07d1abd))
* service manifest management ([#84](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/84)) ([5b2824e](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/5b2824ebea11f9de0d17b7b0ce3a20f9cce75472))
* tsuru role and permission to role management via tf ([#86](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/86)) ([57518cd](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/57518cdcb31fe146a161c50ae645984de0b83541))
* tsuru_app, cname, env, grant, router, unit, closes [#9](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/9) ([2938b63](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/2938b63f2be62c414e152e9fb5e8856fdee564ed))
* Validate app processes are alphabetically sorted ([#64](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/64)) ([745efb1](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/745efb104c62f1fd10466740e87657ed07cd9682))


### Bug Fixes

* id must always contain version if exists ([c810515](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/c810515ab56056afdfa9094dfcbfbfbfd3bcc579))
* parse tags should not include empty strings nor break if one of the passed values is 'nil' ([#80](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/80)) ([2331c02](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/2331c0272a138fc009136a72af0b6b4f5a7ae22f))
* resolve tsuru_router by ID on read, not name/type ([#92](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/92)) ([db1b4bc](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/db1b4bcebe24a01e66bf17f549ce0312a5d574c3))
* retry tsuru_cluster and tsuru_cluster_pool on event lock ([#94](https://github.com/jbragagnolo/terraform-provider-tsuru/issues/94)) ([a976533](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/a976533b27a58d49034c5fc96a674bb4ae4e19f0))
* volumeRead: only when both app && mountPoint ([e86f858](https://github.com/jbragagnolo/terraform-provider-tsuru/commit/e86f8582ef1060658c35af809766ce42f70be304))

## [2.20.1](https://github.com/tsuru/terraform-provider-tsuru/compare/v2.20.0...v2.20.1) (2026-10-29)


### Bug Fixes

* retry tsuru_cluster and tsuru_cluster_pool on event lock ([#94](https://github.com/tsuru/terraform-provider-tsuru/issues/94)) ([a976533](https://github.com/tsuru/terraform-provider-tsuru/commit/a976533b27a58d49034c5fc96a674bb4ae4e19f0))
