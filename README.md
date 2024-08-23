%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% MODEL MADE BY PRUNELLE DAUDRÉ--TREUIL, USE AT YOUR OWN RISK, YOU HAVE BEEN      %
% WARNED !                                                                        %
% COPYRIGHT : CC-BY-SA                                                            %
% LAST UPDATE : 12-04-2024                                                        %
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

## Usage instructions :   

1. Modify your personal information in info.tex                               
2. Compile with XeLaTeX or LuaLaTeX, if you don't know how ask me             
3. I have nothing else to say for the moment, if anything is broken ask me    

## What did I do :                                                               

* personalize the metropolis theme in yellow                               
* modify/add progression bars                                              
* fixed the table of contents                                              
* modify the section page and add a subsection page for long presentations 
* create a pretty (yellow) box to put some text in emphasis like definition, theorem, etc ...  
* add different compilation options
* propose a well organised folder hierarchy and some variables for easier personalisation
* use the part page to modify the \appendix command results and add a \maketoc command

## Folders/files organisation : 

1. config folder : all configuration files in .tex, load with input, I separate them to keep it easy to read and to maintain. Lib and tikz are easy to modify, title more tricky, I would not recommand touching style. Some logo are hidden here, please don't remove. The documentation of the beamer class and the metropolis package are also here.
2. img/slides folders : this is just a suggestion of organisation, do as you want
3. config.tex : just a shortcut to load all configuration settings in one input
4. info.tex : title, subtitle, author and other information needed by this template including the logo used
5. presentation.tex : your main file
6. README.md : the present file
7. sample.bib : the bibliography

I will let some example slides to show what can be done (and flex my skills <3), have fun with it, love you all <3                                              