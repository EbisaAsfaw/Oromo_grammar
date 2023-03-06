
# Package name

oromo_grammar package

# Project Title

A Python package that automatically generates grammar-aware Oromo phrases from a given raw text.

## Description

This is a novel python package that recieves an Oromo text file from a user; extract every possible root-verbs from the text;
and stores them into a python list. It then trims all the verbs in the list to form their corresponding list of stems.
Finally, the algorithm builds the corresponding phrases from the stems using an appropriate affixation and personal pronouns. 
The package can be customized and be replicated for any other languages according to the gramatical structure of the language.
It helps relief machine learning and NLP practitioners,by automatically generating a clean and grammar-aware dataset,which was 
used to be done only manually. The generated Oromo phrases can indicate sentence elements like, number, gender and cases. The 
automatically generated Oromo phrases can be applied to different machine learning applications. It can form a clean phrase-based
dataset that can help to train a Neural Machine Translation (NMT). It can also form a word and phrase-based dictionery, that will
help in automatic word/sentence completion. The output of this tool is also helpful for Linguistics, in providing a clean and
correct gramatical information of a given language.
  
## Getting Started

### Dependencies

* This software package can run on any platform/OS(Windows, Linux, or Mac) and no prerequisites is given, except the Python Software Specifications.
* This software requires Python 3.8 or latter versions, with some useful liberary packages, like NumPy, for a smooth excusion.

### Installing

* Before installing "oromo_grammar" package first check that you have Python 3 software,installed on your device.
* To install Python 3 software on your machine, first download and install the latest python version from "https://www.python.org/".
* Install numPy liberary with python software, if not availabe.
* To install and use this package, you can navigate to the open distribution PyPI package, "https://pypi.org/", and get the full package name.
* The easiest way to install the package is via pip (pip3 in some distributions): "pip install oromo_grammar" -for Window, or
* "pip3 install oromo_grammar" -for Unix/macOS.

### Executing the program


* To use the oromo_grammar program package:

* First open the Python script that you have installed, and type the fowllowing import package.
* >> from oromo_grammar import auto_grammar # type and run this line from your python script to import the main module from the package oromo_grammar.
* Copy and paste the path: "https://www.github/EbisaAsfaw/OroAutoGrammar/oro_text.txt", or your own file from your local directory, into the opened text box.

* If you are opt to enter your own text file into the textbox, do the following:

* First prepare/get an Oromo text and save it as a text document, "oro_text.txt".
* Save the file into your working directory/ user directory/ (e.g., "C:\Users\Eba\oro_text.txt")
* Copy and paste the fully directory path of your file (e.g., "C:\Users\Eba\oro_text.txt") into the text box, and click enter.
* Then go a head and check the generated csv file that is created  for you into "downloads" folder of your local machine. 
* There you will find a csv file that contains generated Oromo grammar dataset, with the file name, 'oro_auto_generated_grammar.csv'
* That is all done!

## Authors

Contributors names and contact info

Ebisa A. Gemechu  
@Ebisa |lammiyad@yahoo.com| (https://www.linkedin.com/ebisa-asfaw-39566361)

## Version History

* 0.0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE file for details
