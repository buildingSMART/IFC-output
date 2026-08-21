# Standards builds

This repository contains mainly auto-generated and published artefacts for the openBIM standards, including Industry Foundation Classes (IFC) specifications and Information Delivery Specification (IDS).

The contents are derived from buildingSMART specification sources and are intended to provide machine-readable outputs such as HTML pages, EXPRESS schemas, XML/XSD schemas, property set definitions, and related generated artefacts.

> [!IMPORTANT]
> Content in this repository may include development, withdrawn, retired, and official releases. For normative use, always refer to the corresponding official buildingSMART publication.
> Files in this repository **should not be edited manually**, as any manual changes may be overwritten by subsequent automated updates.
> This repository is also **not the appropriate place to report issues, request changes, or propose corrections to the IFC specification**.

# IFC

This repository contains both the **automatically generated output of [`IFC4.x-development`](https://github.com/buildingSMART/IFC4.x-development) (DEV)**, and official release snapshots (RELEASE).

Official IFC publications are available from the [buildingSMART IFC Specifications Database](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/).

For specification issues and proposed changes, use the corresponding [`IFC4.x-development`](https://github.com/buildingSMART/IFC4.x-development) repository and its issue tracking process.

Normative and historical IFC releases, including downloadable packages and individual schema representations, are published at:

* [IFC Specifications Database](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/)
* [IFC Release Notes](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/ifc-release-notes/)
* [Official IFC Standards](https://standards.buildingsmart.org/IFC/)

## Version notation

```text
4.3.2.0 (example)
│ │ │ └─ Corrigendum
│ │ └─── Addendum
│ └───── Minor
└─────── Major
```

* **Major** - scope expansions or deletions that may introduce breaking changes.
* **Minor** - feature extensions. Compatibility is maintained for the core schema, but not necessarily for other definitions.
* **Addendum** - improvements to existing features. The schema may change while maintaining upward compatibility.
* **Corrigendum** - documentation improvements. The schema does not change, although deprecations may be introduced.

## License

Copyright © buildingSMART International Ltd. All Rights reserved until formal release. Final IFC is licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)**.

