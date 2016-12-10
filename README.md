# aurelia-cli-electron-app

requires:
  * nodejs 6
  * `npm install aurelia-cli -g`

**install and run:**

```shell
npm install
au run
```
**build (vscode)**
* press Ctrl+Shift+B
* or select a task from the task menu
**debug (vscode):**
* add breakpoints
* press f5. 

**test:**

[The unit test requires the app to be built](https://github.com/aurelia/cli/issues/370)

```shell
au build
```

Once the app is build, you may execute:

```shell
au test --watch
```
**test (vscode)**
* press Ctrl+Shift+B
* then select a test from the task menu