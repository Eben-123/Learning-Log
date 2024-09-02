# Learning-Log
Learning Log will allow users to log topics, hobbies they're interested in and make journal entries


## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/Eben-123/Learning-Log.git
    ```

2. Navigate into the project directory:

    ```
    cd Learning-Log
    ```

3. Create a virtual environment (recommended):

    ```
    python -m venv name_of_env
    ```

4. Activate the virtual environment:

    ```
    source name_of_env/bin/activate
    ```

5. Activate the virtual environment:

    ```
    source name_of_env/bin/activate
    ```

6. Install the packages:

    ```
    pip install -r requirements.txt
    ```

7. Open your web browser and navigate to http://localhost:8000 to view the app.

## Project Structure

Here is a breakdown of the project structure:

```
├── learning_log/
├── learning_logs/
|   ├── urls.py
|   ├── views.py
│   ├── migrations/
│   ├── templates/learning_logs/
|   |                   ├── //User Interface pages
|   |                   ├── base.html
│   |                   ├── edit_entry.html
|   |                   ├── index.html
|   |                   ├── new_entry.html
|   |                   ├── new_topic.html
|   |                   ├── topic.html
|   |                   ├── topics.html
├── users/
│   ├── urls.py
│   ├── views.py
│   ├── /templates/registration/
|   |                   ├── //Authentication pages
|   |                   ├── login.html
│   |                   ├── logout.html
|   |                   ├── register.html
├── .gitignore
|── manage.py
|── Procfile
├── requirements.txt
|── runtime.txt
├── README.md
```

-   `learning_log`: contains all the project dependencies.
-   `learning_logs`: contains any other user interface that will be served by the development server or included in the production build specific to the user.
-   `users`: contains the user authentication code, including the login (`login.html`), logout (`logout.html`), and registration (`register.html`).
-   `.gitignore`: specifies files and directories that Git should ignore.
-   `requirements.txt`: contains the essential packages to run the application.
-   `runtime.txt`: contains the python version, used in the creation of the application.
-   `README.md`: contains project documentation.

## Contributing

### Contributing Guidelines:

Thank you for considering contributing to our project! Here are the guidelines for contributing:

1. Each contributor must create a branch, you can use your nickname as the branch name.

2. Clone the repository to your local machine:

    ```
    git clone https://github.com/Eben-123/Learning-Log.git
    ```

3. Navigate into the project directory:

    ```
    cd Learning-Log
    ```

4. Create a new branch with your nickname and team name:

    ```
    git checkout -b nickname-team-name
    ```

5. Make the necessary changes and commit your changes:

    ```
    git add .
    git commit -m "commit message"
    ```

6. Make sure you run build:

    ```
    npm run build
    ```

7. Push your changes to your branch:

    ```
    git push origin your-branch-name
    ```

8. Create a pull request on the GitHub repository. Be sure to include a descriptive title and a detailed description of your changes.

9. Wait for a maintainer to review your changes and merge them into the develop branch.
10. PLEASE ENSURE YOU MAKE YOUR PULL REQUEST TO THE DEVELOP BRANCH, DON'T INTERACT WITH THE MASTER BRANCH.

### FIGMA LINK

[Fidelity Design](https://www.figma.com/file/mX7juDzXo4p0qdkuR0VDbL/BooksLab?type=design&node-id=157-184&t=KcvQZIkJeMPElOWT-0)

Thank you again for your contributions!
