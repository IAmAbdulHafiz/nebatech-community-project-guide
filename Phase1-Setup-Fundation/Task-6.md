## Dear Engineers, Developers & Innovators,

Great job so far on cloning your repositories to your local machines, you are doing amazing!

### Task 6 (Phase 1 Continued – Working Locally & Syncing with GitHub):
Let’s now take the next steps to build momentum:

1. Edit Your Files Locally
Using VS Code:
•	Open the cloned project folder in VS Code.
•	Create a new file named: login.html
•	Inside login.html, create a basic login form with:

<!DOCTYPE html>
<html lang="en">
	<head>
             <meta charset="UTF-8">
            <title>Login</title>
            <link rel="stylesheet" href="style.css">
	</head>
<body>
  	<form>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required><br><br>
                <button type="submit">Login</button>
       <form>
</body>
</html>

•	Next, create a new file named style.css in the same directory.
•	In both index.html and login.html, link the CSS file by adding this in the <head>:

<link rel="stylesheet" href="style.css">

Basic CSS sample to use: 

body {
  font-family: Arial, sans-serif;
  margin: 40px;
  background-color: #f4f4f4;
}
form {
  background-color: #fff;
  padding: 20px;
  border-radius: 6px;
  max-width: 400px;
}

2. Commit and Push Changes Using GitHub Desktop
•	Open GitHub Desktop.
•	You should see login.html and style.css listed under “Changes”.
•	At the bottom, write a clear commit message, e.g.,
"Added login.html and style.css files"
•	Click “Commit to main”.
•	Then click “Push origin” to upload your changes to GitHub.

Why This Matters
This is a real-world developer workflow — editing, saving, committing, and syncing your code with your team. Mastering this will prepare you for collaborative development and professional Git workflows.