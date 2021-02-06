## How to start ? 


*If you don't have git on your machine, [install it](https://git-scm.com/downloads).*

## Creating Repository

- If you don't have your GitHub account Signup on Github it is an easy setup.
- Now, if you look around you will find a '+' Plus sign on Top Right of your github page or
- Or After doing Sign-Up go to [GitHub Home](https://github.com/), you will find a Green Box 'New', Click on it.
- Give a name to your Repository.
- Make the repository PUBLIC, if not otherwise leave it as it is.
- Un-Tick/Uncheck the "Initalize this repository with a README", if it is otherwise leave it as it is.
- Click on "Create repository"
- 
- Now [IMPORTANT] do not close the GitHub window which has opened
- Copy the HTTPS link provided from the same page of previous step


## Using GitBash to upload it on GitHub 

- Now open the folder where you have your HTML, CSS && JS file save ( Make sure that you have a seperate folder for your project otherwise it will create problem ).
```
For Example if I have my HTML, CSS and JS in E: Drive in folder name Demo then i will go inside that folder
```

- Right click and open 'Refresh' Pop-up inside that folder
- Select Bash Here option


## Inside Bash Terminal 

```
git init
```

```
git remote add origin "url you just copied"
```
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.





Add those changes to the branch you just created using the `git add` command:

```
git add .
```
Ignore the warning it shows

Now commit those changes using the `git commit` command:

```
git commit -m "(Add your message here)"
```

replacing `<Add your message here>` with your message.

## Push changes to GitHub 

Push your changes using the command `git push`:

```
git push origin master
```

Now You are done, Go and Open your GITHUB repository refresh it .


<p style="text-align: center;"> Going Dark </p>



