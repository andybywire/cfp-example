#Content First Prototyping Sample Project
The Content First Prototyping Framework is an open source toolkit that helps you bring real, dynamic content into your prototyping process. This repository is a sample project that demonstrates how the framework works.

If this is the first page you’ve visited about content first prototyping, be sure to also check out the [Smashing Magazine article](https://www.smashingmagazine.com/2016/05/content-first-prototyping/) that introduces the framework, or the [Content First Prototyping Starter Kit](https://github.com/andybywire/content-first-prototyping) repository. If you’re looking for a bare bones version of the framework to clone as a staring point for your own project, check out the [cfp-framework](https://github.com/andybywire/cfp-framework) repository instead.

##Green Lake Community Center 
In order to get a better sense of what content first prototyping looks like in action, this repository stages a prototype build from start to finish, using digital content collection from a real-world situation. Here’s the scenario:

> The Green Lake Community Center offers classes, programs, and events to community members in the Green Lake neighborhood. Unfortunately, all of their current class, program, and event information is only available online via PDF, which in turn is only available from the Center’s fixed-width desktop-optimized site. In an effort to reach community members who are increasingly trying to access class, program, and event information via their mobile phones, the center has decided to launch a mobile-first programs website.

Using a content first prototyping workflow, this project team created a functional mobile wireframe prototype that allows potential users navigate through and interact with actual GCC content:

![gcc-screens](https://github.com/andybywire/cfp-example/blob/master/img/gcc_screens.png)

To see the individual steps followed to build this prototype up from a clone of the [CFP Framework](https://github.com/andybywire/cfp-framework), check out this repository's [commit log](https://github.com/andybywire/cfp-example/commits/master). 

##Using the Sample Files
In order to experiment and modify this sample project on your own computer, you'll need to install the framework dependencies. First, be sure you have:

- [Command line tools](http://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/)
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (if you’re on a Mac this is probably already installed)
- [Node.js](https://nodejs.org/en/)

Once you’ve got your environment set up, install the project framework. (If you're new to the command line, open a terminal window and enter in the commands below. Leave off the "$" – that's a stand-in for the terminal prompt. If you get a permission error, type `sudo` before the line and enter your password when prompted.)

1. Install Jekyll (you may need to use `sudo` if you see permission errors)

        $ gem install jekyll

2. Clone/copy the sample project to your machine (this will take a minute or so)

        $ git clone https://github.com/andybywire/cfp-example.git

    **- or -**

    Download and copy the [.zip](https://github.com/andybywire/cfp-framework/archive/master.zip)

3. Navigate to your project file and install the framework dependencies

        $ cd <path to your project folder>

        $ npm install

4. Run `npm start`. Once installed, this is the only command you'll need to run to begin a new session.

        $ npm start

The start command will assemble your site into the `_site` folder and then serve it to your default browser. You can copy this file to another server if you like, but don't edit any of these files in this folder directly – the next time the framework runs an update, it will overwrite any chages you've made.

For more details on the CFP Framework and tips on buiding your own prototypes, check out the README instructions on the [Content First Prototyping Starter Kit](https://github.com/andybywire/content-first-prototyping) page. 

