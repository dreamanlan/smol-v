# SMOL-V Change Log

For an overview, see [readme](README.md).

## 2016 09 01

* Improve compression for programs already processed by
  spirv-remap. "Relative to result ID" entries now encode
  negative numbers in a more compact way.
* More compact encoding of MemberDecorate op sequences.
* Tests: added suite of shaders from DOTA2 and Talos Principle.


## 2016 08 31

* Optional flag to strip debug information from SPIR-V: `kEncodeFlagStripDebugInfo`. *(Florian Penzkofer)*


## 2016 08 27

* Initial version.