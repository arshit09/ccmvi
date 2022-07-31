# ccmvi

How to run the program?

1. Install Python 3 (https://www.python.org/downloads/release/python-3913/)
2. Install Jupyter Notebook (https://jupyter.org/install)
3. Install Pandas, Numpy, Statistics and Shutil library using following insturction:
	3.1 Open 'Command Prompt' on your machine.
	3.2 Execute following commands one by one:
		pip install pandas
		pip install numpy
		pip install statistics
		pip install pytest-shutil
4. Open one and only main file 'CCMVI.ipynb' in Jupyter Notebook.
5. Now in the code,
	5.1 Copy the folder path which contains all of the CSV files into 'input_folder' variable.
	5.2 Set path to save the imputed files into 'output_folder' variable.
	5.3 Set path for original dataset into 'original_dataset' variable to calculate NRMS value.
	5.4 Set path to 'analysis_file' variable to save the datasheet of analysis for each file (i.e. NRMS values, Run time, Key parameters).
6. Execute the program.