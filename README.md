# CLI-Command-Generator-Backend

## `BACKEND PLANNING`

### `BACKEND TOOLS`
  Node \
  Express \
  Knex \
  Postgres\
  Zod \

### `TABLES`

#### `User`
Pretty self explanatory. The list of users. Each user has multiple commands.

  Columns:
  -id --- integer \
  -email --- string \
  -created_at --- date\
  -modified_at ---date \
  -dark_mode ---boolean \
  -password --- hashed string \
  
#### `Command`
The base trigger of the user's CLI command. For instance `npm jest` or `npx playwright test`. Then the `parameters` table holds all the parameters that go with this command and their various options.
