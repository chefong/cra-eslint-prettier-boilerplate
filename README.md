# cra-eslint-prettier-boilerplate

My go-to setup for creating a new React app with specific Eslint and Prettier settings with a StandardJS foundation.

## Eslint

| Rule                        | Value                                                                        |
|-----------------------------|------------------------------------------------------------------------------|
| semi                        | ["warn", "always"]                                                           |
| comma-dangle                | ["warn", "always-multiline"]                                                 |
| space-before-function-paren | ["warn", { "anonymous": "never", "named": "never", "asyncArrow": "always" }] |
| react/require-default-props | "warn"                                                                       |
| import/order                | "warn"                                                                       |
| no-unused-vars              | "warn"                                                                       |
| multiline-ternary           | "off"                                                                        |
| indent                      | ["warn", 4]                                                                  |
| prettier/prettier           | "warn"                                                                       |

## Prettier

| Formatting option | Value |
|-------------------|-------|
| singleQuote       | true  |
| trailingComma     | "all" |
| tabWidth          | 4     |
