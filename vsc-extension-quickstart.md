# Welcome to your first VS Code Extension

## What's in the folder

- This folder contains all of the files necessary for your extension
- package.json - this is the manifest file in which you declare your extension
  and command. The sample plugin registers a command and defines its title and
  command name. With this information VS Code can show the command in the
  command palette. It doesn’t yet need to load the plugin.
- extension.ts - this is the main file where you will provide the implementation
  of your command. The file exports one function, activate, which is called the
  very first time your extension is activated (in this case by executing the
  command). Inside the activate function we call registerCommand. We pass the
  function containing the implementation of the command as the second parameter
  to registerCommand

## Get up and running straight away

- execute `npm install` in a command line to restore the add-on dependencies
- press F5 to open a new window with your extension loaded
- run your command from the command palette by pressing F1 and typing 'Hello
  World'
- set breakpoints in your code inside extension.ts to debug your extension
- find output from your extension in the debug console

## Make changes

- you can relaunch the extension from the debug toolbar after changing code in
  extension.ts
- you can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your
  extension to load your changes

## Explore the API

- you can open the full set of our API when you open the file
  node_modules/vscode/vscode.d.ts
