# Test in local

This a debug config for typescript express project in a src folder

- `yarn`
- `yarn debug` you should see "Waiting for debugger"
- Go to VSCode debugger and click ion Attach
- Set a breakpoint at the `res.send` instruction
- `curl localhost:3000`
- check the breakpoint in vscode

# Test in your project 

- Install all the dependencies in your project (you should need only nodemon)
- add the script `"debug": "nodemon --config nodemon-debug.json"`
- Add the `.vscode/launch.json` Attach config
- run `yarn debug`
- Start the debugger