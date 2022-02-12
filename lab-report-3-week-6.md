# Lab Report 3
## Setup Github Access from ieng6 
- public key stored on Github
![githubkey](/Image/githubkey.png)
    - Adding the `id_rsa_github.pub` key content generated on my ieng6 account to github by go to **settings** -> **SSH and GPG keys** and click on **New SSH key**. 
- public key in my ieng6 user account 
![ieng6 key](/Image/ieng6key.png)
    - Using `ssh-keygen` to generate public and private keys on my ieng6 account, storing the keys at */home/linux/ieng6/cs15lwi22ajd/.ssh/id_rsa_github*
    - Then the "public key has been saved..." 

- private key you made stored on my ieng6 account *id_rsa_github* in *.ssh*
![private key](/Image/privatekey_onieng6.png)
     - By using `ls` command to show that all of they keys stored in *.ssh*, seeing that the **id_rsa_github** private key is stored in it 

- running `git` commands to commit and push a change to Github while logged into your ieng6 account 
![git commands](/Image/git_commands_onieng6.png)
![push on ieng6](/Image/pushon_ieng6.png)
    - I did several edits on the *MarkdownParse.java* file on my ieng6 account by using `vi` command, and commit and push it by using `git` commands as shown. 
    - When entering password, go to github and generate a **personal access token** to push successfully 

- [a link for the resulting commit](https://github.com/LShen101/CSE15L-TheLunaMoths/commit/abb323e01820494a63c1e486ece7c182aa7d48eb)
    - After all the operations, I could see my change and commit of *MarkdownParse.java* file on my ineg6 account at the above link page. 