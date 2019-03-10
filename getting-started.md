
# Get Started

> if you are really new to github and dont know the basics,
>It is a simple exercise that gets you started when learning something new. 
>Let’s get started!

**You’ll learn how to:**

 1. Clone a repository
 2. Start and manage a new branch
 3. Make changes to a file and push them to GitHub as commits
 4. Open and merge a pull request

 ## 1. Clone a repository
Github use  a  _remote_  repository. You can clone your repository to create a  _local_  copy on your computer and sync between the two locations.

In this exersice you will be using  [https://github.com/sivsivsree/github-repos](https://github.com/sivsivsree/github-repos), repository to clone

1.  On GitHub, navigate to the main page of the repository.
    
    **Note:**  If the repository is empty, you can manually copy the repository page's URL from your browser and skip to step four.
    
2.  Under the repository name, click  **Clone or download**.
    
    ![Clone or download button](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png)
    
3.  In the Clone with HTTPs section, click  to copy the clone URL for the repository.
    
    ![Clone URL button](https://help.github.com/assets/images/help/repository/https-url-clone.png)
    
4.  Open  Terminal.
    
5.  Change the current working directory to the location where you want the cloned directory to be made.
    
6.  Type  `git clone`, and then paste the URL you copied in Step 2.
    
    ```shell
    $ git clone https://github.com/sivsivsree/github-repos
    ```
    
7.  Press  **Enter**. Your local clone will be created.
    
    ```shell
    $ git clone https://github.com/sivsivsree/github-repos
    > Cloning into `github-repos`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.
    ```


## 2. Create a Branch

**Branching**  is the way to work on different versions of a repository at one time.

By default your repository has one branch named  `master`  which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to  `master`.

When you create a branch off the  `master`  branch, you’re making a copy, or snapshot, of  `master`  as it was at that point in time. If someone else made changes to the  `master`  branch while you were working on your branch, you could pull in those updates.

This diagram shows:

-   The  `master`  branch
-   A new branch called  `feature`  (because we’re doing ‘feature work’ on this branch)
-   The journey that  `feature`  takes before it’s merged into  `master`

![a branch](https://guides.github.com/activities/hello-world/branching.png)

> Image taken from Github.

Have you ever saved different versions of a file? Something like:

-   `file.txt`
-   `file-1.txt`
-   `file-1-finsih.txt`

Branches accomplish similar goals in GitHub repositories.


 You can create branch using the following command in the bash.
```bash
git checkout -b your_branch_name
```
