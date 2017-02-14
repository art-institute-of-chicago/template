![Art Institute of Chicago](aic-logo.gif)

# Name of Project
> Additional Sub-Title If Necessary

Summary of the project. This is the first thing you read when you view this 
project. This is a great place to summarize the goals or intentions of this 
project. Generally speaking, this section is optional, but is a nice way to 
get a snapshot of what this project is about.

## Installing / Getting started

A quick introduction of the minimal setup you need to get a hello world up and
running.

```shell
packagemanager install aic-project
aic-project start
aic-project some-setup-function-if-necessary
```

Here you should say what actually happens when you execute the code above.

## Developing

Here is a brief intro about what a developer must do in order to start developing
the project further:

```shell
git clone https://github.com/your/aic-project.git
cd aic-project/
packagemanager install
```

And state what happens step-by-step.

If a developer needs to copy a sample configuration file to get their local instance 
going, provide the most minimum effort needed here. More details on configuration can 
be included in a later section on [Configuration](#configuration).

### Building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### Deploying / Publishing

In case there's some step you have to take that publishes this project to a
server, here is where to state it.

```shell
packagemanager deploy aic-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## Features

What are all the bells and whistles that are significant or unique to this project?

* What's the main functionality
* What new thing does this project provide?
* What unique feature does this project include?

## Configuration

Here you should write what are all of the configurations a user can enter when
using the project, and which file each config is set if applicable.

### Configuration file path

#### Configuration 1 Name
Type: `String`  
Default: `'default value'`

State what it does and how you can use it. If needed, you can provide
an example below.

Example:
```bash
aic-project "Some other value"  # Prints "Hello World"
```

#### Configuration 2 Name
Type: `Number|Boolean`  
Default: 100

Copy-paste as many of these as you need.

## Contributing

We warmly encourage contributions to this project. We use [git-flow](https://github.com/nvie/gitflow) 
on this project. If you'd like to contribute to this project, please fork 
the repository and make your changes in a separate branch.

```bash
git clone https://github.com/you/aic-project.git .
cd aic-project
git flow start feature yourinitials-good-description-issuenumberifapplicable
# Make some changes, commit your code
git push origin yourinitials-good-description-issuenumberifapplicable
```

Then on github.com, create a Pull Request to merge your changes into our 
`develop` branch. 

This project is released with a Contributor Code of Conduct. By participating in 
this project you agree to abide by its [terms](CODE_OF_CONDUCT.md).

If there's anything else a developer needs to know (e.g. the code style
guide), you should link it here. If there's a lot of things to take into
consideration, it is common to separate this section to its own file called
`CONTRIBUTING.md` (or similar). If so, you should say that it exists here.

## Licensing

The code in this project is licensed under the GNU Affero General Public 
License Version 3.
