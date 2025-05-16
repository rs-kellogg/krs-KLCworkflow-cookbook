# Examples and exercises:

- Python setup on KLC 
    * activate or create a conda environment
    * set python interpreter in VS Code

- Push git repo to Github
    * Click on source control icon in VS Code
    * Click on the "Publish to Github" button
    * Follow the prompts to create a new repository on Github
    * Push the code to the new repository

- Clone the repo on your local machine
    * Open a new VS code window
    * Click on the "Clone Repository" button in the source control panel
    * Enter the URL of the repository you want to clone
    * Choose a local directory to clone the repository to
    * Click on the "Clone" button to start the cloning process

- Make a change to the code in the local repo
    * Open the cloned repo in VS Code
    * Make your changes to the code
    * Save your changes
    * Commit the changes to the local repo
    * Push the changes to the remote repo on Github
    * Pull the changes from the Github remote to the KLC repo

- Use Github Copilot to generate code
    * Open `dl_listing_pages.py`
    * Use `/explain` command to get a detailed explanation of the code
    * Start typing a function definition, `download_listing_page`
    * Use the `Tab` key to accept the suggestion
    * Use `Cmd-I` to start an inline chat in the python file

- Use Github Copilot to generate code
    * Open `dl_book_pages.py`
    * Use `/explain` command to get a detailed explanation of the code
    * Start typing a function definition, `download_book_page`
    * Use the `Tab` key to accept the suggestion
    * Use `Cmd-I` to start an inline chat in the python file
    * Use the Copilot chat window to get page extraction code
    * Create a dataframe from the extracted data and save it to a CSV file

- Use Github Copilot to generate tests
    * Open `test_dl_book_pages.py`
    * Use `/test` command in chat to generate test cases for the code

- Create a notebook
    * Open a new Jupyter notebook in VS Code
    * Set the kernel to the conda environment
    * Create a markdown cell to describe the notebook
    * Create a code cell to import the necessary libraries
    * Create a code cell to define the functions
