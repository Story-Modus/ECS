## Installation
1. Open Git Bash / Terminal at the project root
2. Add submodule
   ```
   git submodule add https://github.com/Story-Modus/ECS.git Plugins/ECS
   ```
## Update Flecs
1. Use release branch
2. Copy files from _**distr**_ directory to _**ECS - Source - ThirdParty - FlecsLibrary**_
3. Comment _**#define flecs_STATIC**_ line in _**flecs.h**_
