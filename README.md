# Chat-App
basic chat app over local host

HTML, CSS3, Javascript, Node.js, Express, Socket.io


Steps to run terminal (with the assumption Node.js is already installed on your computer)

- Open up the Terminal app on MacOS or cmd.exe on Windows to get to a command prompt.

You are needed to change the working directory to the location where you have saved this project file.
For me, I saved this project on my desktop inside a "Chat" folder for this example:

cd desktop
cd chat

- We need to make sure our folder is set up to work with other libraries. With this project, we will be using Express. Initialize your folder by typing in the following
command line:

npm init -y

- When this runs, you will notice a new file 'package.json' in your folder. We need to install and save the Express library into our project by running this command from the command line that we have open:

npm install express

- Next step is to install another 3rd party Node module called Socket.io.

Run the following command in the terminal window to install it on the server:

npm install socket.io

- Make sure all your files are saved, and the Node server is still running. Now we can start useing the Chat App by visiting this local host:
http://localhost:8080

Voila!

