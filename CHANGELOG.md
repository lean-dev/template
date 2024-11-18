# Changelog


## v18.0.0

[compare changes](https://github.com/lean-ng/template/compare/v17.0.1...v18.0.0)

### 🚀 Enhancements

- Add eslint v9 with the now clean: ng add @angular-eslint/schematics ([c158f87](https://github.com/lean-ng/template/commit/c158f87))
- Simplify prettier config and drop sort plugin. ([719a4e2](https://github.com/lean-ng/template/commit/719a4e2))

### 🩹 Fixes

- Remove all eslint deps. Prepare upgrade for eslint v9 ([f6066aa](https://github.com/lean-ng/template/commit/f6066aa))

### 🏡 Chore

- Again remove the @angular-eslint/schematics. Still a bug to have that in the deps. ([b12aaa1](https://github.com/lean-ng/template/commit/b12aaa1))
- Upgrade angular via "ng update @angular/core@18 @angular/cli@18" ([58c92fb](https://github.com/lean-ng/template/commit/58c92fb))

### ❤️ Contributors

- Micha Buchholz <mail@lean-stack.rocks>

## v17.0.1

[compare changes](https://github.com/lean-ng/template/compare/v17.0.0...v17.0.1)

## v17.0.0

[compare changes](https://github.com/lean-ng/template/compare/v1.0.3...v17.0.0)

### 🩹 Fixes

- Remove the @angular/schematics dependency. Not needed and not usefull ([30e33c8](https://github.com/lean-ng/template/commit/30e33c8))

### 🏡 Chore

- Force update of zone.js and typescript. ([098e646](https://github.com/lean-ng/template/commit/098e646))
- Upgrade angular via "ng update @angular/core@17 @angular/cli@17" ([eda5489](https://github.com/lean-ng/template/commit/eda5489))
- Update linting. Again with the schematics: ng add @angular-eslint/schematics ([40b8ca7](https://github.com/lean-ng/template/commit/40b8ca7))

### ❤️ Contributors

- Micha Buchholz <mail@lean-stack.rocks>

## v1.0.3

[compare changes](https://github.com/lean-ng/template/compare/v1.0.2...v1.0.3)

### 🩹 Fixes

- Loose cli version strategy. ([37170ec](https://github.com/lean-ng/template/commit/37170ec))
- Loose version strategy of angular-eslint packages. ([e074bb9](https://github.com/lean-ng/template/commit/e074bb9))

### 💅 Refactors

- Improve typescript settings. ([c7b7272](https://github.com/lean-ng/template/commit/c7b7272))

### 🏡 Chore

- **dx:** Upgrade prettier. ([d104ab6](https://github.com/lean-ng/template/commit/d104ab6))
- Upgrade typescript linting. ([70561c5](https://github.com/lean-ng/template/commit/70561c5))

### ❤️ Contributors

- Micha Buchholz <mail@lean-stack.de>

## v1.0.2

[compare changes](https://github.com/lean-ng/template/compare/v1.0.1...v1.0.2)


### 🩹 Fixes

  - Remove lock file. That's a template project! ([0a87e5b](https://github.com/lean-ng/template/commit/0a87e5b))

### ❤️  Contributors

- Micha Buchholz ([@lean-dev](http://github.com/lean-dev))

## v1.0.1

[compare changes](https://github.com/lean-ng/template/compare/v1.0.0...v1.0.1)


### 🩹 Fixes

  - Add missing typescript plugin. ([fd37f3c](https://github.com/lean-ng/template/commit/fd37f3c))
  - Remove verbatimModuleSyntax as it breaks importing services and angular as well. ([fc12ff1](https://github.com/lean-ng/template/commit/fc12ff1))

### ❤️  Contributors

- Micha Buchholz ([@lean-dev](http://github.com/lean-dev))

## v1.0.0


### 🏡 Chore

  - Scaffold angular app. Initial commit. ([3b784f6](https://github.com/lean-ng/template/commit/3b784f6))
  - Update readme and add license. ([5ba15ba](https://github.com/lean-ng/template/commit/5ba15ba))
  - Remove tests, test task and skip test scaffolding. ([07a205e](https://github.com/lean-ng/template/commit/07a205e))
  - Remove external style files. ([a385838](https://github.com/lean-ng/template/commit/a385838))
  - Add linting support via eslint. ([78ccff0](https://github.com/lean-ng/template/commit/78ccff0))
  - Remove default app prefix and adjust lint rule. ([cfe1765](https://github.com/lean-ng/template/commit/cfe1765))
  - Change lint rule for directive-selectors. ([7d67bda](https://github.com/lean-ng/template/commit/7d67bda))
  - Remove VSCode config folder and add instructions in readme. ([3bd7f54](https://github.com/lean-ng/template/commit/3bd7f54))
  - Remove by now not needed assets folder. ([575a2ab](https://github.com/lean-ng/template/commit/575a2ab))
  - Remove by now not needed i18n task. ([a8b4b95](https://github.com/lean-ng/template/commit/a8b4b95))
  - Update, reorganize and comment tsconfig. ([9632cd0](https://github.com/lean-ng/template/commit/9632cd0))
  - Remove ts test project - due to not having tests by now. ([7cbfba3](https://github.com/lean-ng/template/commit/7cbfba3))
  - Clean up app component. ([b95f0a3](https://github.com/lean-ng/template/commit/b95f0a3))
  - Provide local prettier, add npm task with first run done. ([0c9f681](https://github.com/lean-ng/template/commit/0c9f681))
  - Add import sorting plugin for prettier. ([3a45525](https://github.com/lean-ng/template/commit/3a45525))

### ❤️  Contributors

- Micha Buchholz ([@lean-dev](http://github.com/lean-dev))

