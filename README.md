# Identities Text Parser

Pre-Setup for Personal Identites MK2 Parser

    Ensure all modules corresponding to imported libraries are installed.


AWS Configuration

    Create an AWS account if you haven't.
    Navigate to the AWS Management Console and locate your API key and secret keys.
    Open your terminal and run aws configure.
        Input your API key, secret key, and set your default region.
    After setting up AWS through the console, locate the section in the code that specifies the AWS region.
    Change the region in the code to match your desired AWS region.

Semaphore & CPU Settings

    Scroll to semaphore.
    Access the Task Manager by using ctrl+shift+esc and go to the Performance tab.
    Check the number of CPU threads.
    Input that number in the parentheses where it says 6.

LRU_Cache Settings

    Locate lru_cache in the code.
    Change maxsize to 5000.

Bincheck API

    Sign up for Bincheck.
    Click the URL provided.
    Input your API key.

Folder & File Management

    Create a folder on your computer.
    Place the JSON files from Dropbox into this folder.
    Set the code to pull JSON files from this folder.

Save Settings

    Scroll to the bottom of the code to df.to_excel.
    Change the path but keep the / {new_file_name} part.
