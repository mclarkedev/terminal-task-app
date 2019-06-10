# terminal-task-app
A notes app that runs on your terminal/command line using Node.js

Using your terminal or command line program, with Node.js already installed, you can use this tool to add and remove notes with a title and body.
You can also list out all of your notes and read individual notes.

This tool creates a JSON file on your drive that stores these notes. 

Commands/Arguments:
node app.js

Add a note:
add --title="<note title here>" --body"<note body here>"

Remove a note:
remove --title="<note title>"

List notes:
list

Read individual note:
read --title="<note title>"

