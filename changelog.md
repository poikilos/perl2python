# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).


## [Unreleased] - 2020-05-23
(Poikilos)
### Added
- quality script
- Changelog

### Changed
- Fix some spelling and grammar.
- Conform to PEP8.
  - Change regex strings to start with r (before opening quote of
    the Python literal) to avoid bad escape sequences. Replace real
    escape sequences manually as necessary.
- Change the end of the shebang from `python2.7 -u` to `env python`.
