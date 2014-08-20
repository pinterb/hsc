# HSC

HSC (Hack Some Code) is an opinionated command line utility designed to get you writing code....quickly!

## Why?
If you are new to software development, the whole process of choosing a lanuage, framework, design pattern, tooling, etc. can seem daunting.  Solving that problem or implementing that new idea quickly becomes unapproachable.

And even if you're an experienced engineer, do you really want to spend an hour writing boilerplate before you can implement that proof-of-concept?

## Usage

**init**: First time installing HSC

**new**: Create a new project

**fork**: Collaborate on an existing project

**issues**: Manage project ideas, features, stories, and bugs

**info**: Display version of your local HSC install

**check**: Check for available updates for HSC

**download**: Updates to latest HSC version

**help**: Show this help

### In Depth
Let's explore each of the sub-commands.   

#### Init
This sub-command initializes a user's local installation with necessary configuration to streamline processing.  Storing a configuation locally will also eliminate the need to query for input that may be redundant across sub-commands.  GitHub repository information would be one example of the type of data that may be redundant across sub-commands.

#### New
This sub-command creates a new project for a user.  The user would be able to select from a list of pre-defined starter projects ideally implemented in multiple languages.  A good example would be the customary "hello world" application implemented as a [microservice](http://martinfowler.com/articles/microservices.html).

#### Fork
If you find an existing project you'd like to contribute to, this is the sub-command for you.  

#### Issues
If you have a bug, enhancement, feature, etc. that you want to create for an existing project and don't feel like going to GitHub.  Additionally, this sub-command will allow you to "import" feature files as issues in GitHub. 

#### Info
Display version of your local HSC install.  This includes both the semantic version number as well as Git information.

#### Check
Automagically checks the ether for a new version of this utility.

#### Download
Updates to latest HSC version.

#### Help
Display some help message.
