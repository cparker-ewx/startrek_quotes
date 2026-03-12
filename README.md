# Star Trek Quotes API

An OpenAPI 3.1 specification for an API that serves Star Trek quotes, with listing, random quote, and character endpoints.

## Overview

This repository contains the API contract (OpenAPI 3.1) for a read-only REST API that returns Star Trek quotes. The spec defines endpoints to list quotes with optional filters, fetch a quote by ID, get a random quote, and list available character names.

## Tech Stack

- **OpenAPI 3.1** — API specification (YAML)
- **pnpm** — Package manager

## Getting Started

### Prerequisites

- Node.js (recommended LTS)
- pnpm ([install pnpm](https://pnpm.io/installation))

### Installation

```bash
pnpm install
```

### Development

```bash
pnpm run dev
```

### Build

```bash
pnpm run build
```

## Project Structure

- **openapi.yaml** — OpenAPI 3.1 specification for the Star Trek Quotes API (paths, schemas, examples).

## License

*(Add your license here.)*
