# MA-HS-Experiments: Harmonized Specification for the Experiments Format

This repository contains the Modelica Association Harmonized Specification for the **Experiments Format** (`ma-hs-experiments`), an XML-based file format for describing experiment setups for simulation models.

The format supports specifying start/stop time, solver settings, parameter sets, stimuli, and reference results, and is intended to be referenced from layered standards such as [FMI-LS-REF](https://github.com/modelica/fmi-ls-ref).

## Contents

- `docs/index.adoc` — The specification document (AsciiDoc)
- `docs/examples/` — Example experiment files
- `schema/maHarmonizedSpecificationExperiments.xsd` — XML Schema for the Experiments Format
- `LICENSE.txt` — License information

## Building the Documentation

The documentation uses [Asciidoctor](https://asciidoctor.org/). After cloning with submodules:

```bash
git submodule update --init
asciidoctor docs/index.adoc
```

## License

This document is licensed under the Attribution-ShareAlike 4.0 International license.
The schema and example code are released under the 2-Clause BSD License.
See [LICENSE.txt](LICENSE.txt) for details.
