# yarn

A [dagger action](https://docs.dagger.io/1221/action) based on the todoapp example. It installs, build and tests a node app that uses yarn as its package manager.

## Example Usage 

1. Install this action to your dagger project via `https://github.com/Bilaltariq98/yarn.git@v0.0.1` 
2. Import into your dagger project and provide `clientFileSystem` as an input (with the location of the source code to be tested and built)
3. Use the output as reqired

An example usage of this action can be found [here](https://github.com/Bilaltariq98/todoapp-dagger/blob/master/todoapp.cue)
