# json-schema-typed

JSONSchema TypeScript definitions.

[![tslint: Slick](https://img.shields.io/badge/tslint-slick-3a6b93.svg?style=flat-square)](https://github.com/typeslick/tslint-slick)
[![code style: Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![npm](https://img.shields.io/npm/v/json-schema-typed.svg?style=flat-square)](https://npmjs.org/package/json-schema-typed)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)
[![License](https://img.shields.io/badge/license-BSD--2--Clause-blue.svg?style=flat-square)](https://github.com/typeschema/json-schema-typed/blob/master/LICENSE)

## Install

```sh
$ npm install json-schema-typed
```

## Usage

TypeScript:

```typescript
import { JSONSchema } from 'json-schema-typed'

const schema: JSONSchema = {
  // ...
}
```

## API

Additional exports:

| Name                        | Type       | Purpose                                                    |
| --------------------------- | ---------- | ---------------------------------------------------------- |
| `JSONSchemaFormat`          | Enum       | JSON Schema string formats.                                |
| `JSONSchemaType`            | Enum       | Standard values for the "type" field.                      |
| `JSONSchemaContentEncoding` | Enum       | JSON Schema content encoding strategies.                   |
| `JSONSchemaKeys`            | `string[]` | All the standard property keys available in a JSON schema. |

## Versioning

```
+----- Major version is synchronized with the major version of JSON Schema.
| +--- Minor version has BREAKING CHANGE and/or new features.
| | +- Patch version.
| | |
x.x.x
```

---

## Related

- [typeschema](https://github.com/typeschema/typeschema)

## News and Updates

[Follow @typeslick on Twitter](https://twitter.com/typeslick) for the latest
updates and new project announcements.

## Sponsors

- [Loomble](https://loomble.com/)

## Maintainers

- [Jay Rylan](https://jayrylan.com/)

## License

[BSD-2-Clause](https://github.com/typeschema/json-schema-typed/blob/master/LICENSE)
