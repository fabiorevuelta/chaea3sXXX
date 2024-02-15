================================
CHAEA3S PACKAGE USER INFORMATION
================================

This text file briefly comments on how CHAEA3S package can be used.
CHAEA3S is the accronym for CHAEA Automatic Analysis Software, 
which is a Python software package developed in Python to
perform a  principal software analysis of the learning styles
present in a group of student according to CHAEA
(activist, theorist, pragmatist, and reflector).

The software provided here is distributed on an “as-is” basis,
without any warranties or guarantees of any kind.
While we have made every effort to ensure its accuracy
and reliability, we cannot be held responsible for any
unintended consequences, errors, or issues that may arise from its use.
Users are encouraged to thoroughly test the software,
review the source code, and exercise due diligence before deploying it 
in any critical environment.

By using this software, you agree to hold the developers harmless 
from any liability, damages, or losses resulting from its use.
Additionally, when sharing or distributing it,
we kindly request that acknowledge Fabio Revuelta
as the author of this software, and you cite the reference 

J. Ablanque, V. Gabaldon, P. Almendros, J. C. Losada,
R. M. Benito,  and F. Revuelta
"CHAEA3S: A software for the automated principal-component analysis
of CHAEA learning styles"
Journal of Science Education and Technology (2024)

The program has been tested in the following operating systems:

A. Ubuntu 22.04 (Linux).
B. Microsoft Windows 11.

Its use under macOS (Darwin) should be straightforward.

CHAEA3S is can be downloaded from 

https://github.com/fabiorevuelta/chaea3s

CHAEA3S is provided in three different formats:

- chaea3s.py script, to be run in a terminal.
- chaea.ipynb notebook to be run on a web broser with Jupyter.
- chaea3s.exe, to be run under Windows.

Further information on the use of CHAEA3S can be found in the refence:

J. Ablanque, V. Gabaldon, P. Almendros, J. C. Losada,
R. M. Benito,  and F. Revuelta
"CHAEA3S: A software for the automated principal-component analysis
of CHAEA learning styles"
Journal of Science Education and Technology (2024)

In any case, in order to use CHAEA3S package,
the students must first  fulfill the CHAEA questionnaires.
Then, all the questionnaires must be placed in the input folder,
which most be located in the same folder as that where chaea3s is
exceuted.

The results of CHAEA3S package will be all placed 
in the output folder, which is automatically created.
This folder contains:

- All the generated figures.
- A chaea3s.log file, with all the results that are
  also shown on the screen during the execution.
- The file CHAEA_learning_styles_summary_report.docx
  with the summary results in docx format.
- The file CHAEA_learning_styles_summary_report.pdf
  with the summary results in pdf format.

Feel free to adapt this disclaimer further to match your specific context.
And remember to give credit to us :)

Author: Fabio Revuelta
        Grupo de Sistemas Complejos
        Universidad Politecnica de Madrid
        Madrid, February 2024





--------------------------------
LINUX
--------------------------------

To execute the chaea3s.py program in the Linux terminal,
follow these steps:

1. Open a terminal window, and navigate to the directory
   where chaea3s.py is located.
   You can use the cd command to change directories.

   >> cd /path/to/directory

2. Execute the program by typing on the terminal
   the following command:

   >> python chaea3s.py

   Notice that sometimes the "python" term must
   be substituted by others, such as e.g. python3.
   Furthermore, certain libraries, such as
   matplotlib or pandas, must be installed.
   If they were not previously installed, 
   you can do it by writing on the terminal
   the following commands:

   >> python -m pip install -U matplotlib
   >> pip install pandas
   >> python -m pip install scipy
   >> pip install python-docx
   >> pip install docx2pdf
   >> pip install xlrd
   >> pip install openpyxl
   >> pip install pyarrow

3. View the generated output files (figures, summary report,
   log auxiliary file...) in the output directory.




   Alternatively, chaea3s.ipynb notebook can
   be also executed in Jupyter.
   This can be done using Jupyter Notebook
   or JupyterLab as:

1. Open a terminal window, and navigate to the directory
   where chaea3s.ipynb is located.
   You can use the cd command to change directories.

   >> cd /path/to/directory

