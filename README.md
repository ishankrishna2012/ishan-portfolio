# Ishan Krishna Verma Portfolio

A minimal editorial portfolio for Ishan Krishna Verma, built with React, TypeScript and Vite.

## Local development

```bash
npm install
npm run dev
```

## Personal npx command

This repo includes a small npm binary at `bin/ishan.js` and maps it through `package.json`:

```bash
node bin/ishan.js
node bin/ishan.js --links
node bin/ishan.js --help
```

After publishing the package to npm, the public command can be run as:

```bash
npx ishan
```

If the npm package name `ishan` is unavailable, publish under an available package name while keeping the binary name as `ishan`; for example, users can still run the installed binary after global install or through package-specific npx usage.
