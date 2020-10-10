# doxygen

To clone this repo with submodules, run `git clone --recurse-submodules http://github.com/dafoam/doxygen`

To generate new documentation for DAFoam

- First install Doxygen: `sudo apt-get install doxygen graphviz`

- Go to the dafoam folder and get the latest version of dafoam: `git pull origin master`

- Change `PROJECT_NUMBER` in Doxyfile

- Delete the docs/html folder (old documentation)

- Run `doxygen Doxyfile` to generate new documentation

- Finally, push the latest to Github: `git add . && git commit -m "Update." && git push`
