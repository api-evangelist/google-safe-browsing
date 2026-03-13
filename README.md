# Google Safe Browsing API

The Google Safe Browsing API enables client applications to check web resources (most commonly URLs) against Google-generated lists of unsafe web resources including malware, social engineering, unwanted software, and potentially harmful applications.

## APIs

- **Google Safe Browsing API** - Check URLs against threat lists and manage local threat databases.

## Base URL

```
https://safebrowsing.googleapis.com/v4
```

## Key Endpoints

- **Find Threat Matches** - `POST /threatMatches:find` - Check URLs against threat lists
- **List Threat Lists** - `GET /threatLists` - List available threat lists
- **Fetch Threat List Updates** - `POST /threatListUpdates:fetch` - Get latest threat list updates
- **Find Full Hashes** - `POST /fullHashes:find` - Find full hashes matching prefixes

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/ThreatMatch.json) - JSON Schema (draft 2020-12) for ThreatMatch
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/safe-browsing/v4/get-started)
- [API Reference](https://developers.google.com/safe-browsing/v4/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
