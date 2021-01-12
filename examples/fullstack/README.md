# example for https://github.com/cypress-io/code-coverage/issues/380

1. Run the app
```sh
$ npm run dev
```
2. Check generated report.

**Expected result:**
HTML and cobertura reports should be generated in examples/fullstack/coverage, according to package.json config.

**Current result:**
Default set of reports is generated in examples/fullstack/test/ui/coverage, also generated report paths are messed up.
