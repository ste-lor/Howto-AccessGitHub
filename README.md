# Howto-AccessGitHub
Quick description of how to access GitHub repositories in linux and windows.

<br />

**For Linux:**<br />
1. Make sure **git** is installed at your local machine.
````
sudo apt install git
````

2. Clone your repository at a location of your choice. In GitHub there exist different possibilties how to clone your repository: HTTPS, SSH, GitHub CLI. In this tutorial we will use HTTPS. <br /><br />
    2.1 Copy the HTTPS link of your repository
    ![PIC1](https://user-images.githubusercontent.com/67844725/199693502-2bf0d82c-1ec9-48b4-9b25-5d865125d3cf.png)
    
    2.2 Type in terminal (at location of your choice)
	````
	git clone "insert your specific link (https://github.com/...)"
	````

3. GitHub asks **for each clone-, pull- and push-request username and passwort** (the required passwort here is the so called **acess token** which has to be generated first, a detailed description on how to create this token can be found here [GitHub Access Token](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)).<br />
This can sometime be annoying. Thus, in order to **remeber your credentials, GitHub CLI** can be installed. A detailed installation description for Linux, Windows and Mac can be found here [GitHub CLI](https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git).<br /><br />

4. **GitHub Push Request:** For pushing your changes **from your local machine to your GitHub repository**, type in your terminal
````
git add .
git commit -m "title description of your changes" -m "further remarks of your changes (not necessary needed)"
git push
````
There exist a lot of possibilities to further extend the `commit` command: [git commit documentation](https://git-scm.com/docs/git-commit). <br /><br />

5. **GitHub Pull Request:** For pulling your changes **from your GitHub repository to your local machine**, type in your terminal
````
git pull
````



<br /><br /><br />




**For Windows:**<br />
1. Install **git** on your local machine. A detailed description can be found here [Git Installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).<br />

2. Clone your repository at a location of your choice. In GitHub there exist different possibilties how to clone your repository: HTTPS, SSH, GitHub CLI. In this tutorial we will use HTTPS. <br /><br />
    2.1 Copy the HTTPS link of your repository
    ![PIC1](https://user-images.githubusercontent.com/67844725/199693502-2bf0d82c-1ec9-48b4-9b25-5d865125d3cf.png)
    
    2.2 Type in terminal (at location of your choice)
	````
	git clone "insert your specific link (https://github.com/...)"
	````
	
3. **GitHub Push Request:** For pushing your changes **from your local machine to your GitHub repository**, type in your terminal
````
git add .
git commit -m "title description of your changes" -m "further remarks of your changes (not necessary needed)"
git push
````
There exist a lot of possibilities to further extend the `commit` command: [git commit documentation](https://git-scm.com/docs/git-commit). <br /><br />

4. **GitHub Pull Request:** For pulling your changes **from your GitHub repository to your local machine**, type in your terminal
````
git pull
````
