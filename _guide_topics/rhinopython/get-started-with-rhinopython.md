---
title: Getting Started with Rhino.Python on the Mac
description: This guide covers the basics of getting started writing Python in Rhino for Mac.
authors: ['Alain Cormier']
author_contacts: ['Alain']
apis: ['RhinoPython']
languages: ['Python']
platforms: ['Mac']
categories: ['Getting Started']
origin: http://wiki.mcneel.com/developer/python
order: 2
keywords: ['Rhino.Python', 'Python']
layout: toc-guide-page
TODO: 'needs update, adding more resource links, etc.'
---

# {{ page.title }}

{% include byline.html %}

{{ page.description }}

To get acquainted with how Python scripts can help you model in Rhino first run some of the sample scripts that are provided.

  - In the Command prompt edit box (top left by default) type the RunPythonScript command.
  - If it's the first time you run this command the dialog box that comes up will show the files in the samples directory.  If it's not then navigate to it.  It should be under:
  ```bash
  /Users/HOME/Library/Application\ Support/McNeel/Rhinoceros/Scripts/samples
  ```
  (replace HOME with your home directory name).
  - Experiment by running the various samples starting with HelloPython.py

You can open any of the sample Python scripts in a text editor to see what they look like.  From Finder navigate to the samples directory and right-click on any of the scripts and from the context menu that pops up select Open With -> TextEdit.app which is the text editor that comes with macOS.  You can try editing and saving the files and then re-run them but when you're ready start writing more complex scripts you can use the <a href="https://atom.io" target="_blank">Atom text editor</a> that's been specifically enhanced with the <a href="https://atom.io/packages/rhino-python" target="_blank">rhino-python</a> package to help with scripts that will be run by Rhino.

After you've followed the above links and setup Atom the next step is to get familiar with the different [application programming interfaces (API)](../apis-for-python/) you'll need to write scripts that interact with Rhino.
