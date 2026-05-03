# TheCocktailDB (thecocktaildb)
An open, crowd-sourced database of cocktails and drinks from around the world with a free API.

**URL:** [Visit TheCocktailDB](https://www.thecocktaildb.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cocktails, Drinks, Recipes, Food And Beverage

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### TheCocktailDB API
An open, crowd-sourced database of cocktails and drinks from around the world with a free API. Search cocktails by name, ingredient, category, glass type, or alcoholic content. Look up full recipes with ingredients, measurements, instructions, and images. Free tier available with API key 1.

**Human URL:** [https://www.thecocktaildb.com/api.php](https://www.thecocktaildb.com/api.php)

#### Tags:

 - Cocktails, Drinks, Recipes, Food And Beverage

#### Properties

- [Documentation](https://www.thecocktaildb.com/api.php)
- [OpenAPI](openapi/thecocktaildb-openapi.yml)
- [Sign Up](https://www.thecocktaildb.com/signup.php)
- [JSONSchema - Drink Schema](json-schema/thecocktaildb-drink-schema.json)
- [JSONStructure - Drink Structure](json-structure/thecocktaildb-drink-structure.json)
- [JSON-LD - TheCocktailDB JSON-LD Context](json-ld/thecocktaildb-context.jsonld)

## Common Properties

- [Website](https://www.thecocktaildb.com/)
- [Documentation](https://www.thecocktaildb.com/api.php)
- [Sign Up](https://www.thecocktaildb.com/signup.php)
- [SpectralRules](rules/thecocktaildb-spectral-rules.yml)
- [Vocabulary](vocabulary/thecocktaildb-vocabulary.yml)
- [NaftikoCapability - Cocktail Discovery](capabilities/cocktail-discovery.yaml)

## Features

| Name | Description |
|------|-------------|
| Cocktail Search | Search cocktails by name or browse alphabetically by first letter |
| Ingredient Search | Search for ingredients and find cocktails containing them |
| Filter by Category | Filter cocktails by category (Cocktail, Shot, Punch, etc.) |
| Filter by Glass Type | Filter cocktails by glass type (Cocktail glass, Highball, etc.) |
| Alcoholic Filtering | Filter cocktails by alcoholic or non-alcoholic status |
| Random Cocktail | Retrieve a random cocktail recipe for inspiration |
| Full Recipe Details | Complete recipes with up to 15 ingredients, measurements, and step-by-step instructions |
| Multi-Language Instructions | Instructions available in English, Spanish, German, French, and Italian |
| Images | Drink and ingredient images available in multiple sizes |

## Use Cases

| Name | Description |
|------|-------------|
| Cocktail App Development | Build cocktail recipe apps and websites |
| Bartender Tools | Recipe lookup and ingredient substitution for professional bartenders |
| AI Recipe Assistant | Power AI agents that help users find cocktail recipes |
| Menu Planning | Plan bar menus by category, ingredient, or glass type |

## Integrations

| Name | Description |
|------|-------------|
| TheMealDB | Sister site providing food recipes from the same provider |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [TheCocktailDB API OpenAPI](openapi/thecocktaildb-openapi.yml)

### JSON Schema

- [thecocktaildb-drink-schema.json](json-schema/thecocktaildb-drink-schema.json)
- [thecocktaildb-cocktails-response-schema.json](json-schema/thecocktaildb-cocktails-response-schema.json)
- [thecocktaildb-filter-response-schema.json](json-schema/thecocktaildb-filter-response-schema.json)
- [thecocktaildb-list-response-schema.json](json-schema/thecocktaildb-list-response-schema.json)

### JSON Structure

- [thecocktaildb-drink-structure.json](json-structure/thecocktaildb-drink-structure.json)
- *(and 3 more)*

### JSON-LD

- [TheCocktailDB JSON-LD Context](json-ld/thecocktaildb-context.jsonld)

### Examples

4 example JSON payloads for all schema types.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [TheCocktailDB](capabilities/shared/thecocktaildb.yaml) — 5 operations for cocktail data access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cocktail Discovery](capabilities/cocktail-discovery.yaml) | TheCocktailDB | 13 | Bartender, Mixologist, AI Agent |

## Vocabulary

- [TheCocktailDB Vocabulary](vocabulary/thecocktaildb-vocabulary.yml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [TheCocktailDB Spectral Rules](rules/thecocktaildb-spectral-rules.yml) — 18 rules across 7 categories enforcing TheCocktailDB API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
