# Character Queries – ALX GraphQL Project

This directory contains GraphQL queries and corresponding outputs used to interact with the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) to fetch character-related information.

---

## 🔍 1. Get a Specific Character by ID

Fetches individual character data using the `character(id: ID!)` query.

### Fields retrieved:
- `id`
- `name`
- `status`
- `type`
- `gender`

### Files:
| File | Description |
|------|-------------|
| `character-id-1.graphql` | Query for character ID 1 |
| `character-id-1-output.json` | Response for character ID 1 |
| `character-id-2.graphql` | Query for character ID 2 |
| `character-id-2-output.json` | Response for character ID 2 |
| `character-id-3.graphql` | Query for character ID 3 |
| `character-id-3-output.json` | Response for character ID 3 |
| `character-id-4.graphql` | Query for character ID 4 |
| `character-id-4-output.json` | Response for character ID 4 |

---

## 📄 2. Get a Paginated List of Characters

Retrieves a list of characters using the `characters(page: Int)` query.

### Fields retrieved:
- `id`
- `name`
- `status`
- `image`

### Files:
| File | Description |
|------|-------------|
| `characters-page-1.graphql` | Query for page 1 characters |
| `characters-page-1-output.json` | Response for page 1 |
| `characters-page-2.graphql` | Query for page 2 characters |
| `characters-page-2-output.json` | Response for page 2 |
| `characters-page-3.graphql` | Query for page 3 characters |
| `characters-page-3-output.json` | Response for page 3 |
| `characters-page-4.graphql` | Query for page 4 characters |
| `characters-page-4-output.json` | Response for page 4 |

---

## 🌐 API Endpoint

All queries are executed against:

