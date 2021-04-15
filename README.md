# Welcome to the Didact Tutorials Registry!

*Note:* This is a work in progress and proof of concept!

The goal of this GitHub repository is to provide a location where links to tutorials of all kinds can be placed for easy access. Pick one and copy the link to make it available from within your `Didact Tutorials` view! 

## Using these links

To add these tutorials to the Didact Tutorials view in your local VS Code workspace or simply start them in a new Didact window, do the following:

* Copy the link text for the tutorial from this page.
* Launch VS Code Quick Open (Ctrl+P), type `Didact: Process vscode link from web`, and press enter. 
* The command will pick up the URL from the clipboard and register or start the tutorial.

### Requirements Example

Provides examples of how to handle requirements checking in Didact tutorials. 

* Copy this text to the clipboard to register the tutorial: `vscode://redhat.vscode-didact?commandId=vscode.didact.registry.addUri&&https=raw.githubusercontent.com/redhat-developer/vscode-didact/master/examples/requirements.example.didact.md&&name=Requirements%20Example&&category=From%20The%20Web`
* Copy this text to the clipboard to start the tutorial: `vscode://redhat.vscode-didact?https=raw.githubusercontent.com/redhat-developer/vscode-didact/master/examples/requirements.example.didact.md`









## Try this

<a href="vscode://redhat.vscode-didact?commandId=vscode.didact.registry.addUri&&https=raw.githubusercontent.com/redhat-developer/vscode-didact/master/examples/requirements.example.didact.md&&name=Requirements%20Example&&category=From%20The%20Web" target="_blank">VS Code requirements example</a>

<a href="http://example.com">Link</a>

### These Methods Don't Work

[VSCode link from web - does not work, link is hidden](vscode://redhat.vscode-didact?commandId=vscode.didact.registry.addUri&&https=raw.githubusercontent.com/redhat-developer/vscode-didact/master/examples/requirements.example.didact.md&&name=Requirements%20Example&&category=From%20The%20Web)

![vscode://redhat.vscode-didact?commandId=vscode.didact.registry.addUri&&https=raw.githubusercontent.com/redhat-developer/vscode-didact/master/examples/requirements.example.didact.md&&name=Requirements%20Example&&category=From%20The%20Web](./button_copy-link.png) (This doesn't work)
