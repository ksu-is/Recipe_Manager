# foodmanager
Yet another tool to manage receipes, shopping lists and your daily menu

For quite some time, I looked around for a tool, that allows me to store my favorite receipes, easily generate shopping lists out of them and put up a daily menu. But no tool around satisfied all my needs. So I started my very own foodmanager.
There is no fixed roadmap, no release cycle and absolutely no idea, where this will end up. But if you are interested in the topic, feel free to help, either by cloning and working on your own set of ideas, or by contacting me to help further developing this branch.

## Getting started (Updated 11/28/2018)
To get involved with development, clone the repository to your local IDE and perform the following tasks:
- Install Github Desktop
- Clone 'foodmanager' repository to your local IDE
- Using the Command Prompt, navigate to the Project Folder
- Create a virtual environment using 'virtualenv'
- Activate the virtual environment using 'venv\Scripts\activate'
**Created a requirements.txt dependency file. Installed Django onto this**
    - pipreqs 'Project Folder Location'
    - pip freeze > requirements.txt
    - 'requirements.txt pip install django' - This creates the base requirements.txt information
- To install dependencies type 'pip install -r requirements.txt'
- Create a database with the correct structure by running `manage.py migrate` in the CLI
- Add a super-admin user to the database to start playing around by running `manage.py createsuperuser`
- You will be prompted to enter username, password, and email.
- Create a local development server using 'manage.py runserver'
    - This creates a localhost:8000 server
    - From here, you can use localhost:8000/planner to view the planner HTML Page
    - From here, you can use localhost:8000/admin to view the Django administrator page
            - Enter information you provided for super-user account into django admin page
            - Begin adding recipes, adding calenders, adding users, groups, and much more.
- End development server connection using 'CTRL-C'

## Contact
The foodmanager project was started and is currently run by Christoph Krammer <chris@twotigers.de>.
## Updated Contact: (11/27/2018)
Currently being tested by Jackson Draper. For questions and concerns contact <jdraps94@gmail.com>.
