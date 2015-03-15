# Blockly

Google's Blockly is a web-based, visual programming editor.  Users can drag
blocks together to build programs.  All code is free and open source.

**The project page is https://developers.google.com/blockly/**

![](https://developers.google.com/blockly/sample.png)

## Getting started

If you want to make changes to your local copy of Blockly we recommend you [Fork](https://help.github.com/articles/fork-a-repo/) this repository. If you just want to have Blockly running on your machine, the following instructions will get you up and running in no time:

1) Create a folder to contain all the code needed and move into it:

    mkdir blockly_sources
    cd blockly_sources
    
2) Clone the Blockly repository:

    git clone git@github.com:google/blockly.git
    
3) Clone the Google Closure repository:

    git clone git@github.com:google/closure-library.git

4) Open blockly/demos/index.html. You can do this manually from your file explorer, or from terminal if you are using a mac with:

    open blockly/demos/index.html
