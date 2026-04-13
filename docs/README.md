# FAQ

## Is source code available?

Yes. Source code is available through the following channels:

- **Source ISO:** [https://dlnavix.navercorp.com/9/x86_64/BaseOS/source/iso/](https://dlnavix.navercorp.com/9/x86_64/BaseOS/source/iso/)
- **Per-repository source tree:**
  ```
  https://dlnavix.navercorp.com/9/x86_64/{repository}/source/tree/
  ```
  Example: `https://dlnavix.navercorp.com/9/x86_64/BaseOS/source/tree/`

## What repositories are available?

| Repository | Description |
|---|---|
| **AppStream** | Application packages and additional software |
| **BaseOS** | Core OS packages and ISOs |
| **CRB** | Code Ready Builder — additional development libraries |
| **HighAvailability** | Clustering and high-availability packages |
| **ResilientStorage** | Resilient storage packages |
| **Updates** | Security and bug-fix updates |

Each repository contains the following subdirectories:

| Subdirectory | Contents |
|---|---|
| `os/` | Binary RPM packages |
| `source/` | Source RPM packages |
| `debug/` | Debug symbol packages |
| `iso/` | ISO images (BaseOS only) |

## Where can I report a bug or request a feature?

Please use the issue templates in the main repository:

- [Report a bug](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=bug%2Cnew&projects=&template=bugreport.yml&title=%5BBUG%5D)
- [Request a feature](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml&title=%5BENHANCEMENT%5D)
- [Ask a question](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=question&projects=&template=question.yml&title=%5BQ%5D)
