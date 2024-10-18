# Package example

This is a simple example of a package and it has little to no functionality.

## Installation

```bash
 npm i loa-package-demo
```

## Usage

```typescript
import { add, subtract, multiply } from 'loa-package-demo';

const result = add(1, 2); // 3
const result2 = subtract(2, 1); // 1
const result3 = multiply(2, 3); // 6
```

## Make changes to the package:

This is to remember how to make changes to the package:

1. Make a change
2. Run `ci` to make sure everything is working
3. Run `npm run bump` to create a new version tag and update the package.json
4. Create a PR and merge it - this will trigger the CI/CD pipeline and publish the new version to npm
