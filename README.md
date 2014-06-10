# Sandbox

Place to test git workflow

## Git Workflow

1. Clone repository from sandbox repo (the first time you start working with it)

    ```bash    
    # change into your local projects directory (in your own computer) 
    cd ~/projects
    # clone the sandbox repository
    git clone https://github.com/ippc/sandbox.git
    ```

2. In the future, before beginning the day's work, pull the latest changes from the online repo

   ```bash
   git pull

3. Change to sandbox directory and open the directory with your text editor (in this case, mate == textmate editor)  

    ```bash    
    cd sandbox && mate .
    ```

3. At end of day or more often as you prefer, add your changes to your local staging area and commit them to your local repo

    ```bash    
    git add .
    git commit -m 'new work'
    ```

4. Push your changes to main server at end of day (or more often)


    ```bash
    git push origin master
    ```
    
### Branchinch

1. Create a new branch called 'newfeature' and switch to it

    ```bash    
    git checkout -b newfeature
    ````
    
2. Create a new file for this new feature and add some text to it

    ```bash    
    echo 'a text file!' >> newfile.txt
    ````

3. At end of day or more often as you prefer, commit the changes to this branch

    ```bash    
    git add .
    git commit -m 'new feature'
    ````

4. Push your branch to main repo at end of day (or more often)

    ```bash    
    git push origin newfeature
    ````
