# CMPG-323-Overview-33572798
This is my overview repository for all my CMPG 323 projects. 

## Branching Strategies
My branching strategy for all my CMPG 323 projects is Trunk based development. Trunk based development is a strategy whereby the developer(s) merge changes directly to the main branch(trunk).By changes I am referring to small frequent updates. This practice promotes continuous development.
<a href = "https://trunkbaseddevelopment.com/">Read more<a/> about  Trunk based development

See below the diagram representation of the approach.
<img src="trunk-based-development.png" width="500" title="Trunk based development">


## Project and Repository Structure
Every CMPG 323 project will have its own repository. However all the repositories will share a Github project. 
That means I will have five repositories for five CMPG projects with one Github project. This will help me to have clean repositories. Furthermore, it will help me with separating submissions.
<br>See the diagram below for structural representation.

  
<img src="repos-structure.png" width="500" title="Trunk based development">
  
  
## gitignore file
It is/will not be the case whereby I push everything that is on my local machine to github.
There will be a lot of files that I would not want to push to github. For example, I will not push .log files. To achieve that I will use the gitignore file. The gitignore file will allow me to specify files that I want to ignore when pushing everything to github.  
  
## Credentials Storage
For secure credential storage I will make use of environment variables and of course the gitignore file.
I will have a .env file - a file for environment variables. This will allow me to use variables in my code and not credentials as they are. With the use of gitignore I will ignore the .env file which has my credentials.

Links to resources:
<a href = “https://www.optimizely.com/optimization-glossary/trunk-based-development/”>Trunk based development<a/>
<a href = “#”><a/>
<a href = “#”><a/>
