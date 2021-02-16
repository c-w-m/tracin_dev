# Tracin Development

`tracein` development with the goal of reducing overfitting models.


# Reference Commands

## Submodules
### git clone --recurse-submodules
Clone superproject and submodules:
```shell
$ git clone --recurse-submodules
```
### git submodule add
Adding submodules to a superproject:
```shell
$ git submodule add https://github.com/c-w-m/tracin.git
```
### git submodule deinit
Remove submodule from a superproject:
```shell
# Remove the submodule entry from .git/config
git submodule deinit -f path/to/submodule

# Remove the submodule directory from the superproject's .git/modules directory
rm -rf .git/modules/path/to/submodule

# Remove the entry in .gitmodules and remove the submodule directory located at path/to/submodule
git rm -f path/to/submodule
```
