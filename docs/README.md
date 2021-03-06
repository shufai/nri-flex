# Flex documentation

## Basics

- [File and directory structure](basics/file_layout.md)
- [Structure of a Flex configuration file](basics/flex_config_sections.md)

## APIs

The Flex APIs provide means to acquire data from multiple sources for [processing](apis/functions.md):

- [commands API](apis/commands.md)
- [url API](apis/url.md)

For more information on all the functions and their order of precedence, see [Functions for data manipulation](apis/functions.md).

## Experimental features

Flex implements the following experimental features. 'Experimental' here means that New Relic does not yet provides support for them.

- [Database queries](experimental/db.md)
- [Net dial](experimental/dial.md)
- [Git configuration synchronization](experimental/git_sync.md)
- [JMX](experimental/jmx.md)

## Deprecated features

The following functionalities are still provided by Flex for backwards compatibility, but
its use is discouraged and unsupported because New Relic provides more convenient implementations
of such functionalities.

For each deprecated functionality, please consider migrating to the New Relic supported equivalent,
as linked in the right column of the following table. 

| Deprecated feature | New Relic supported equivalent |
|---|---|
| [Discovery](deprecated/discovery.md) | [Container auto-discovery for On-Host Integrations](https://docs.newrelic.com/docs/integrations/host-integrations/installation/container-auto-discovery) |
| [JMX](deprecated/jmx.md) | [New Relic JMX On-Host Integration](http://github.com/newrelic/nri-jmx) |
| [Prometheus](deprecated/prometheus.md) | [New Relic Prometheus OpenMetrics integration for Docker and Kubernetes](https://docs.newrelic.com/docs/integrations/prometheus-integrations) |
| [Secrets management](deprecated/secrets.md) | [Secrets management for On-Host Integrations](https://docs.newrelic.com/docs/integrations/host-integrations/installation/secrets-management) |


