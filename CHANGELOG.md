# GCPy Changelog

All notable changes to GCPy will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added

### Changed

### Deprecated

### Fixed

### Removed

## [0.1.1] - 2020-02-28

### Added

- This CHANGELOG file to track notable changes in GCPy.

### Changed
- Pb210, Be7, and Be10 species are now added to species_database.yml.
- gcpy/budget_aer.py and gcpy/budget_tt.py now get molecular weights from species_database.yml.
- Updated the value of MW_AIR in constants.py to add more precision.
- gcpy/benchmark.py now writes OH metrics output to the Plots/Tables folder.
- Updated CHANGELOG.md for 0.1.1.

## [0.1.0] - 2020-02-26

### Summary

This is the first labeled version of GCPy. The primary functionality of GCPy is plotting and tabling diagnostics from GEOS-Chem. Main features include:

- Functions for comparing GEOS-Chem benchmark output for multiple versions of GEOS-Chem, including 2D plots and mass and budget table creation.
- Support for plotting benchmark output for both GEOS-Chem Classic (lat/lon data) and GCHP (cubed-sphere data).

The first official release version of GCPy, v1.0.0, will correspond with the release of GEOS-Chem 13.0.0.
