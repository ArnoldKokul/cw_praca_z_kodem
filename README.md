Instructions for installation and running the app:

Begin with:
1. Make sure Python is downloaded (version 3.9 or higher). You can download the latest version from Python.org
2. Download and install Git, available at https://git-scm.com/downloads

Cloning the repository:
1. Clone the repository to your computer:
       git clone https://github.com/ArnoldKokul/cw_praca_z_kodem

Installation of dependencies:
1. Open the terminal
2. Go to project catalog:
       cd cw_praca_z_kodem

3. Create the virtual environment:
       python -m venv venv

4. Activate the venv:
       activate

5. Install the libraries:
       pip install -r requirements.txt
       pip install flask
       pip install makefile
   

Run the app:
1. While in the project catalog:
       python -m flask run

Other information:
1. Structure of the project should look like this:
       cw_praca_z_kodem
             |-- templates
             |    |-- index.html
             |    |-- hello.html
             |-- app.py
             |-- requirements.txt
             |-- README.md
2. Make sure to regularly update the dependencies if you add more libraries, using the command:
       pip install -r requirements.txt

If you have any questions or problems, don't hesitate to contact the authors of the project.
