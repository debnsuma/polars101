# Installation instructions
The current recommended python versions for the course are 3.10 or 3.11

## Mac OS
- Download the course-package-linux-macos.tar.gz file
- Unzip the course-package-linux-macos.tar.gz file to a location on your system
- Run the `pip-deploy.sh` script
- Activate the virtual environment with `source course_env/bin/activate`
- Confirm the virtual environment is activated with `which python`. The output should end with `course_env/bin/python`
- Start the Jupyter notebooks with `jupyter lab`. This will either open the notebook in your browser or print a URL that you can use to open the notebook in your browser
- Check your installation by opening notebooks/TestInstallation.ipynb


## Windows
- Download the course-package.tar.gz file
- Unzip the course-package.tar.gz file to a location on your system
- Open powershell in this directory
- Run the powershell script `create-course-environment.ps1`
- Run the powershell script `activate-course-environment.ps1`
- Confirm that the virtual environment is working: it should say course_env at the start of your powershell prompt
- Run: `jupyter lab` 
- Check your installation by opening notebooks/TestInstallation.ipynb


