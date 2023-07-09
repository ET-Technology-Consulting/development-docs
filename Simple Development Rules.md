# Simple Development Rules

## Code structure

- We structure project with Domain-Drive Design (DDD)
- Example : https://markus.oberlehner.net/blog/vue-project-directory-structure-keep-it-flat-or-group-by-domain/

## App design

- Create a document with all reference designs :
  - Colors for themes (light, dark) and action (hover, click, etc..)
  - Font size foreach elements (p, h1, table, etc..)
  - Other rules like border radius, box shadow, etc..
- Create components on storybook to validate it

## Gitting

- 2 main branches :
  - `main` for production environment
  - `dev` for staging environment
- Create a new branch from `dev` with a conventionnal name :
  - `feat/NAME-OF-NEW-FEAT` : new feature
  - `fix/FIX-NAME` : code fix
- Once changes are made, ask for a merge request
- Until it is not validated, add changes on the same branch
- Once it is validated, merge squash changes in `dev` branch and drop branch
- Validate updates on staging
- Merge `dev` into `main` and create a semantic version

## Commit & semantic version

- Write conventionnal commits (https://www.conventionalcommits.org/en/v1.0.0/)
- Write semantic version (https://semver.org/lang/en/)

## Project Management

- We write any idea
- We choose to validate some of this idea to convert them into issues (task)
- We choose to integrate some of them for the new sprint and link it to the right project and milestone 