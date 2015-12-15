## Word-to-Markdown Workflow 

This document presents step-by-step instructions for converting Word documents to Github Flavoured Markdown.

### 1 Download and install Pandoc

[Pandoc](http://pandoc.org/) is an open-source document converter. While there are [online converters](http://pandoc.org/try/),
it would be better to download and install Pandoc in local machine.

- Download [Pandoc](http://pandoc.org/) and install it.
- Find the installation folder (e.g. `C:\Users\priitp\AppData\Local\Pandoc`).
- Start up *Pandoc User's Guide.html*.

### 2 Prepare documents

- Copy Word documents to be converted into a separate folder (further: Document Folder).
- Open the operating system shell (command line interpreter). It can be [Git Bash](https://git-for-windows.github.io/) or
some other shell.
- Change to the Document Folder`. 
- Optional: Here or later you can check the list of files: `ls`

### 3. Convert the document

Run `pandoc` in CLI (shell). Example:
````
pandoc -s -f docx -t markdown_github -o SecurityServerUserGuide.md SecurityServerUserGuide.docx
````

Options:
- `-s` - produces standalone document
- `-f doxc` - convert from doxc
- `-t markdown_github` - convert to GitHub Flavored Markdown
- `-o` <output file name> - output to file
- `--extract-media=` <folder name> - extract images to separate folder 

After the options provide name of the file to be converted.

#### 4. Check and edit the converted file

Check, and where necessary - correct the Markdown file. Pandoc can be unable to convert everything correctly. In particular, check 
and correct Table of Contents (TOC) links.

NOTE: It's useful to open the original and the converted documents side-by-side.

While there are online side-by-side Markdown editors (for example, http://dillinger.io/), it would be better to enter
the converted file directly into GitHub and edit there. 

- Remove page numbers from TOC.
- Correct links in TOC, you may need to re-build the TOC.
- Remove extraneous HTML code. For example, ´span´ anchor tags that were incorrectly converted.
- Convert heading markings to # and ## style.
- Format examples as Markdown code blocks.
- Upload images into GitHub and adjust links to the images.

Editing and checking of one document can take several hours of work.

#### Testing the Workflow

This workflow has been partially tested by converting
[X-Road 6 SECURITY SERVER USER GUIDE](http://x-road.eu/docs/x-road_v6_security_server_user_guide.pdf).
The converted [Markdown file](https://github.com/PriitParmakson/TEST/blob/master/SecurityServerUserGuide.md)
still needs some more editing: TOC is only partially reworked; images are missing and examples
have not been marked as code blocks.
