# ReadMe

## Getting Started

### Jekyll

> ## NOTE: Installation is not needed on a local machine except to test before uploading new documents.  Jekyll does not actively support versions for Windows.  Installation on *nix and OSx is vert straightforward.

# Installation

* [Installation instruction for Windows](https://jekyllrb.com/docs/windows/)
    * [Chocolately Windows Installation package](https://chocolatey.org/install)
* [Install from Linux or MacOS](https://jekyllrb.com/docs/installation/)

Duane used the following without any problems: Windows installation process from https://labs.sverrirs.com/jekyll/

Practice install was done with
1.  Ruby 2.2.* or most recent recommended stable version for a 32-bit or 64-bit OS.
2.  RubyDevKit for the selected Ruby version and 32-bit or 64-bit OS.
3.  gems for jekyll, builder, and themes


Tips from [Sourceforge](https://sourceforge.net/p/anacondapython/discussion/markdown_syntax) on Markdown.

# Jekyll File Information
## configuration files
### _config.yml
Global settings and variables are in the _config.yml file in the root directory.

Examples of informational items currently stored here are:
* title: OMSCS 6460 Educational Technology Course Library - Georgia Tech
* email: david@davidjoyner.net
* baseurl: "" # the subpath of your site, e.g. /blog
* url: "" # the base hostname & protocol for your site, e.g. http://example.com
* twitter_username: [enter your twitter handle]
* github_username:  [enter your GH uid]

Configuration items are also stored here:
* markdown: kramdown
* theme: minima

Other variables can be created and referenced directly from any page in the document.
This is good for recurring document types such as footers and headers.

## include files
### header.html

### footer.html

### default.html

## YAML
A lot of information exists about YAML.

# Markdown
An inline link is the most common item in the web pages.  The syntax is to enclose the reference text in [ and ] and the hyperlink in ( )

Example: [OMSCS CS6460 Syllabus]()

Also, in markdown, paragraph tags are not required.  Put a blank line
between paragraphs to start a new paragraph.  Contiguous lines, with the
line break for readability, are rendered as a single paragraph.  Be sure
 to leave a leading or trailing space in a line if needed to get the
 proper formatting.

Blank lines are not needed following a special formatting character like '#'.

