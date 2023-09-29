# advanced-python-homework-2023
How to create virtual enviroment

1. Ensure you have the latest version of Python.
Print 
python --version
If you have the lattest version, go to the next step. Othervise download it from the oficcial website.
2. Create a Virtual Enviroment.
Open your terminal, choose your project directory, run the next command:
python -m venv .<venv_name>
3. Activate the Virtual Enviroment.
.\<venv_name>\Scripts\activate
4. Done.
Note: if you use Virtual Studio Code, you may not have the virtual enviroment name in the beggining of the string, but your project files become green. 

If you need to deactivate your Virtual Enviroment, print
deactivate 

How to create a documentation

1. Open your project directory
cd <path>
2. Print
sphinx-quickstart
3. Answer all questions that installator asks you 
You can change all configurations in conf.py
4. Print
sphinx-build -b html source build\html