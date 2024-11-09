# Template-for-VueJs-Projects
This is a template repository for kickstarting the development of VueJs projects
## Usage

### Dependencies
```sh
npm install
```

### Run the project in Dev mode
```sh
npm run dev
```

### Run Unit Tests using [Vitest](https://vitest.dev/)
```sh
npm run test
```

### Code formatting with [Prettier](https://prettier.io/)

#### Check code format
```sh
npm run format:check
```

#### Format code
```sh
npm run format:write
```

### Code linting with [ESLINT](https://eslint.org/)

#### Check for code errors
```sh
npm run lint:check
```

#### Correct code from errors
```sh
npm run lint:fix
```
## Git Hooks

The template comprises also two Git hooks,  if at least one of these fails, a Git commit is not produced:
- `pre-commit` hook verifies that tests, code format and linter checks complete successfully before applying the commit;
- `commit-msg` ensures that the commit message follows the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) specification.

## CI/CD

Navigate to the *Let's Stream It* report to see the details of the CI/CD pipeline: [Report link](https://letsstreamit.github.io/documentation/report/devops/#version-control).
