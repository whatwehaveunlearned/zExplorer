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
