# Javascript Sample Codes

A curated collection of small JavaScript sample programs, snippets, and patterns to demonstrate common language features, algorithms, browser APIs, and Node.js usage. This repository is ideal for beginners learning JavaScript and for developers looking for quick reference examples.

## Table of Contents

- [About](#about)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [How to Run Samples](#how-to-run-samples)
- [Contributing](#contributing)
- [Development Guidelines](#development-guidelines)
- [License](#license)
- [Author](#author)

## About

This repo groups concise, self-contained JavaScript examples by topic (e.g., basics, DOM, asynchronous programming, Node.js, data structures & algorithms). Each sample should be runnable with minimal setup and include a short explanation in a README or header comment.

## Repository Structure

A suggested structure — adjust to match actual contents:

- basics/
  - hello-world.js — simple console output
  - variables-and-types.js
- dom/
  - dom-manipulation.html
  - event-handling.js
- async/
  - promises.js
  - async-await.js
  - fetch-example.js
- node/
  - http-server.js
  - file-io.js
- algorithms/
  - sorting/
    - bubble-sort.js
    - quick-sort.js
  - search/
    - binary-search.js
- utils/
  - helpers.js
- tests/
  - (optional sample tests using Jest or Mocha)
- package.json (optional; helpful for scripts and dependencies)
- README.md

If your repo differs, I can customize this section once you share the actual tree.

## Getting Started

Prerequisites:
- Node.js v14+ (recommended) for Node samples
- A modern browser for DOM samples
- Optional: npm or yarn if using package.json

Clone the repository:
```bash
git clone https://github.com/PrashantRatanparikhe/Javascript-Sample-Codes.git
cd Javascript-Sample-Codes
```

Install dependencies (only if a package.json exists):
```bash
npm install
# or
yarn
```

## How to Run Samples

Run a Node sample:
```bash
node basics/hello-world.js
```

Run a Node server sample:
```bash
node node/http-server.js
# then open http://localhost:3000 in a browser (if the sample uses port 3000)
```

Open a browser sample:
- Open the HTML file in the `dom/` folder (e.g., open `dom/dom-manipulation.html`).

If package.json includes scripts, run them:
```bash
npm run start
npm run test
```

## Example: hello-world.js
```js
// basics/hello-world.js
console.log('Hello, world!');
```

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a branch: `git checkout -b feat/my-sample`.
3. Add your sample under an appropriate directory. Each sample should:
   - Be self-contained and small.
   - Include comments explaining purpose and usage.
   - Follow ES6+ style (prefer const/let, arrow functions where appropriate).
4. Add/Update tests if applicable.
5. Commit changes with meaningful messages.
6. Open a pull request describing the sample and rationale.

Please follow the code style and add a brief README or header comment for each new sample.

## Development Guidelines

- Keep samples short (~10–100 lines).
- Prefer clarity over cleverness.
- Avoid external dependencies unless necessary; if used, document them in package.json.
- Use descriptive file names and folders.
- Add license and author attribution headers if needed.

## License

This repository is available under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Prashant Ratanparikhe

Contact: https://github.com/PrashantRatanparikhe
