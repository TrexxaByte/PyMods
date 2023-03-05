# PyMods
For all intents and purposes, this development is a practice run, learning experience, and coding exercise. Unfortunately,
my teacher sucks major ass... as I'm learning in my spare time... self taught. LOL :P

Any guidance is openly welcomed and greatly appreciated - constructive criticism and all! 

DESCRIPTION
=============================
Automated command line Python module / package updater with options to update all, update only specified modules, and display list of outdated with no updating.
I've considered incorporating automatic updating - either for all outdated or only user specified - if I continue to progress and further develop the project.

USAGE
===========================================================================================================
| 	Command										                |	Description												                        |
|---------------------------------------------------------------------------------------------------------|
| python pymods -a OR --all						        | Updates all outdated modules / packages indicated via pip.|
|												                      |															                              |
| python pymods -f OR --file **<filepath>**		| Updates only user-specified modules listed in <filepath>	|
|												                      | modules should be comma delimited (no space) or separated	|
|												                      | by newline carriage returns - one on each line.			      |
|												                      | 											                                    |
| python pymods -l OR --list					        | Returns list of all outdated modules found on the local	  |
|												                      | system - also returns dictionary with module names as keys|
|												                      | and the current -> newest versions for that module.		    |
|==========================================================================================================
