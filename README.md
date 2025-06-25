# Character Queries - ALX GraphQL Project

This directory contains GraphQL queries and their corresponding outputs to interact with the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql). The queries focus on retrieving individual characters and paginated lists of characters.

---

## 📌 Queries Included

### 1. 🔍 Get a Character by ID

Fetch details of a specific character by their ID.

**Queried Fields:** `id`, `name`, `status`, `type`, `gender`

| File | Description |
|------|-------------|
| `character-id-1.graphql` | Query for character with ID 1 |
| `character-id-1-output.json` | API response for ID 1 |
| `character-id-2.graphql` | Query for character with ID 2 |
| `character-id-2-output.json` | API response for ID 2 |
| `character-id-3.graphql` | Query for character with ID 3 |
| `character-id-3-output.json` | API response for ID 3 |
| `character-id-4.graphql` | Query for character with ID 4 |
| `character-id-4-output.json` | API response for ID 4 |

---

### 2. 📄 Get a Paginated List of Characters

Fetch a list of characters for pages 1 to 4 using the `characters(page: Int)` query.

**Queried Fields:** `id`, `name`, `status`, `image`

| File | Description |
|------|-------------|
| `characters-page-1.graphql` | Query for page 1 characters |
| `characters-page-1-output.json` | API response for page 1 |
| `characters-page-2.graphql` | Query for page 2 characters |
| `characters-page-2-output.json` | API response for page 2 |
| `characters-page-3.graphql` | Query for page 3 characters |
| `characters-page-3-output.json` | API response for page 3 |
| `characters-page-4.graphql` | Query for page 4 characters |
| `characters-page-4-output.json` | API response for page 4 |

---

## 🌐 API Endpoint

All queries are executed against the following GraphQL endpoint:

