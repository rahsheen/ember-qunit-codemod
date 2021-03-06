# ember-qunit-codemod

This codemod is intended to automatically convert your projects from the older
`moduleFor*` syntax of `ember-qunit@2` to the newer syntax proposed by [emberjs/rfcs#232](https://github.com/emberjs/rfcs/blob/master/text/0232-simplify-qunit-testing-api.md).

## Installation

```sh
npm install -g ember-qunit-codemod
```

## Usage

```sh
ember-qunit-codemod ./tests/
```

This codemod can be used in conjunction with [ember-test-helpers-codemod](https://github.com/simonihmig/ember-test-helpers-codemod).

## Credit

ember-qunit-codemod is heavily inspired by the work done in [qunit-dom-codemod](https://github.com/simplabs/qunit-dom-codemod)
and [ember-mocha-codemods](https://github.com/Turbo87/ember-mocha-codemods)
largely by Tobias Bieniek. Thank you!
