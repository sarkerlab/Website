---
permalink: /pm_abuse_data/
title: "PM Abuse Data -- JMIR"
excerpt: "Page for JMIR publication and data..."
layouts_gallery:
  - url: /assets/images/mm-layout-splash.png
    image_path: /assets/images/mm-layout-splash.png
    alt: "splash layout example"
  - url: /assets/images/mm-layout-single-meta.png
    image_path: /assets/images/mm-layout-single-meta.png
    alt: "single layout with comments and related posts"
  - url: /assets/images/mm-layout-archive.png
    image_path: /assets/images/mm-layout-archive.png
    alt: "archive layout example"
last_modified_at: 2019-08-27T15:46:43-04:00
toc: true
---
## Manuscript and Data

Please cite this paper as: 
O'Connor K, Sarker A, Perrone J, Gonzalez Hernandez G. Promoting Reproducible Research for Characterizing Nonmedical Use of Medications Through Data Annotation: Description of a Twitter Corpus and Guidelines. J Med Internet Res 2020;22(2):e15861. DOI: 10.2196/15861. PMID: 32130117 PMCID: 7066507.


The data described is being used for the SMM4H shared task (Task 4). The shared task website is available [HERE]( https://competitions.codalab.org/competitions/23705?secret_key=aeda0cb9-a3da-4e4f-9d6a-d639355b455e)

The full paper can be accessed [HERE](https://www.jmir.org/2020/2/e15861/)


## Abstract Text

### Background
Social media data are being increasingly used for population-level health research because it provides near real-time access to large volumes of consumer-generated data. Recently, a number of studies have explored the possibility of using social media data, such as from Twitter, for monitoring prescription medication abuse. However, there is a paucity of annotated data or guidelines for data characterization that discuss how information related to abuse-prone medications is presented on Twitter.

### Objective 
This study discusses the creation of an annotated corpus suitable for training supervised classification algorithms for the automatic classification of medication abuse–related chatter. The annotation strategies used for improving interannotator agreement (IAA), a detailed annotation guideline, and machine learning experiments that illustrate the utility of the annotated corpus are also described.

### Methods 
We employed an iterative annotation strategy, with interannotator discussions held and updates made to the annotation guidelines at each iteration to improve IAA for the manual annotation task. Using the grounded theory approach, we first characterized tweets into fine-grained categories and then grouped them into 4 broad classes—abuse or misuse, personal consumption, mention, and unrelated. After the completion of manual annotations, we experimented with several machine learning algorithms to illustrate the utility of the corpus and generate baseline performance metrics for automatic classification on these data.

### Results 
Our final annotated set consisted of 16,443 tweets mentioning at least 20 abuse-prone medications including opioids, benzodiazepines, atypical antipsychotics, central nervous system stimulants, and gamma-aminobutyric acid analogs. Our final overall IAA was 0.86 (Cohen kappa), which represents high agreement. The manual annotation process revealed the variety of ways in which prescription medication misuse or abuse is discussed on Twitter, including expressions indicating coingestion, nonmedical use, nonstandard route of intake, and consumption above the prescribed doses. Among machine learning classifiers, support vector machines obtained the highest automatic classification accuracy of 73.00% (95% CI 71.4-74.5) over the test set (n=3271).

### Conclusions 
Our manual analysis and annotations of a large number of tweets have revealed types of information posted on Twitter about a set of abuse-prone prescription medications and their distributions. In the interests of reproducible and community-driven research, we have made our detailed annotation guidelines and the training data for the classification experiments publicly available, and the test data will be used in future shared tasks.

<!-- - Bundled as a "theme gem" for easier install/upgrading.
- Compatible with GitHub Pages.
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Nine different skins (color variations).
- Several responsive layout options (single, archive index, search, splash, and paginated home page).
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data
- Optional [header images](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers), [custom sidebars](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars), [table of contents](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#table-of-contents), [galleries](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery), related posts, [breadcrumb links](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#navigation-list), and more.
- Commenting support (powered by [Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), [Discourse](https://www.discourse.org/), [utterances](https://utteranc.es/), static-based via [Staticman v1 and v2](https://staticman.net/), and custom).
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Brazilian Portuguese (Português brasileiro), Catalan, Chinese, Danish, Dutch, French (Français), German (Deutsch), Greek, Hindi (हिंदी), Hungarian, Indonesian, Italian (Italiano), Japanese, Korean, Malayalam, Nepali (Nepalese), Persian (فارسی), Polish, Punjabi (ਪੰਜਾਬੀ), Romanian, Russian, Slovak, Spanish (Español), Swedish, Thai, Turkish (Türkçe), and Vietnamese. -->




<!-- | Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

For even more demo pages check the [posts archive][year-archive].

[sample-collection]: {{ "/recipes/chocolate-chip-cookies/" | relative_url }}
[categories-archive]: {{ "/categories/" | relative_url }}
[tags-archive]: {{ "/tags/" | relative_url }}
[year-archive]: {{ "/year-archive/" | relative_url }} -->

---




<!-- ### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fontawesome.io/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](https://jekyllrb.com/)
- [jQuery](https://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- Greedy Navigation - [lukejacksonn](https://codepen.io/lukejacksonn/pen/PwmwWV)
- [jQuery Smooth Scroll](https://github.com/kswedberg/jquery-smooth-scroll)
- [Lunr](http://lunrjs.com)

---

Minimal Mistakes is designed, developed, and maintained by Michael Rose. Just another boring, tattooed, designer from Buffalo New York. -->
