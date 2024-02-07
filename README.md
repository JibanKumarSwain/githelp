# githelp


1--.Initialize a Git repository: In the directory where you want to store your file, open Git Bash and 
type the following command to initialize a new Git repository:


$ git init



2--.Add the file to the repository: Use the following 
command to add the file you want to upload to the repository:

$ git add <file_name>


$ git status "if colour is green it is good" 




3--.Commit the changes: Use the following command to 
commit the changes and add a message describing the changes:


$ git commit -m "Initial commit"
$ git commit -M main/master  (we can choose to what we use main / master)



4--.Connect to a remote repository: If you want to upload your
 file to a remote repository, such as GitHub, you'll need to 
connect your local repository to the remote repository. 
To do this, use the following command:



$ git remote add origin <remote_repository_URL>



5--.Push the changes: Use the following command to push
the changes to the remote repository:


$ git push origin master




This is the basic process for uploading a file using Git Bash. More advanced scenarios and additional options are available, so it's recommended to read the Git documentation for a more complete understanding of how Git works.
