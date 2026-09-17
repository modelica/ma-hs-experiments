# MA-HS-Experiments: Harmonized Specification for the Experiments Format

[![Build Specification](https://github.com/modelica/ma-hs-experiments/actions/workflows/build-hs-experiments.yml/badge.svg)](https://github.com/modelica/ma-hs-experiments/actions/workflows/build-hs-experiments.yml)

This repository contains the current draft of the Modelica Association
Harmonized Specification for the **Experiments Format**
(`ma-hs-experiments`), an XML-based file format for describing
experiment setups for simulation models.

The format supports specifying start/stop time, solver settings,
parameter sets, stimuli, and reference results, and is intended to be
referenced from layered standards such as
[FMI-LS-REF](https://github.com/modelica/fmi-ls-ref).

Note that this draft is being worked on actively, and thus is subject to
change without notice.
It is now developed by the MAP-COORD project and shall be written in a
way that makes it applicable to models following the Modelica, FMI, and
SSP standards.
Note that due to this recent change, some documentation may be outdated.

This is currently not normative, nor is this document to be considered
officially endorsed by the Modelica Association or other involved
organisations prior to official adoption.

The [MA Harmonized Specification Experiments][spec] is currently
maintained on [GitHub][githubspec] and is published [here][spec].

[githubspec]: docs/index.adoc
[spec]: https://modelica.github.io/ma-hs-experiments/main/

## Contents

- `docs/index.adoc` — The specification document (AsciiDoc)
- `docs/examples/` — Example experiment files
- `schema/maHarmonizedSpecificationExperiments.xsd` — XML Schema for the Experiments Format
- `LICENSE.txt` — License information

## Building the Documentation

The documentation uses [Asciidoctor](https://asciidoctor.org/).
After cloning with submodules:

```bash
git submodule update --init
asciidoctor docs/index.adoc
```

## License

This document is licensed under the Attribution-ShareAlike 4.0
International license.
The schema and example code are released under the 2-Clause BSD License.
See [LICENSE.txt](LICENSE.txt) for details.
