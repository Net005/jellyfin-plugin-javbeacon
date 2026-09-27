# Changelog

All notable changes to the JAVBeacon Jellyfin plugin are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.0.139.0] - 2026-09-27

### Changed

- Split this plugin out of the JAVBeacon monorepo (previously
  `integrations/jellyfin/` there) into its own repository. JAVBeacon no
  longer builds or bundles this plugin as part of its own release process;
  this repo now owns its own versioning, build, and release. No functional
  change to the plugin itself - JAVBeacon's HTTP API contract this plugin
  talks to is unchanged.
