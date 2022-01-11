# zExplorer
Zexplorer

The Zexplorer project comprises of three repositories:

Two are mantained by me:

[SageBrain](https://github.com/whatwehaveunlearned/zExplorerPythonServer): Python Server to manage data.
[zotAngular](https://github.com/whatwehaveunlearned/zExplorer_ZotAngular): Frontend interface in angular.

Another is an external repository:

[Bert_as_a_service](https://github.com/hanxiao/bert-as-service) 

The 3 repositories should be downloaded into the same directory in the computer.

SageBrain and ZotAngular have 2 main branches Master and user study.

The difference between them is that Master contains the original application with a dashboard and an importer to select different documents from zotero collections. Also it uses an encoder model to learn the user model.
User study preselects a group of documents that get passed to the system hardcoded into one of my zotero collections. Also it uses a contrastive model to imitate the document movement. User study incorporates functions to execute both encoder and contrastive models.

# How to install zExplorer

Download the three repositories and store them in your local system. They can be installed in different paths but I recommend installing all the projects in the same path. 

For example: /zexplorer_project

/zexplorer_project/SageBrain

/zexplorer_project/zotAngular

/zexplorer_project/Bert_as_a_service

You will need to install python3 and all the necesary python packages for SageBrain.
You will need to install Node version V8.15.0 for zotAngular and also install all the dependencies for the angular project.
If you need different node versions installed I recommend using NVM node manager.

# To start project

1. Launch Bert_as_a_service server by: $ bert-serving-start -model_dir {{path_to_your_model}}/ -num_worker=4
2. Launch SageBrain by navigating to SageBrain Folder and: $ jupyter sageBrain.py
3. Launch zotAngular by navigating to zot_angular_app folder and: $ ng serve
