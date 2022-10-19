# Scientific Programming: Practical 2 - Group 4

## Member commands and log :dizzy:

### Julen Berrueta 

- git branch collaborator_julen

- git checkout collaborator_julen

- nano collaboratorjulen_story.txt

- git add .

- git commit -m "Adding my new branch with todays story"

- git push origin collaborator_julen

- cp collaboratorjulen_story.txt newstory.txt

- git add .

- git commit -m "Updating README and adding newstory.txt"

- git push origin collaborator_julen

### Joel Moro

* Creation and writing of the story
````
 touch collaboratorjoel_story.txt 
 vim collaboratorjoel_story.txt - Writting story 
````

* Creating the branch and pushing the changes  

````
 * git checkout -b collaborator_joel 
 * git add . 
 * git commit -m "Pushing to my collaborator branch my personal story" 
 * git push origin collaborator_joel 

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
