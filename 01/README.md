# How to Use package.json, the Core of Any Node.js Project or npm Package

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="backend">
        <p>Working on these challenges will involve you writing your code using one of the following methods:</p>
        <ul>
            <li>Clone this GitHub repo and complete these challenges locally.</li>
            <li>Use our Replit starter project to complete these challenges.</li>
            <li>Use a site builder of your choice to complete the project. Be sure to incorporate all the files from our GitHub repo.</li>
        </ul>
        <p>If you use Replit, follow these steps to set up the project:</p>
        <ul>
            <li>Start by importing the project on Replit.</li>
            <li>Next, you will see a .replit window.</li>
            <li>Select Use run command and click the Done button.</li>
        </ul>
        <p>When you are done, make sure a working demo of your project is hosted somewhere public. Then submit the URL to it in the Solution Link field.
        The package.json file is the center of any Node.js project or npm package. It stores information about your project, similar to how the head section of an HTML document describes the content of a webpage. It consists of a single JSON object where information is stored in key-value pairs. There are only two required fields; name and version, but it’s good practice to provide additional information about your project that could be useful to future users or maintainers.
        If you look at the file tree of your project, you will find the package.json file on the top level of the tree. This is the file that you will be improving in the next couple of challenges.
        One of the most common pieces of information in this file is the author field. It specifies who created the project, and can consist of a string or an object with contact or other details. An object is recommended for bigger projects, but a simple string like the following example will do for this project</p>
        "author": "Jane Doe",
        <p>
            Add your name as the author of the project in the package.json file.

Note: Remember that you’re writing JSON, so all field names must use double-quotes (") and be separated with a comma (,).
        </p>
        <a href="https://replit.com/@Angelique09/boilerplate-npm">Replit Solution</a>
        <a href="https://boilerplate-npm.angelique09.repl.co">Web Solution (from Replit)</a>
    </div>
</body>
</html>
