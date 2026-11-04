# MA-HS-Experiments: Harmonized Specification for the Experiments Format

[![Build Specification][build-badge]][build-workflow]
[![Specification][spec-badge]][spec]

This repository contains the current draft of the Modelica Association
Harmonized Specification for the **Experiments Format**
(`ma-hs-experiments`), an XML-based file format for describing
experiment setups for simulation models.

The format supports specifying start/stop time, solver settings,
parameter sets, stimuli, and reference results, and is intended to be
referenced from layered standards such as
[FMI-LS-REF][fmi-ls-ref].

Note that this draft is being worked on actively, and thus is subject to
change without notice.
It is now developed by the MAP-COORD project and shall be written in a
way that makes it applicable to models following the Modelica, FMI, and
SSP standards.
Note that due to this recent change, some documentation may be outdated.

This is currently not normative, nor is this document to be considered
officially endorsed by the Modelica Association or other involved
organisations prior to official adoption.

The MA Harmonized Specification Experiments is currently maintained on
[GitHub][githubspec] and is published as an
[HTML document on GitHub Pages][spec].

## Contents

- [`docs/index.adoc`][githubspec] — The specification document (AsciiDoc)
- [`docs/examples/`][examples] — Example experiment files
- [`schema/maHarmonizedSpecificationExperiments.xsd`][schema] — XML Schema for the Experiments Format

## Building the Documentation

The documentation uses [Asciidoctor][asciidoctor].
After cloning with submodules:

```bash
git submodule update --init
asciidoctor docs/index.adoc
```

## License

This document is licensed under the Attribution-ShareAlike 4.0
International license.
The schema and example code are released under the 2-Clause BSD License.
See [LICENSE.txt][license] for details.

[asciidoctor]: https://asciidoctor.org/
[build-badge]: https://github.com/modelica/ma-hs-experiments/actions/workflows/build-hs-experiments.yml/badge.svg
[build-workflow]: https://github.com/modelica/ma-hs-experiments/actions/workflows/build-hs-experiments.yml
[examples]: docs/examples/
[fmi-ls-ref]: https://github.com/modelica/fmi-ls-ref
[githubspec]: docs/index.adoc
[license]: LICENSE.txt
[schema]: schema/maHarmonizedSpecificationExperiments.xsd
[spec]: https://modelica.github.io/ma-hs-experiments/main/
[spec-badge]: https://img.shields.io/badge/spec-main-blue
