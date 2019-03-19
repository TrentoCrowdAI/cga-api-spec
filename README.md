# CGA-api OpenAPI Specification
[![Build Status](https://travis-ci.org/TrentoCrowdAI/cga-api-spec.svg?branch=master)](https://travis-ci.org/TrentoCrowdAI/cga-api-spec)
## Links

- Reference Documentation (ReDoc): https://trentocrowdai.github.io/cga-api-spec/preview/dev/
- SwaggerUI: https://trentocrowdai.github.io/cga-api-spec/preview/dev/swagger-ui/
- Look full spec:
    - JSON: https://trentocrowdai.github.io/cga-api-spec/preview/dev/openapi.json
    - YAML: https://trentocrowdai.github.io/cga-api-spec/preview/dev/openapi.yaml


## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
