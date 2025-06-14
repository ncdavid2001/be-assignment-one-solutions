# BE Week One Assignment Solutions
Node.js is a JavaScript environment that allows developers to run JavaScript on the sever-side, outside of the web browser and handle multiple projects efficiently.

Node.js differ from other server technologies because it allows developers to single language like JavaScript to code for front-end and back-end

It uses event-driven, non-blocking I/O models which make efficient in handling multiple requests at a time.

Node.js is lightweight, scalable making it suitable for real time applications and microservices

relationship between Node.js and V8 engine; one V8 engine compile, optimize and execute JavaScript code also Node.js uses V8 engine to execute JavaScript code on server side
a.	Fast and scalable
b.	Event-driven and non-blocking
c.	JavaScript can run but in back-end and front-end
d.	JavaScript has many packages and modules 
e.	Flexible and suitable for microservices and modern web development

Node.js handles multiple concurrent connection using Event-driven architecture, non-blocking it doesn’t wait for I/O operations to complete, instead it continues processing other requests and it will call it back to handle it when it ready.

Non-blocking means that Node.js don’t wait for I/O operations to complete, instead it continues executing other task and handles I/O operations response when it’s ready.

Node.js listens for specific events, e.g. completed or incoming task and it triggers callback function to handle events. This make Node.js very efficient in handling multiple tasks at a time and also give room to other processing task in the background

Conceptual questions
NPM is a package manage for Node.js that allows developers to easily install, manage (manages dependencies between packages, ensuring that projects have the required libraries) and share reuseable code packages.

It considered cross-platform because it can run on different operating system like Windows, macOS andLinus and the benefits are flexibility, portability and broader reach.
They are:
File system operations(fs), Http request(http), path manipulation(path) and URL parsing (URL) and the benefit convenience, reliability and core functionality.

Class Two - Version Control
Git is different from other version control system because it distributed or decentralize system because others are centralized.

The purpose of repository helps to locate and store files, track changes, manage versions and collaborate with others.

Git tracks changes by Snapshotting of the codebase at different point in time, commits changes in a meaningful message and it store histories

Branching in Git helps a developer to work features independently, running a code without affecting the main code and collaboration with others.

The different between merging and rebasing is merging is combining changes from one branch into another without preserving commit history while rebasing is clean, linear commit history and are working on a feature branch.

Merging conflict occur when git can’t automatically merge changes from two branches or changes made in the same file or line. 

Conflict resolution step in git: Identify the conflict, manually resolve and commit resolution.

Collaborative Workflow
The purpose of creating pull request is to allow the developers to review and approve changes before merging them into the main codebase.

The process of creating pull request is first create a branch, make changes, commit and push, then open a pull request on the repository’s platform.
The different between forking and cloning is that forking is creating a copy of a new repository in your account, allowing you to make changes without affecting the original works while cloning is copying a repository in your system, allowing you to work on the code.

Git collaborates with other developers by creating branching, commit and push and pull request.
When to use Git stash when a developer wants to temporally save a change in working directory and also when to switch or work on something without committing changes.

Git tags mark a specific commit as important and use git tag command to create a lightweight or annotated tag.
How to manage a remote is first adding remotes and linking it to the remote repository, then pushing and pulling to share changes with the remote repository.

Discussion Questions

Node.js
Node.js single thread Nature increases the performance of O/P-bound tasks, but may struggle with CPU-intensive tasks also scalability is another tool that makes it easier to add more resources as needed

The advantages of using event-driven architecture are efficient handling of concurrent connections and scalability and the disadvantages is the complexity and nested callbacks lead to code complexity

Node.js non-blocking I/O model benefit we application benefit by allowing Node.js to handle multiple requests concurrently, improving performance and responsiveness. And the advantage for web application it makes it suitable for real-time web applications, such as chat apps, live updates, and streaming services.
Version Control

Version control is important for tracking changes, collaboration and error recovery.
Version control help in team collaborating by concurrent work, change tracking and code review.
Best practices for organizing a git repository:
1.	Clear commit messages
2.	Branching strategy
3.	Consistent naming
4.	Regular commit

Combined Concepts
The Relationship between Node.js and version control system control development is first code management (code changes, collaboration and version) and tracking dependency.

Version control system helping in managing Node.js dependencies by initialize Git, create a. gitignore file and the use npm init: create a package. Json file to manage dependencies.

version control help in managing Node.js dependencies by track package. Json changes: version control track changes to dependencies and version.
Reproduce environments: version control ensures consist dependencies across environment 
