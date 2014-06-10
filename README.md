# Sandbox

Place to test git workflow

## Git Workflow

1. Clone repository from sandbox repo

    ```bash    
    # change into your local projects directory (in your own computer) 
    cd ~/projects
    # clone the sandbox repository
    git clone https://github.com/ippc/sandbox.git
    ```

2. Change to sandbox directory and open the directory with your text editor (in this case, mate == textmate editor)  

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
    
