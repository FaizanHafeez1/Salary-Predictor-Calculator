# Salary-Predictor-Calculator
This a simple, Jupyter Notebook Based salary predictor calculator that uses a dataset from Kaggle to estimate a salary for a prospective candidate to be used by a hypothetical HR hiring team .

User Guide:
1. Navigate the link below to download the latest Windows release of Python
https://www.python.org/downloads/
a. When going through the installation wizard, make sure to check the "Add
Python to PATH" box before clicking "Install Now."
b. This will also install the Python installation manager, Pip
2. Head over to this link https://www.anaconda.com/download/success and
download the Miniconda Windows 64 Bit - Graphical Installer
a. When going through the installation wizard, you do not need to check any
additional settings

3. To test for installation, in the Windows search bar, enter “anaconda prompt” and
click on the Anaconda Prompt App to open. It will start in a base environment.
a. Navigate to the project folder using the CD command.


4. Once in your directory, we will create the environment using the yml file in the
Anaconda command prompt within the project directory. Enter:
  a. conda env create -f environment.yml --prefix ./env
  b. This will take a while as it downloads all the required libraries.
  c. This will create the env directory within the project folder and install the
  dependencies.
  i. During this process, accept any terms of use from Anaconda

5. We will now activate the environment using the path to the project folder in the
command prompt:
a. conda activate C:\Users\Faizan\Desktop\FaizanHafeezCapstone\env
b. The path specified is to the env directory in the project folder

6. To launch the Jupyter Notebook, enter the command prompt:
a. jupyter notebook
b. This will open up Jupyter Notebook in your default browser locally with the
files in the project directory
c. Click the ClientApp.ipynb file to open the application.

7. In the menu bar, select Run, then Run All Cells. This will also take a couple of
minutes.

8. If any issues come up, you will have to select each cell and run it individually until
you reach the bottom, where the app UI is.

9. Navigate to the bottom, where the interactive sliders are, to enter values for an
estimate. Happy Hiring!

10. To close the application, close the tabs of the notebook and navigate back to the
Anaconda prompt, and press Ctrl + C
a. If you are relaunching after closing the Anaconda prompt, follow the
instructions from step 5 to reopen the application from the base directory
within the project.
