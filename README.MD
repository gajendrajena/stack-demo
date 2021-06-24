# Learning TDD in javascript via https://www.youtube.com/watch?v=Jv2uxzhPFl4&ab_channel=Fireship

Implement a stack following TDD in js.

## creating empty application
```sh
npm init @vitejs/app
```

## Add jest to the application

```sh
npm install jest --save-dev
```
# Add test config to run the tests
add the following to package.json file under scripts

```json
    "test": "jest --watchALL --verbose --coverage"
```
## running tests from cosole
```sh
cd stack-demo
npm run test
```

# Add coverage
update the jest config in package.json file under scripts to have coverage

```json
    "test": "jest --watchALL --verbose --coverage"
```
