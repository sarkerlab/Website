# Welcome to the Sarker Lab Website!

This document will explain how to set up an environment for testing changes to the website before making them live, perform common updates and deploy the website.

---

### Setting Up Git

If you do not have a [github account](https://github.com/), you will need to make one. Once you have made a github account, follow these steps:

1. Open your terminal
2. Enter the following `git --global user.name "[YOUR GITHUB USERNAME]"`
3. Enter the next line `git --global user.email [YOUR GITHUB EMAIL]` (no quotes around email!)
4. Clone your version of the lab website to the server using  `git clone https://github.com/sarkerlab/Website.git`

> Note: You will need to familiarize yourself with how Git works - there are plenty of tutorials and I would suggest the official tutorial from the [Git Website](git-scm.com).

### Running Jekyll locally

1. Open your terminal
2. Using the terminal, cd to the directory where you cloned the Website code e.g. `cd ~/your_directory/Website`
3. Once there, run the command `bundle exec jekyll serve`. You should receive an output where it shows a line like `Server address: http://localhost:4000`

Now, you can peruse the local version of the website as if it is live! Any changes you make to the codebase while jekyll is still "serving" the website pages, will appear in localhost (you may need to refresh the page for the changes to show up).

> Note: Jekyll renders Markdown into HTML; the HTML is then stored in `_site/` files.

> Error Note: If jekyll does not work when you run `jekyll serve`, run this command in your terminal, `source ~/.rvm/bin/rvm`. This should now enable jekyll to work properly.

---

## Linux Set-Up

If you want to run jekyll and the website locally, it is fairly straight forward. For this tutorial, I am going to assume you are familiar with the major concepts with Linux (package managers, distributions, etc.) Instructions are below:

1. Install [RVM](https://rvm.io/rvm/install) to your system with the latest version of Ruby (the RVM instructions will tell you what to do)
2. Install [Jekyll](https://jekyllrb.com/docs/installation/) and make sure you have all the proper dependencies
3. Clone the [Website](https://github.com/sarkerlab/Website.git) github repository to your machine
4. Go to the repository and run `jekyll serve`

From there, you should be set to go! Enjoying playing around with Jekyll locally.

---


# Updating the Website

## Adding People

To add or update people, you will need go to the file `people.md` in the _pages folder. Add the following format and attritubes:

```
-
 name: Who, MD
 title: Time Lord
 dept: TARDIS
 location: Space
 picture: /assets/img/who.jpg
 twitter: "https://twitter.com/bbcdoctorwho"
 email: mailto:badwolf@infinitymail.xio
 site: "https://www.doctorwho.tv/"
 pubs: "http://www.bbc.com/"
-
```

## Adding Publications

To add a new publication page, you will need to create a new file in the `_posts` folder. Publications will be categorized according to the YEAR-MONTH-DAY-title format.

YEAR is a four-digit number, MONTH and DAY are both two-digit numbers, and title is the name or phrase of the publicaton. For example, the following are examples of valid publication filenames:

```
-
2016-07-20-my-publication-name.md
2015-01-03-publication-title-goes-here.markdown
-
```

## Updating Publications

To update or finish creating a publication, add the following format and attritubes in the existing publication's file. 

```
-
 authors: "J. Doe, N Smith"
 title: "Publication title here"
 additinal info: "Any Additional info about publication."
 external_url: "https://publication/link/here"
 data: "https://data/link/here"
 code: "https://code/link/here"
 resource: "https://resource/link/here"
-
```

## Updating the Rest of the Website

The rest of the website is much easier to update. Here are locations for files and what files to edit to get the desired changes:


# Notes
