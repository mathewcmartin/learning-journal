
<h1># LJ Code 201 - Day 1</h1>
//
Codefellows 201 Journal
Mathew C. Martin

3/6/2017

Meet with Brandi the Codefellows Seattle Campus manager and Nick our 201 instructor. We covered new the title of "Software Developer".

-We studied "Emotional Intelligence & Self Awareness" and their importance in finding and keeping a job as well as during my study at Codefellows.

-Friday we meet with industry folks and need to bring a lunch.

-Some Slack groups I might be interested in #military-vets-or-cf  #seattle-201d20  #alumni  #jobs

-Nest Camera Recordings are available of course work for classes.

-Garage Code: 2909   Men room: 5218*

-Upcoming Holidays Memorial Day, Independence Day

-Immersive learning is the modus operandi at Codefellows.

-Employers value EI or IQ.
    -Calm under pressure
    -Resolve conflict directly
    -Are empathetic to their colleagues and act as such
    -Lead by example
    -May put more consideration into business

-Unix Commands
    $ atom .bash_profile
    $ cd ~
    $ atom .bashrc
    $ source .bashrc

-Updated bashrc file with Slack 201 code for today from Nick which updated and modified my bashrc file in my home dir.

    $ ls -a
    $ tree      Current dir contents
    $ pwd       Gives path to working directory
    $ cd        Change dir

-ls -a outputs a listing of all the dir contents while ls -lha includes hidden files

    $ cd ~             Changes dir to the root dir
    $ cd ..            Changes dir up one level in the tree
    $ mdkir name       Creates dir
          Ex: mkdir code-demo code-demo/foo
    $ touch filename   Creates filename
    $ which            Determine where shell command exists
    $ mv               Use move to change filename or move to a new location
          Ex: $ mv mashed ../    //moves mashed up one directory
    $ less example \ file\ 1     //Used to remove spaces in win file names
    $ rm path\filename           //Remove Command
    $ rmdir                      //Remove directory
    $ rm -rf                     //Kills directory
    $ cp                         //Copy Command
          Ex: $ cp mashed code-demo/
    $ history                   //Every command used during session
    $ clear
    $ history | grep git        //Pull every cmd w/git
    $ man                       //Displays manual
    $ q                         //To end history
          Ex: $ mkdir html js css
    $ touch html

git: developed by Linus Torvalds is a version control system

-git snapshots are called commits

    $ git status
    $ git add index.html
    $ git add .                 //Adds everything in dir
    $ git commit -m "this is my first msg"

//* vs + in the git prompt indicates committed changes versus changes out of sync between the origin and master. (Add, Commit, Push)

    $ git push origin master

//google ohshitgit

-Codefellows homework will be distributed thru git.

-Remote Repository

    $ git remove -v
    $ git checkout -b class-a       // -b indicates a new branch
    $ git checkout master
    $ git checkout class-1
    $ git status

//Syntax:  git push <origin> <repository>

-Pull Request
    $ git commit -m                 // adds msg

//git > graphs > network    shows graphical interpretation of a git Repository

-Added eslinter package to git.

-html
    -Tags <element>
        Ex: <p> </p>

        <p lang = "en-us">

//Added atom package emmett

        <!DOCTYPE>
        <p class>
        <div>
        <section>
        <article>
        <span>
        <aside>
        <iFrame>
        <meta>
        <figure>
        <a> </a>                    //Anchor Tags
        <a href = "#"> </a>

Chapter 18 HTML Book:

        -wireframe
            site structure
        -calls to action

Javascript:
        var =
        alert
        prompt
        confirm
        var = user input
        var = user bool

Homework:
        1. Use prompt command to ask four questions and alert to answer the prompt using user input then combine all four answers into the final output (alert). Use an index.html file and app.js files to create the code and include 'use strict' in the .js file.

        2. Create a learning journal .md file (markdown journal)

  3/7/2017
