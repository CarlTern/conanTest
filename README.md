# Scanning Conan (C/C++) with Debricked

### Note:

As of June 2025, C and C++ are not officially supported by Debricked. It is currently in active development, however, and this workaround may become outdated after the official release.

Please check out https://docs.debricked.com/overview/language-support for the most up-to-date information.

### The workaround 

As Conan has an official extension for generating SBOMs, which Debricked can scan, it can be utilised to prepare Conan projects for Debricked scanning. Please check out the [GitHub Actions workflow](.github/workflows/debricked.yml) in this repo for more details. 
