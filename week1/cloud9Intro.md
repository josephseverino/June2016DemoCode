Cloud9 Introduction
================

Purpose
---------

The purpose of this lecture is to introduce students to cloud9, so that they can use basic BASH commands in their workspace to navigate around, edit files, and serve html pages. 


Lecture Notes
---------


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

setup
-----------------

- register for a free cloud9 account

- click on 'repositories' section
    - link your github account with your c9 account

- click on 'workspaces' section
    - click 'create a new workspace'
        - The owner is you.
    - choose any workspace name you like (e.g. bestWorkspaceEver)
    - choose any description you like (e.g. this is where I work!)
    - choose 'hosted workspace'
    - choose 'private' (you can only have one private workspace. think of it as your personal development computer)
    - omit the git url
    - choose the 'custom' template
    - create workspace
    
```Totally messed up your workspace? No big deal, just delete it and recreate it. You're only limited to one private workspace AT A TIME. Any work you've done that is important should always be pushed to github.```


- open your new private workspace
    - click the 'share' button in the top right corner. 
    - share your workspace with the instructors (raphael.serota@gmail.com, robert.camp@outlook.com)
    - this will allow the instructors to check in on your progress. 
    
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-==-=-=

usage
-----------------------

You'll develop in cloud9 using multiple tabs.

We start with one TERMINAL TAB. To make more, click the + button, and select 'New Terminal'
In a terminal tab, you have full command-line access to your virtual machine. It's just a BASH environment, like the codeCademy command-line course.

```Cloud9 provides a special command we can use to open files: `c9 README.me` will open the readme.```

This creates a second type of tab, a `FILE EDITOR TAB`. This editor is extremely simple, but also has lots of shortcuts if you want to be a 'power-user'.  I recommend `sublime mode`.
You can also open an entire folder: `c9 .` This will add that folder to your 'favorites' on the left sidebar. This is very useful for looking at related files within the same project. 


Lets make a hello world page.
- `touch index.html`
- `c9 index.html`
<code>&lt;h1&gt;Hello World&lt;/h1&gt;</code>

Right click in the editor, or the file browser, or at the top bar, click "Run". 
This will start apache, which will serve your html file. Navigate to the URL provided, and see your site on the internet! 

=-=-=-=--=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
