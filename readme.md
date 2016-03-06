# This build is still in progress

# Mapper

![mapper demo](readmeAttachments/mapperdemo.gif)

This is a demo file I'm using to prototype the interaction between a vue.js app and a google map instance.

## Prerequisites

To launch this project you'll need [Node.js](https://nodejs.org/en/download/) installed. This will install both Node and npm.

You will also need to generate your own google maps API key.

Once you have your key, you'll need to add it to the `map.vue` component. I'll add more detail on how and where later.

 
## Install and Launch

To get this project up and running:

- Clone the repo to your computer, open a terminal, and `cd` into the root:

	    cd ~/Desktop
	    git clone https://github.com/chris-schmitz/Mapper.git Mapper
	    cd VueToDos

- Install the project dependencies using `npm` (installed when you install node):

	    npm install

- Start the default task in `gulp` (installed when you run npm install):

    	./node_modules/.bin/gulp

- In your terminal you should see the url for the server that this project starts:

	![mapper launched](readmeAttachments/MapperLaunched.png)
