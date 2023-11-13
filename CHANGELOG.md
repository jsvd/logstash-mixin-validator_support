## 1.1.1
  - Fixes `:required_host_optional_port` validator to accept _all_ RFC1123-compliant hostnames, including single-label names like `localhost` [#7](https://github.com/logstash-plugins/logstash-mixin-validator_support/pull/7)

## 1.1.0
  - Introduces `:required_host_optional_port` validator [#4](https://github.com/logstash-plugins/logstash-mixin-validator_support/pull/4)

## 1.0.2
  - Fix: '' value behavior in `field_reference` validator [#2](https://github.com/logstash-plugins/logstash-mixin-validator_support/pull/2)

## 1.0.1
  - Introduces plugin parameter validation adapters, including initial backport for `:field_reference` validator.