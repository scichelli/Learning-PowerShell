Inspired by [Paul Campbell's essay at TXJS] (http://www.pabcas.com/feeling/my-txjs-2011-talk), I'm taking a careful look at the tools I use--or _could_ be using. PowerShell sits squarely with the latter, a powerful tool that would often present itself as the answer if I were handier with its capabilities. I want to get better at it.

I also have a Dropbox folder full of text files containing urls and notes I want to consider later, which I _never_ get back to because they're a big pile of text files. A big pile that needs editing, renaming, searching, formatting... Sounds like a job for PowerShell!

This repository contains a list of challenges I set for myself (listed in this readme), a representative collection of text files to use as sample input to the challenges, and my attempts to answer the challenges in the form of PowerShell scripts. Feel free to fork the repository and create your own solutions and your own challenges.

1. The files are named Description_Date.txt, but I wish I'd named them Date_Description.txt. Write a script to rename. (For extra practice, write another to switch them back.)
1. Invoke that script from the PowerShell command line.
1. Some files contain keywords like "todo." Write a command to find those files.
1. Write a script for the above find-in-files that accepts a command-line argument for the string to search for. Also search file _names_ for the keyword, since the filename is usually serving as a bookmark description.
1. Write a script that pipes the output of the find-in-files script to a script that outputs the file name and contents (or writes that to a file).
1. Write a script that formats those results as html, uses regex to turn the urls into links, and opens the file in a browser.

