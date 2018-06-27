# Ebook for Visual Studio Tips and Tricks



## What is this?
This is the repo for a bunch of tips and tricks on Visual Studio. Everybody can participate.
Every checkin will trigger a build of an ebook. The ebook will have EPUB format and will be available for download freely.
Currently this is a very early state.

## Can I participate?
Yes, absolutly. Your GitHub Name will be listed in the Author section of the ebook, once your Pull Request has been acceppted.

## Why does this project exist?
This is a longer story. Here's the short one.
1. I belive in books and written knowledge.
2. I belive in communities and in sharing knowledge. I profited from this a lot in the past. This is another way to say "Thank you" and to give something back.
3. I think a traditional approach to write books on technical documentation is outdated - the wheel is just turning too fast. We have to be more flexible when it comes to updating and editing.
4. I liked the idea of treating technical documentation in a CI/CD way.

## Will you share the details on how to set up CI/CD for e-books?
Yes. Once it's working I'll write a blog post or something similar on it. All the magic is currently done in Team Services and all the code can be found in this repo.

## Where can I find the ebook?
Here: https://github.com/DanielMeixner/ebook-visual-studio-tipps/releases

## There isn't too much content in the book yet.
I know. 
I'm working on it. Currently my focus was on setting up CI/CD. 

## Guidlines
* Fork the repo.
* Create a folder for your tipp in the content subfolder.
* Add images for your tipp in a images subfolder within your tipp's folder.
* Write your tipp in markdown.
* Be short and precise. Add an "Essentials" and a "Guidance" chapter - as shown in the samples.
* Send out a pull request.
* Currently I will be reviewing your tipp and I have to push the button to build manually. This is just during this early phase. CI/CD could be enabled with a flick of a switch but I have to improve stability and the review process first.

## Current Limitations: 
* Use *.png images only
* Place your content in a folder which will be the name of your chapter. Do not use whitespaces.
* Table of content is broken.



