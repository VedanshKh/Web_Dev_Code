# WEB_DEV_CODE

This repository contains web development code and files.

## Cloning the Repository

To clone this repository to your local machine, use the following steps:

1. Open a terminal or command prompt on your computer.

2. Navigate to the directory where you want to clone the repository:

    ```bash
    cd Desktop
    ```

3. Clone the repository using the following command:

    ```bash
    git clone https://github.com/VedanshKh/Web_Dev_Code
    ```

## Adding Files to the Repository

4. Change into the newly cloned repository directory:

    ```bash
    cd WEB_DEV_CODE
    ```

5. Add the files you want to include in the repository. You can add specific files:

    ```bash
    git add .
    ```

6. Commit the changes with a meaningful message:

    ```bash
    git commit -m "<your message>"
    ```

## Pushing Changes to GitHub

7. Push the changes to the GitHub repository:

    ```bash
    git push origin main
    ```

   If you are working with a different branch, replace `main` with your branch name.

That's it! Your changes should now be reflected in the GitHub repository.

## Fetching Updates from the Remote Repository

If there are updates to the repository that you want to incorporate into your local copy, you can use the following steps:

1. Open a terminal or command prompt on your computer.

2. Navigate to the repository directory:

    ```bash
    cd Desktop/WEB_DEV_CODE
    ```

3. Fetch the latest changes from the remote repository:

    ```bash
    git fetch
    ```

4. Merge the fetched changes into your local branch:

    ```bash
    git merge origin/main
    ```

   Replace `main` with your branch name if you are working with a different branch.

Alternatively, you can combine fetching and merging into a single command:

   ```bash
   git pull origin main
