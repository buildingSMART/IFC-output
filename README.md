# IFC4.x output

This repository contains generated and published artifacts for the **IFC 4.x** family of Industry Foundation Classes (IFC) specifications.

The contents are derived from buildingSMART specification sources and are intended to provide machine-readable outputs such as HTML pages, EXPRESS schemas, XML schemas, property set definitions, and related generated artifacts.

Official IFC publications are available from the [buildingSMART IFC Specifications Database](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/).

> [!IMPORTANT]
> Content in this repository may include development, withdrawn, retired, and official releases. For normative use, always refer to the corresponding official buildingSMART publication.

## Generated repository

This repository is the **automatically generated output of [`IFC4.x-development`](https://github.com/buildingSMART/IFC4.x-development)**.

Its contents are produced by automated publication and generation processes. Files in this repository **should not be edited manually**, as any manual changes may be overwritten by subsequent automated updates.

This repository is also **not the appropriate place to report issues, request changes, or propose corrections to the IFC specification**.

For specification issues and proposed changes, use the corresponding [`IFC4.x-development`](https://github.com/buildingSMART/IFC4.x-development) repository and its issue tracking process.


## Version notation

IFC versions use the following notation:

```text
Major.Minor.Addendum.Corrigendum
```

* **Major** - scope expansions or deletions that may introduce breaking changes.
* **Minor** - feature extensions. Compatibility is maintained for the core schema, but not necessarily for other definitions.
* **Addendum** - improvements to existing features. The schema may change while maintaining upward compatibility.
* **Corrigendum** - documentation improvements. The schema does not change, although deprecations may be introduced.

For example:

```text
4.3.2.0
│ │ │ └─ Corrigendum
│ │ └─── Addendum
│ └───── Minor
└─────── Major
```

## Official publications

Normative and historical IFC releases, including downloadable packages and individual schema representations, are published at:

* [IFC Specifications Database](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/)
* [IFC Release Notes](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/ifc-release-notes/)
* [Official IFC Standards](https://standards.buildingsmart.org/IFC/)

## License

IFC is licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)**.

Copyright © buildingSMART International Ltd.
