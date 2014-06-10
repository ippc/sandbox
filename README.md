# Sandbox

Place to test git workflow

## Git Workflow

1. Clone repository from sandbox repo

    :::bash    
    # change into your local projects directory (in your own computer) 
    cd ~/projects
    # clone the sandbox repository
    git clone https://github.com/ippc/sandbox.git

2. Change to sandbox directory and open the directory with your text editor (in this case, mate == textmate editor)  

    :::bash    
    cd sandbox && mate .

3. Create a new branch called 'newfeature' and switch to it

    :::bash    
    git checkout -b newfeature
    
4. Create a new file for this new feature and add some text to it

    :::bash    
    echo 'a text file!' >> newfile.txt

5. At end of day or more often as you prefer, commit the changes to this branch

    :::bash    
    git add .
    git commit -m 'new feature'

6. Push your branch to main repo at end of day (or more often)

    :::bash
    git push origin newfeature
    
