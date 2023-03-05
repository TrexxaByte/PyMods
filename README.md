# PyMods
For all intents and purposes, this development is a practice run, learning experience, and coding exercise. Unfortunately,
my teacher sucks major ass... as I'm learning in my spare time... self taught. LOL :P

Any guidance is openly welcomed and greatly appreciated - constructive criticism and all! 

DESCRIPTION
=============================
Automated command line Python module / package updater with options to update all, update only specified modules, and display list of outdated with no updating.
I've considered incorporating automatic updating - either for all outdated or only user specified - if I continue to progress and further develop the project.

USAGE
=============================
C:\> python pymods -a | --all                               Updates all outdated modules / packages indicated via pip.

C:\> python pymods -f <filepath> | --file <filepath>        Reads a comma delimited or newline separated list of modules and updates only those specified by the user.

C:\> python pymods -l | --list                              Returns a list of outdated modules found on the local system as well as a dictionary with module names as
                                                            keys and the current -> newest versions of the module as the key values.
