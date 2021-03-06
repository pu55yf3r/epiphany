# Changelog 0.9

## [0.9.0] YYYY-MM-DD

### Added

- [#921](https://github.com/epiphany-platform/epiphany/issues/921) - Implement log rotation for PgBouncer

### Fixed

- [#1273](https://github.com/epiphany-platform/epiphany/issues/1273) - PostgreSQL replication with repmgr: hot_standby not set in config file
- [#1792](https://github.com/epiphany-platform/epiphany/issues/1792) - Not possible to debug failures in applications role
- [#1835](https://github.com/epiphany-platform/epiphany/issues/1835) - Automated tests may give false negative result for PGAudit
- [#1409](https://github.com/epiphany-platform/epiphany/issues/1409) - custom_image_registry_address setting is not implemented
- [#1280](https://github.com/epiphany-platform/epiphany/issues/1280) - [RHEL] Pgpool not showing Replication State
- [#1833](https://github.com/epiphany-platform/epiphany/issues/1833) - DaemonSets of Node Exporter and Filebeat deploy in default namespace
- [#1872](https://github.com/epiphany-platform/epiphany/issues/1872) - pythonPath in launch.json is not supported
- [#1868](https://github.com/epiphany-platform/epiphany/issues/1868) - Repository host runs Ubuntu on Azure/RHEL cluster
- [#1875](https://github.com/epiphany-platform/epiphany/issues/1875) - epicli upgrade fails when there is no kubernetes_master group in inventory
- [#1834](https://github.com/epiphany-platform/epiphany/issues/1834) - Kafka - Disable debug logging and make this option configurable
- [#1888](https://github.com/epiphany-platform/epiphany/issues/1888) - epicli upgrade of cluster created by Epiphany v0.5 may fail
- [#1884](https://github.com/epiphany-platform/epiphany/issues/1884) - Prometheus is not able to scrape metrics from AKS/EKS nodes
- [#1887](https://github.com/epiphany-platform/epiphany/issues/1887) - epicli upgrade of cluster created by Epiphany v0.6 fails on "Store preflight facts" task

### Updated

- [#1770](https://github.com/epiphany-platform/epiphany/issues/1770) - Upgrade Filebeat to the latest version (7.9.2)
- [#1848](https://github.com/epiphany-platform/epiphany/issues/1848) - Update Ansible to v2.8.17
- [#1854](https://github.com/epiphany-platform/epiphany/issues/1854) - Upgrade RabbitMQ to the latest version (3.8.9)
- [#1137](https://github.com/epiphany-platform/epiphany/issues/1137) - Upgrade Kafka to 2.6.0
- [#1855](https://github.com/epiphany-platform/epiphany/issues/1855) - Upgrade Docker to v19.03.14
- [#1853](https://github.com/epiphany-platform/epiphany/issues/1853) - Upgrade Zookeeper to 3.5.8

### Breaking changes

### Known issues
