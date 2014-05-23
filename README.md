Official stupIT by-laws
==============

## Intention
*stupIT by-laws* is a repository created to support the collaborative work of adopting
ammendments, where individual changes can be merged into one canoncial copy of the text.

Use of GitHub will make it easier to keep track of proposed ammendments and merge them with
the official branch if they are voted for on the general assembly.

## Usage
When creating a proposal for an ammendment just clone the repository to your own computer,
branch out and make the changes in the branch. Please provide an explanatory name for
the branch and a description of the committed changes. When you are satisfied with the result
you will make a pull-request, and the changes can be discussed and eventually merged into the official version.

### How to make a suggestopm for a change
1. **Fork the repository**

    First thing to do is to create your own fork. Press the *Fork* button in the top
     of the page. You will now have a repository of your own. Your fork can be found on
     ```https://github.itu.dk/[LOGIN]/stupIT_by-laws.git```
     
1. **Clone the repository to your local drive**

    Before you can start working on the changes, you will have to have them locally on your computer.
    Open a terminal window (or Command prompt) and navigate to the directory where you will keep your copy.
    Once you are in place, run this code:
    ```bash
    # Clone this repository to your local drive
    $ git clone https://github.itu.dk/stupIT/stupIT_by-laws.git
    ```

1. **Branch out**

    If you are suggesting changes that will have to be enacted by the general assembly,
    then it is helpful to create a new branch with your changes. This way, we may
    have a vote and then *merge* the branch if necessary.
    ```bash
    # Make a new local branch with an explanatory name
    $ git checkout -b "proposal-morten" 	# You may use your own name ;)
    ```

1. **Make your changes to stupIT_by-laws.tex**
    
    Anybody can make changes to the by-laws using just a text editor. 
    Open the stupIT_by-laws.tex file with your prefered editor and make the desired changes.
    Because the bylaws are written in LaTeX and then compiled into the pdf, you will need 
    a LaTeX editor in order to **compile the pdf**. You can make the changes to .tex file and 
    the follow the remaining steps, then ask someone else to compile it for you.

1. **Commit your changes**

    *to be updated...*

1. **Make a pull-request**

    *to be updated...*
    