# Generic-Makefile

This is a generic makefile for any types of use. It allows
you to have a pain-free compile time. It is designed to have
an easy set-up for any language with explained user-defined
variables, but the `make` part behind that isn't documented.

It is suitable for executables, libraries, compiled documents,…

An example is given in the [example](./example) folder.

# Features

* Multiple file extension for sources
* Multiple source folder
* Automatic discovery of source files within the source folder
* Pre-make, pre-link and post-build hooks with arguments
* Final build inhibition (ie: build only objects file and not final executable)
* Comments explaining variables you'd probabily like to set
* File exclusion capability
* A beautiful display (imho at least :D)




#License

This project is under the zlib license.
[Read the license file](LICENSE.md)
