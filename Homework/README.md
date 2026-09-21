# Homework Submission Rules
*Homework Assignments Submission Rules (Absolutely important)*

Hello Class,  

1. For all homework assignments, we will use the GitHub classroom for programming assignments’ submission. TAs will post an invitation link for each assignment before the due day. For submission, all you need to do is click that link to accept that assignment, and it will redirect you to a private repository for that programming assignment. Please use only one GitHub account for submission during the whole semester.  

2. For all assignments, when submitting, please organize your code and data file as the directory structure shown in the figure below (P.S. The top-level folder is the root of the GitHub repository). Also, please use a relative path when loading your data file so that TAs can execute your Jupyter Notebook files without changing everything. Also, please avoid using “\” for specifying a path. No matter you are specifying an absolute path or a relative path, using backslash is always a bad idea since it cannot be recognized correctly in platforms other than Windows. Instead, one should always use “/”, e.g. “C:/Users/user1/Desktop”, “/usr/bin”, or “../data/notebooks”. Using the following figure as an example, the correct path should be …/data/vertebral_column_data/column_2C.dat. Do not use absolute path otherwise there is a high probability that your TAs/CPs will fail to execute your code. Points will be deducted if your TAs/CPs fail to execute your code because of not using a correct relative path in your assignments. requirements.txt is a must for all the libraries you install. readme, and gitignore are optional. Thank you for your cooperation.  

3. For each programming assignment, please use markdown cells to indicate which question you are solving. Also, use markdown cells to report your answers if the result cannot be explicitly output by your code. Thank you for your cooperation.

4. For each programming assignment, please use the “cell -> run all” function provided by the Jupyter Notebook to sequentially testing all code is working correctly. Otherwise, you may lose some points because there may be some unseen exceptions when TAs executing your code. For example, you declare a variable in a very beginning cell. Then you use that variable in the following cells. A few hours later, you think that this variable is no longer useful and you delete it. However, this variable has already been in memory. Thus, the autocomplete mechanism may push you to use that variable again and again unless you restart your notebook and finally find that variable is deprecated.

5. Please use the local Jupyter Notebook for finishing your assignment. In the previous semester, some students used the Google Colab for finishing assignments and then copied the code for the Google Colab notebook to a local Jupyter Notebook file and submitted it without testing. In this case, some unexpected exceptions may arise and the TAs have to take out some points from your assignments.

6. Please include your Name, Github Username and USC ID in the first cell of the Jupyter Notebook file for each assignment. Name your jupyter file as Lastname_Firstname_HW(i).ipynb, for example, my HW0 should look like Nandi_Soumyaroop_HW0.ipynb- Additional Instructions: A few suggestions for a cleaner submission: The below points are suggestions and good practices and not rules.

1. Try to organize all imports together (preferably in the first cell)This can help in understanding all the dependencies required to run your notebook. This might also help avoid problems that arise when cells run out of order during development.

2. References and CitationsTry to maintain a list of links/documents that you referred to while researching any algorithm at the bottom of your notebook in a markdown cell so as to support any decisions/techniques used to solve the problems in the assignments. This is also good practice so that you have a collection of links/documents that you referred for a specific problem and might save time when required in the future.

3. Plots and figures try to label (and add index) your plots wherever possible to convey information quickly and in a concise manner. Sometimes combining a few plots (eg. using subplots in matplotlib) can make your submission drastically more presentable and will help you in learning data visualization techniques using python (which is a very useful skill)

Note: Once you upload your homework, you don't need to follow up with the TAs, checking if your homework was submitted. There will be a timestamp of your submission in Github and as long as it is within the submission deadline, you don't need to worry.

Always submit a copy of your .ipynb file where the code has been executed in each cell.