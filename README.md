# My Undergrad Thesis: Decision Visualizer
Repository to hold my 4490Z thesis under Professor Kamran Sedig at Western University Canada. 
This program will create a classification decision tree. 

# How to use

-Iris Visualizer can be run by simple running a local web server in the Iris Visualizer folder. The program rums on an HTML page. 

-Generic Visualizer is a bit more complicated
	-Appendix - B of CS4490Z_AtherQureshi_Thesis.pdf will outline specifics. 

You must have Python 3.62 installed, along with the libraries Numpy, Pandas, Bs4, and sci-kit learn. 

	1. Download Generator.py, generic_tree.html, and the README.txt to a folder on your
		Computer.

	2. Add in a properly formatted CSV file into the folder (Specifics found on page 11 of CS4490Z_AtherQureshi_Thesis.pdf)

	3. In a terminal, write via command line in the folder, type “python Generator.py x” where x is your csv
		file. This should generate two JSON files (tree and data), and a html page called index.


	4. Run a local server in the folder. 
		For instance, if you have python
		ex. In a terminal, write via command line in the folder, type ‘python -m SimpleHTTPServer 8000”, and
			leave the terminal open. This will host a local web server in the folder that you can access.

	5. Open a browser (Chrome is recommended) and visit the URL “localhost:8000” to see your
		visualization! 