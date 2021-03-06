# Collection

This folder contains external data sets imported in JSON Schema format:

| Name       | Description  |
|------------|--------------|
| `language` | Programming languages and associated extensions, sources: [Linguist](https://github.com/github/linguist) |
| `license`  | Software licenses names and acronyms, sources: [SPDX](https://spdx.org/licenses/) |
| `manager`  | System and language package managers, sources: [Wikipedia](https://en.wikipedia.org/wiki/List_of_software_package_management_systems) |

The posfix in the file name (e.g. [license.*spdx*.json](license.spdx.json)) indicates the original source of the data set (in this example SPDX catalog) while files without postfix (e.g. [license.json](license.json)) defines a final collection as a composition of several sets.

Those sets are used as allowed values in [core schemas](../schema) and it's structure is described in [docs](../../docs/).
