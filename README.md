# Deployment Plan

## Local Environment

## Step 1
#### Create an Empty Repository

>1. log into github.com and select new Repo ( Creates new empty Repository)
>2. Give the Repo a name

## Step 2
#### Clone the Repo you created in a folder on your computer
>1. Select the Repo you created
>2. On the bottom right of your screen there is a button that reads **Clone in Desktop**
there should be a Download ZIP button below it.
>3. Once you select that button, it will let you select where you want to save that folder to be saved.

## Step 3
#### Use Terminal to create your files and Directories
>1. Type in cd to see what directory your currently in
>2. Type in ls to see the lists in that directory
>3. Type in cd nameofdirectory to go into the repository folder you created.
>4. Type in ls to see whats inside.
>5. Type in mkdir to create a new directory(Folder) in your repo, so it would look like this mkdir siteName (this is saying create a new folder called siteName)
>6. Make sure to view your directories by typing in **ls** (Double check you have created and uploaded all the files you need)

## Add to Github


## Commit
#### Relevant detailed commit message
##### make change to file
> 1. git add -A
> 2. git commit -q -m “some note about your push” (Make sure to use the proper “Quotations Marks”)
##### go see site on IPAddress (stage) 
> 3. git push stageServer
##### go see site on IPAddress (prod)
> 4. git push prodSever
##### go see site on IPAddress (Github)
> 5. git push mddhub
