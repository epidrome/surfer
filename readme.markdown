---
layout: page
title: About
permalink: about.html 
---

## Surfing, photography, and life
The photos in this digital album stand for a rather small and non representative sample of surf and photography. In my experience, as a photographer and as a surfer, I have found that the best moments in life are to be experienced with full engagement and almost zero gadgets. Indeed, early surfboards were handmade and did not have any fins, while early surfers did not wear any fancy (branded) swimwear.

## Some notes on image gallery software
There is a lot of software available for managing image galleries. Of course, just like any piece of software, current digital photo albums make several assumptions that might not be suitable, depending on the requirements.

The specification I was looking for included:

* A style similar to Instagram, because people are creatures of habit, even when those habits are bad for them, especialy then!
* Git repository for the code, but not for the images.
* Flexibility to choose the web site theme and the image viewer library.

## Image files are outsourced
Image files are hosted and managed by a dedicated Content Delivery Network (CDN). Hosting and delivering multiple image formats according to user device and network is a complicated problem.

## Slow social features
It is nice to receive a personal email message that is thoughtful and meaningful. You know, the kind of communication that, not so long ago, people used to have on paper mail, before chat.

## Dependencies

* [Jekyll Minima](https://github.com/jekyll/minima) is already flexible enough with skins, social media icons, and configuration files.
* [nanogallery](https://nanogallery2.nanostudio.org) has been implemented as a jekyll minima custom head and a [jekyll layout](https://jekyllrb.com/docs/layouts/).
* [Uploadcare](https://uploadcare.com) manages the photo delivery and the automatic production of photo thumbnails.

## Alternatives

Why bother with this piece of (fragile) software that requires you to understand the inner workings of some machinery? Just use instagram, but be careful not to be used by it ;)



