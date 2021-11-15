# UUID

Lightweight (500 byte) web-based UUID utility functions.

- native UUID v4 support
- UTC time ordered UUIDs

## Installation

Install via NPM

```bash
npm i -S @codewithkyle/uuid
```

Install via CDN

```html
<script src="https://unpkg.com/@codewithkyle/uuid@1/uuid.min.js"></script>
```

```javascript
import { UUID, orderedUUID } from "https://unpkg.com/@codewithkyle/uuid@1/uuid.min.mjs";
```

## Usage

```typescript
import { UUID, orderedUUID } from "@codewithkyle/uuid";

UUID() // 2834d4a2-4768-41d6-be77-e14b1d2c3a93
orderedUUID() // 94e2c93c-4394-45e9-abff-0d88b0bd9eff
```
