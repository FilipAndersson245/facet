# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.24.3](https://github.com/facet-rs/facet/compare/facet-serialize-v0.24.2...facet-serialize-v0.24.3) - 2025-05-18

### Other

- Introduce `'shape` lifetime, allowing non-'static shapes.

## [0.24.2](https://github.com/facet-rs/facet/compare/facet-serialize-v0.24.1...facet-serialize-v0.24.2) - 2025-05-16

### Other

- Rust 1.87 clippy fixes
- almost fix everything
- Fix json tests
- Support OffsetDateTime in YAML

## [0.24.1](https://github.com/facet-rs/facet/compare/facet-serialize-v0.24.0...facet-serialize-v0.24.1) - 2025-05-13

### Other

- updated the following local packages: facet-core, facet-reflect

## [0.23.6](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.5...facet-serialize-v0.23.6) - 2025-05-12

### Other

- updated the following local packages: facet-core, facet-reflect

## [0.23.5](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.4...facet-serialize-v0.23.5) - 2025-05-12

### Other

- Update `facet-serialize` to handle a few more affinities
- Add support for time crate's OffsetDateTime and UtcDateTime

## [0.23.4](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.3...facet-serialize-v0.23.4) - 2025-05-10

### Other

- updated the following local packages: facet-core, facet-reflect

## [0.23.3](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.2...facet-serialize-v0.23.3) - 2025-05-10

### Other

- updated the following local packages: facet-core, facet-reflect

## [0.23.2](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.1...facet-serialize-v0.23.2) - 2025-05-10

### Other

- updated the following local packages: facet-core, facet-reflect

## [0.23.1](https://github.com/facet-rs/facet/compare/facet-serialize-v0.23.0...facet-serialize-v0.23.1) - 2025-05-10

### Other

- Release facet-reflect
- Release facet-derive-parser
- Upgrade facet-core
- Determine enum variant after default_from_fn
- Uncomment deserialize
- Fix up enums a bit
- Make variant() getters fallible — we might not know the internal enough to read the discriminant etc.
- Make options work for facet-serialize
- debug facet-serialize
- Fix memory leak, work on facet-serisalize

## [0.23.0](https://github.com/facet-rs/facet/compare/facet-serialize-v0.22.0...facet-serialize-v0.23.0) - 2025-05-08

### Other

- Use `PeekListLike`

## [0.22.0](https://github.com/facet-rs/facet/compare/facet-serialize-v0.21.0...facet-serialize-v0.22.0) - 2025-05-06

### Added

- *(serialize)* add more optional start- and end-serialize calls

### Fixed

- *(reflect)* add missing scalar types

### Other

- *(serialize)* make end_* trait methods optional
- *(serialize)* optionally widen-cast number types to u64 in trait

## [0.21.0](https://github.com/facet-rs/facet/compare/facet-serialize-v0.20.0...facet-serialize-v0.21.0) - 2025-05-02

### Other

- JSON facet-serialize?
- Use facet-serialize in facet-msgpack
- Don't depend on git version of insta anymore
- Introduce facet-serialize
