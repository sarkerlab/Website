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

### Running Jekyll Locally

1. Open your terminal
2. Using the terminal, cd into the directory where you cloned the Website code `cd ~/your_directory/Website`
3. Once there, run the command `jekyll serve`. You should receive an output where it shows a line like `Server address: http://localhost:4000`

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

To add people to the peoples page, go to the file `members.yml` in the _data file. To add a new person to the members page, add new yml like so:

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

Make sure if you want to include an image alongside a person's profile, to put that image in the _site/assets/img folder.

> Note: Do not forget the hyphens and indentation levels! yml files are quite picky.

## Updating the Rest of the Website

The rest of the website is much easier to update. Here are locations for files and what files to edit to get the desired changes:

+ Update  `__people/__`
+ Update Info (onboarding) at `__info.md__`
+ Update Ethics at ` __ethics.md__`
+ Update Jobs Page at ` __jobs.md__`


## Adding Publications

To update the publications to the publications page, go to the file `members.yml` in the _data file. To add a new person to the members page, add new yml like so:

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

Make sure if you want to include an image alongside a person's profile, to put that image in the _site/assets/img folder.

> Note: Do not forget the hyphens and indentation levels! yml files are quite picky.

## Updating the Rest of the Website

The rest of the website is much easier to update. Here are locations for files and what files to edit to get the desired changes:

+ Update Alumni or Gari's bio in `__people/__`
+ Update Info (onboarding) at `__info.md__`
+ Update Ethics at ` __ethics.md__`
+ Update Jobs Page at ` __jobs.md__`


---

# Notes
