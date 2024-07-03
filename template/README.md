# <PACKAGE NAME>

Your description

## Features

- Feature 1
- Feature 2

## Installation

```
npm install <PACKAGE NAME>
```

## Usage

````ts
import { <EXPORT NAME> } from '<PACKAGE NAME>';
````

<!--- @@inject: dist/docs/modules.md#Functions --->

<!--- @@inject-end: dist/docs/modules.md#Functions --->

<!--- @@inject: dist/docs/interfaces/*.md#Properties --->
REPLACE THIS BLOCK WITH AS MANY REFERENCE TO GENERATED INTERFACE DOCUMENTATION AS YOU NEED
<!--- @@inject-end: dist/docs/interfaces/*.md#Properties --->


## Contributing

This project uses ASDF and Yarn.

1. clone repo
2. make branch: `git checkout [fix|feat|docs|chore]/blah-blah` (see [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
3. run `./tools.sh`
4. run `just setup`
5. run `just demo`
6. run `just unittest`
7. run `just lint`

## Todo

- [ ] Add more tests
