# cap-starter

## Starter project for caprover projects

Utilizes docker for deployment so some change will need to be made to fit your needs.

There is a `example.deploy.yml.remove` file within github workflows that must be updated to match your needs.

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run src/index.ts
```

This project was created using `bun init` in bun v1.0.2. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
