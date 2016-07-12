# node-app-hackathon

## Dependencies
- You must have `node v >= 4.0` and `npm` installed (via `brew install node` or [NodeJS.org](https://nodejs.org/en/));
- `npm i -g typings webpack-dev-server webpack rimraf`
- If you have previously installed `typings`, be sure you are on `version 1.x` as this repo requires it

## Getting Started


```bash
git clone https://github.com/ArthurManz/node-app-hackathon.git
cd node-app-hackathon
npm i
typings install
npm start
```

Then navigate your browser to http://localhost:3001 and use the app.

## Testing
The test setup includes `webpack.test.config.js`, `spec-bundle.js`, and `karma.conf.js`. To run unit tests, execute `npm test` in your terminal.
