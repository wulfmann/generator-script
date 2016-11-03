#Generator Information#

This is a set of templates coupled with a bash script that allows user choices, and generates the corresponding project folders.

##Templates##
All of the template files are contained in the template directory. Based on user input and selections, the script will copy and install certain files, folders and dependencies to the folder where the script is run.

####Template sections####
There are three main sections for the templates:

*html
*styles
*gulp

The HTML directory contains all of the nunjucks template partials and layouts. If nunjucks is selected then it will copy all of those files to their respective folders.

The styles directory contains all of the different files for the different CSS preprocessors. These like the HTML, are copied to their respective folders.

The gulp folder contains a base gulpfile which includes a script to access the gulp tasks that are separated into individual modules in the gulp folder. Depending on which templateing engine and preprocessors is selected, the needed gulp tasks will be copied over.

