# Purpose
To illustrate the different ways to import modules and packages that allow different file management organization in python.

# Use case
when you multiple scripts using shared components where you may have many src directories
such as below;


common  {shared modules}
src     {scripts}
src/dataImportScripts/createDatamart1
src/dataImportScripts/createDatamart2
src/dataImportScripts/createDatamart3

# Using
- The code in in examples
- You will have to run the code to remove imports from memory (noted in code) to be able to test the imports

# Notes
It is important to note that once a module is imported it is then in memory meaning that if you change the import it will not refresh automatically 

# How to change Imports
- 1 change code in the module to be imported
- 2 run the code that is below the annotation "# run this if you edit the import module"
- 3 rerun that import script and you will THEN see your changes reflected
