

# Scientific Programming: Practical 2 - Group 4


## Command Glossary

* Clone repository into the system
````
git clone https://github.com/CreatorUser/Repository.git
````

* Create branch
````
git branch collaborator_xxx
````

* Move to branch
```
git checkout collaborator_xxx
````

* Create and move to branch
````
git checkout -b collaborator_xxx
````

* Add ALL file contents to the index
````
git add .
````

* Record changes to the repository adding a comment
````
git commit -m "Adding my new branch with todays story"
````

* Upload changes to the branch
````
git push origin collaborator_xxx
````


## Member commands and log :dizzy:


### Gerard Font

* Cloning the repository
````
git clone git@github.com:JoelMoro/SP_g4.git
````

**Creation of branch and .txt file**

````
git checkout -b collaborator_gerard
vi collaboratorgerard_story.txt
````

**Pushing the changes to my branch to personal story**

````
git add .

git commit -m "Pushing to my collaborator branch my personal story"

git push origin collaborator_gerard
````

** Pushing the changes to my branch regarding  the collaborator story and readme**
````
vi collaboratorgerard_story.txt

git add .

git commit -m "Adding some actions for afternoon and evening as expected in the task"

git push origin collaborator_gerard

vi README.md

git add .

git commit -m "Adding the commands used to the README.md"

git push origin collaborator_gerard

````

### Julen Berrueta 

**Creation of branch and .txt file**

````
git branch collaborator_julen
git checkout collaborator_julen
nano collaboratorjulen_story.txt
````

**Doing the first commit to my branch**

````
git add .
git commit -m "Adding my new branch with todays story"
git push origin collaborator_julen
````

**Creating newstory.txt and doing the second merge to my branch**

````
cp collaboratorjulen_story.txt newstory.txt
git add .
git commit -m "Updating README and adding newstory.txt"
git push origin collaborator_julen
````


### Joel Moro

* Creation and writing of the story
````
 touch collaboratorjoel_story.txt 
 vim collaboratorjoel_story.txt - Writting story 
````

* Creating the branch and pushing the changes  

````
git checkout -b collaborator_joel 
git add . 
git commit -m "Pushing to my collaborator branch my personal story" 
git push origin collaborator_joel 

````
* Concatenate our personal story to the group story file called newstory.txt

````
cat newstory.txt collaboratorjoel_story.txt > newstory2.txt
rm newstory.txt
mv newstory2.txt newstory.txt
git add .
git -m commit "Adding my personal story to newstory.txt"
git commit -m "Adding my personal story to newstory.txt"
git push origin collaborator_joel
````

### Group Commands

* Accepting the merges of the three different branches and resolving the conflicts throught the process
* Modify README.md with the report specifications

