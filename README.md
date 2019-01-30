# aptt
**Website for A Place to Talk (pages.jh.edu/aptt).**

## Getting Started
**To make any changes to the A Place to Talk (APTT) website, you will need to
follow the setup instructions below.**

First, ask the APTT Co-Directors to request website access for you and any
other member who is authorized to modify the website. The Co-Directors must
contact Johns Hopkins (JH) IT and provide them with the JHED IDs of all members
who are requesting access.

Once you have been given access to modify the website, you will need to install
software to access the JH file system. The easiest program to use is
[CyberDuck](https://cyberduck.io/) (Mac and Windows). This
[sample screenshot](http://pages.jh.edu/~websvcs/cyberduck-setup.png) may help
you understand the setup process. Make sure you change the drop-down item to
have "HTTP/SSL" instead of plain HTTP. You also must change the JHED fields to
match your JHED. You must create a "bookmark" to get the "more options" section
so you can enter the correct path. "Open Connection" will not work as it does
not have the "more options" section in the dialog box. Files must go in the
`public_html` directory (folder). The `public_html` directory itself must NEVER
be deleted, but you can delete anything within it as needed. If you have any
questions throughout this setup process,
[contact JH IT](https://it.johnshopkins.edu/help/).

If you need to access the files while off the JH wifi network, you must connect
via the [JH VPN](http://www.it.johnshopkins.edu/services/network/VPN/). You will
need to follow the options for "Pulse Secure" if you do not already have "client
access."

## Editing Website Content
### Simple Content Edits
For most edits to the content of the website, such as updating member names,
adding information about the APTT application, or other simple content edits,
you will only need to modify the `index.html` file. Editing this can be done
with any plain-text editor, such as TextEdit (Mac), WordPad (Windows), or
[Atom](https://atom.io/) (Mac and Windows).

Throughout the `index.html` document, you will find comments (these begin with
`<!--` and end with `-->`). These are meant to make the code more readable and
to help indicate how to edit content on the website. Look for the comments that
include `begin modify me` - these indicate the beginning of a section of the
code containing text that can easily be modified to change website content. A
description of what part of the website the section corresponds to is usually
included in this comment as well. The end of these modifiable sections is
denoted with another comment that includes `end modify me`.

### More Complex Edits
Portions of code outside of the modifiable sections discussed above can
definitely be edited, but they usually contain more vital code which may cause
problems on the website if improperly modified. You are more than welcome to
make more substantial changes to the website, including completely re-doing the
website, if you want. Before you make any substantial or complex changes,
however, be sure that you are familiar with HTML and CSS, and maybe even
JavaScript if you would really like to customize the behavior of the website.

Also, be sure to work with **many** backups of the website during development.
This will take a little extra time to set up and maintain, but will save you
**hours** of time if you make a mistake. Git is a great version control system
that allows you to upload and track versions of your code throughout development
(like Google Drive for developers). Two of the most popular Git hosting
repositories are [GitHub](https://github.com/) and
[BitBucket](https://bitbucket.org/).

## Learning Resources
Web design skills are very useful and are fun to learn. If you are interested in
learning more about HTML, CSS, JavaScript, and web design in general, there are
many great resources on the internet. Here are some to get you started:
[HTML Tutorial](https://www.w3schools.com/html/)
[CSS Tutorial](https://www.w3schools.com/css/)
[JavaScript Tutorial](https://www.w3schools.com/js/)
[Git Handbook](https://guides.github.com/introduction/git-handbook/)
