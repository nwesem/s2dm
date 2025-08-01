# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2025-07-29

### Added

- Add first docs
- Add shacl command to the CLI
- Expand instance tags from the spec.
- SHACL exporter functioning
- Add ariadne for loading and validating multiple graphql files with a given path. Update documentation for model validation and exporters
- First draft of VSPEC generation.
- First draft vspec converted with Seat example
- Improve to_vspec exporter and add Seat example of VSS
- Enhance to_vspec processing for nested types
- Add unit mapping for various measurement types in to_vspec
- Add new GraphQL types and update VSS Seat example
- Add test case and example of COVESA AMM presentation
- Update .gitignore file.
- Add concept URI generator script
- Add spec history generation or update from existing history
- Add simple ci/cd workflows with github actions
- Add example/ directory with README and example files.
- Refactoring
- Parse @metadata(comment: String) as rdfs:comment.
- Added InCabinArea3x3
- Add basic CLI framework with click integration
- Add export commands for id, concept-uri, and spec-history
- Add constraint checker and graphql inspector tools
- Added modeling map with overlay
- Enhance version-bump command with semantic version detection
- Implement json schema exporter in python (#89)
- Doks Theme (#90)

### CI/CD

- Update CI configuration and coverage requirements
- Trigger ci on pushes to main
- Add release pipeline with automatic semantic versioning
- Apply zero-based versioning scheme
- Add DEPLOY_KEY to allow pushing to main from github actions
- Fix version replacement in release creation and manually update CHANGELOG

### Changed

- Made a first "iris" sub command
- Update GraphQL schema and dependencies
- Remove unnecessary lines in CONTRIBUTING.md and README.md
- Lines and formats, add figures.
- Refactor CLI options in s2dm/cli.py and add new subcommand
- Common types and GraphQL files of example 0
- SHACL exporter working without expansion. Supported field cases are: ['NON_NULL', 'SET_NON_NULL', 'DEFAULT', 'SET']
- Improve handling of list types in SHACL property shape creation
- Remove example 0 files that are covered in another repo. Improve the directory structure.
- Remove iris module and update CLI import. Enhance modeling guide with output type examples.
- Move examples folder and do some clean up.
- Enhance CLI commands for exporting schemas. Minor clean ups.
- Clean up
- Improve logging and code readability in to_vspec and utils
- Create history files based on schema
- Merge pull request that adds the first implementation of the identification functions
- Organize examples/
- Merge pull request #30 from COVESA/feat/refactoring-2
- Add mypy for tests dir
- Temporarily update min percentage of test coverage to 70%
- Merge pull request #2 from COVESA/feat/refactoring
- Update README.md
- Update main README (#35)
- Update SHACL exporter. (#44)
- Merge pull request #49 from COVESA/fix/shacl-exporter
- Merge pull request #53 from COVESA/feat/cabin-area-3-3
- Update concept models and services for CLI integration
- Merge pull request #56 from nwesem/ci/trig-main
- Docs/page update (#64)
- Merge pull request #66 from COVESA/excalidraw-map
- Merge pull request #67 from nwesem/feat/enhance-version-bump
- Click - pass obj instead of context with console
- Merge pull request #72 from COVESA/feat/click-pass-obj-instead-of-context
- Refactor page outline
- Merge pull request #73 from COVESA/refactor/web-page
- Merge pull request #42 from COVESA/develop
- Merge pull request #87 from COVESA/fix/shacl-comment
- Merge pull request #88 from COVESA/ci/fix-release-workflow
- Merge pull request #91 from ahmdmhd/fix/jsonschema-instance-expansion

### Documentation

- Update CONTRIBUTING.md and README.md for clarity and consistency
- Add Mozilla Public License Version 2.0 LICENSE
- Use GitHub pages with content from docs-gen folder
- Update README for spec history registry usage
- Add version bump CLI examples documentation

### Fixed

- Missing vssTypes
- Remove unused IRI generation command from CLI
- Mypy errors for utils.py, to_vspec.py, and to_shacl.py
- Resolve mypy type checking errors and improve type safety
- Fix imports related to idgen
- Mypy changes on tests
- Update docgen.yml
- Fixed some shacl exporter findings
- Removed duplicated log handlers and aligned log statements
- Expand instances in SHACL exporter.
- Wrong VssType in example, update Seat.graphql
- SHACL comment in properties. Test for GraphQL field cases
- Output correct object shape when processing instance tags
- Combine version bump and changelog update in single commit

### Miscellaneous

- Update uv.lock
- Add __init__.py to tests
- Update uv.lock
- Move all bumpversion config to .bumpversion.toml

### Testing

- Add comprehensive e2e and unit tests for CLI functionality
- Add GraphQL schema files for version bump testing
- Expand version-bump test coverage

[0.2.0] - 2025-07-29: https://github.com/COVESA/s2dm/compare/v0.1.0..HEAD

<!-- generated by git-cliff -->

## [0.1.0] - 2025-02-20

### Added

- Everything (init)
