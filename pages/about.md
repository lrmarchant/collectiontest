---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="This is the first psychiana section;This is the second section" %}

## This is the first psychiana section

Is this a dagger I see before me? The handle toward my hand?

{% include feature/item-figure.html object="demo_001" width="50"%}

## This is the second section

Come, let me clutch thee. I have thee not yet I see thee still.

{% include feature/card.html header="Art thou" text="fatal vision sensible to feeling as to sight?" width="50" centered=true %}

## About the Collection

This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

The base site features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
