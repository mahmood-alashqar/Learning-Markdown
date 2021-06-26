# NODE.JS  

## An Introduction to Node.js  

### What Is Node.js?  

To define **Node.js** we have to mention **The V8 engine**.  

**The V8 engine** is a performance in mind and open source compiler, that compiles `JavaScript` on native machine and works with every **Chromium-based web browser**, this include Google Chrome, Brave, Opera, and Vivaldi.  

**Node.js** is a software or program that is used to execute `JavaScript` on our computers. The **Node.js** took **the V8 engin** and enhanced it with various features, such as a file system API, an HTTP library, and a number of operating system–related utility methods.  

-------------------

- There are two method to install **Node.js** at your system:
    1. go to **Node.js** official web-site and choose your system and download it [Node.js Official Web-Site](https://nodejs.org/en/download/)
    1. Install it using `npm` or a Node Package Manager [npm install method](https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/)  

- There are some advantages using the second method like:
    - it negates potential permission issues when using Node with npm.
    - it lets you set a Node version on a per-project basis.

- To know what is the current **node** version at your system, type `node -v` or `node --version` at your terminal, for example mine is `v12.21.0`  

- To run a `JavaScript` code using **Node.js**, type at you terminal `node name-of-your-file.js`. 

- One advantages of running **Node.js**, that you don't have to worry about the compatibility of your code with the browser, since **Node.js** has excellent support for ECMAScript (**JavaScript**) 2015 (ES6) and beyond.  

### npm  

**npm** is another software/program, but this is the the world’s largest software registry. Through **npm**, which stands for (Node Package Manager), you can download many **JavaScript** codes.  

- For example to download **jshint** package globally on your system, type at your terminal the following code `npm install -g jshint`  

- To install a package at a certain folder. First, create and auto-populate a `package.json` file in the same folder by typing at your terminal, while ine directory of the folder this code: `npm init -y`. Then type this code to install for example **lodash** package: `npm install lodash --save`.  

### What Is Node.js Used For?  

One use is installing and running various build tools — designed to automate the process of developing a modern JavaScript application.  

Bu the biggest use is, that **Node.js** Lets Us Run JavaScript on the Server.  

In more details, when the server face an event it spawn a new thread to handle the event. However, if it face an **I/O** operation, it wil stop and handle the blocking I/O operations and then comes back to the event to start processing it. And if a new event happen then a new thread will be spawned. This can cause a site to fall down.

**Node.js** make the live of a server much easier, like when blocking I/O operation happens, it will register a callback before continuing to process the next event. Then when th server finish from the blocking I/O operation the callback function is called so the server can continue to work on it.  

Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections.  

- Also, **Node.js** even has a built-in module to help you implement a cloning strategy on a single server.

 
  
### Are There Any Downsides?  

There some cons to **Node.js** like:  
- blocking I/O calls should be avoided.
-  CPU-intensive operations should be handed off to a worker thread.
-  errors should always be handled correctly for fear of crashing the entire process.  


### What Kind of Apps Is Node.js Suited To?  

Real Time Applications, is the answer. For example, chat sites, building APIs where you’re handling lots of requests that are I/O driven, or for sites involving data streaming.  

### What Are the Advantages of Node.js?

1. speed and scalability.
1. do everything in the same language.
1. it speaks **JSON**.
1. transitioning to Node development is, because JavaScript is popular.

### Other Uses of Node

- For example it can be used as a scripting language to automate repetitive or error prone tasks on your PC. It can also be used to write your own command line tool, such as this Yeoman-Style generator to scaffold out new projects.

- Node.js can also can be used to build cross-platform desktop apps and even to create your own robots.



## 6 Reasons for Pair Programming  

**pair programming** is the practice of two developers sharing a single workstation to interactively tackle a coding task together, and is one way we foster a collaborative environment while developing key industry skills.  

### How does pair programming work?  

There are to role in pair programming, the **Driver** who's mission to type the code, with all of its technicality , and is the only one doing the typing. And the other role is the **Navigator**, who's mission to guid the driver and think about the big picture and what is next, the navigator might also read documentations and do researches.  

### What are the 6 reasons for pair programming?

1. Greater efficiency: while pair programming might take slightly more time, it does not need that much time of recoding to fix bugs, and its quality is more higher. So it's more efficient.

1. Engaged collaboration: focus levels are higher in pair programming and procrastinating is way less. Also, finding solutions for problems is easier and consume less time.  

1. Learning from fellow students: every developer has special skills and techniques, and with pair programming two people can share their skills and methods and learn new tings. Also, experience students can help less experience ones.  

1. Social skills: communication is a key factor in pair programming and by this, developer can enhance their communication skills while working building quality applications.

1. Job interview readiness: many companies expose their applicant to pair programming while in an interview, to see how they fit in their teams. So this will help you secure a position in the future.

1. Work environment readiness: Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.