2. Start Jupyter Notebook or JupyterLab by 
   writting on the terminal one of the following commands:

   >> jupyter notebook

   or 

   >> jupyter lab

   Any of the two pervious commands launch Jupyter server,
   and open a new tab in the default web browser
   showing the Jupyter dashboard.

3. Open the chaea3s.ipynb notebook by selecting it
   from the Jupyter dashboard. Click on it to open.

4. Execute the notebook.
   The code cells can be executed by clicking on them and
    pressing Shift + Enter, or by clicking the "Run" button in the toolbar.

   Recall that some libraries, such as matplotlib or
   pandas, are necessary. Thus, if they were not previously
   installed, you can do it by typing on the terminal before
   opening the notebook the following commands:
   
   >> python -m pip install -U matplotlib
   >> pip install pandas
   >> python -m pip install scipy
   >> pip install python-docx
   >> pip install docx2pdf
   >> pip install xlrd
   >> pip install openpyxl
   >> pip install pyarrow

5. View the output of the code cells under them.
   You can interact with the notebook and view the results as needed.
   Furthermore, all the output files (figures, summary report,
   log auxiliary file...) can be found in the output
   directory.

6. Shutdown the Jupyter server after finishing work by going back
   to the terminal/command prompt where it is running and
   pressing Ctrl + C. Confirm that you want to shutdown the server.




--------------------------------
WINDOWS
--------------------------------

To execute the chaea3s.py program
in a cmd terminal, follow these steps:

1. Open a terminal window by typing cmd, and navigate
   to the directory where chaea3s.py is located.
   You can use the cd command to change directories.

   >> cd /path/to/directory

2. Install the necessary libraries,
   by writting on the cmd terminal:

   >> python -m pip install -U matplotlib
   >> pip install pandas
   >> python -m pip install scipy
   >> pip install python-docx
   >> pip install docx2pdf
   >> pip install xlrd
   >> pip install openpyxl
   >> pip install pyarrow

3. Execute the program by typing on the terminal
   the following command:

   >> python chaea3s.py

   Notice that sometimes the "python" term must
   be substituted by others, such as e.g. python3.

3. View the generated output files (figures, summary report,
   log auxiliary file...) in the output directory.




   Alternatively, you can execute chaea3s.ipynb 
   notebook using Jupyter.
   This can be done using Jupyter Notebook
   or JupyterLab as:

1. Open a terminal window, and navigate to the directory
   where chaea3s.ipynb is located.
   You can use the cd command to change directories.

>> cd /path/to/directory

2. Install the necessary libraries,
   by writting on the cmd terminal:

   >> python -m pip install -U matplotlib
   >> pip install pandas
   >> python -m pip install scipy
   >> pip install python-docx
   >> pip install docx2pdf
   >> pip install xlrd
   >> pip install openpyxl
   >> pip install pyarrow
   
3. Start Jupyter Notebook or JupyterLab by 
   writting on the terminal one of the following commands:

>> jupyter notebook

or 

>> jupyter lab

   Any of the two previous commands launch Jupyter server,
   and open a new tab in the default web browser showing the Jupyter dashboard.

4. Open the chaea3s.ipynb notebook by selecting it
   from the Jupyter dashboard. Click on it to open.

5. Execute the notebook.
   The code cells can be executed by clicking on them and
    pressing Shift + Enter, or by clicking the "Run" button in the toolbar.

6. View the output of the code cells under them.
   You can interact with the notebook and view the results as needed.
   Furthermore, all the output files (figures, summary report,
   log auxiliary file...) can be found in the output
   directory.

7. Shutdown the Jupyter server after finishing work by going back
   to the terminal/command prompt where it is running and
   pressing Ctrl + C. Confirm that you want to shutdown the server.
   
   
   
   Finally, another alternative consist creating an
   executable program chaea3s.exe under Windows,
   which can be easily executed by simply clicking
   on its icon.
   For this purpose, go to the directory where chaea3s.py
   is found and install the libraries required.
   Then, you can use, e.g., PyInstaller.
   For this purpose,
  
1. Install PyInstaller by running the following command
   in your terminal or command prompt:

   >> pip install pyinstaller

2. Execute the following command to create a single executable file:

   >> pyinstaller --onefile chaea3s.py

The executable is found in the dir directory.

