# POG

## Installation

### Yarn

```
yarn add @edukinara/pog
```

## Usage

### Use Module

```typescript
// @ts-ignore
import { prismaOffsetPagination } from '@edukinara/pog';

...
const result = prismaOffsetPagination({
    model: User,
    cursor: <cursor>,
    size: 5,
    buttonNum: 7,
    orderBy: 'id',
    orderDirection: 'desc',
    where: {
      email: {
        contains: 'smallbee',
      },
    },
});
```
