# 11056-project2

## 11056 Project 2 Starter

This is repo containing everything you need to start Project 2. All you need to do is clone this repository to your computer and start editing...

Make sure you refer to Canvas for more info.

## Install Elventy
From Terminal, navigate to the folder you saved the repository in:

Type `npm create`

or, if that doesn't work: `npm install --save-dev @11ty/eleventy`

## Test your site

Open Terminal and type: `npm start`

This will create a local server to test the website.

Go to: http://localhost:8080 to view your site

## Build the site

Run `npm build`

Open up your site folder and you'll discover a folder within it called `final-website` this is where your actual site files are located. 

# Reflection
This assignment required me to continue to use HTML and CSS in order to create an experimental, responsive website. The project additionally introduced to the concept of a Static Site Generator, a program which creates different files from necessary components of a site. These can then quickly and easily be filled with different content using a Markdown file. Whilst I was initially confused by the applicability and process of creating a site with this method, this project allowed me to see the considerable benefits it provides, particularly across multiple pages. 

To begin the assignment, I first had to download a Static Site Generator. I was originally intending to use the recommended program Jekyll, however as there were too many difficulties downloading the system, I opted for Eleventy. I was additionally provided a template, which was extremely helpful in showing me how to operate a statically generated site. I decided I wanted to create a portfolio website, as I could have more creative freedom in the design, and could include interesting elements such as a photo gallery or ‘Prior Experience’ segment. 

I began by making small changes to the layout, adding a hero content banner. I then attempted to create an image gallery. This was the most difficult aspect to overcome with this assignment. However, with some help from my classmates, I realised that fully utilising the ‘Front Matter’ content on the Markdown file allowed me to place images in the homepage.html file and edit the styling in CSS. I also decided an easy method of adding a caption to the images, was to simply reuse the ‘alt’ text. I then proceeded to create the ‘Experience’ segment. This was fairly easy, as I just had to make multiple cards and place them within a block. I had initially wanted to make this segment an interactive vertical scroll feature by essentally overlapping the cards and adding Javascript (as I have made a this before in previous commissioned projects), however when I tried to edit the eleventy.js file I caused a number of errors. If I were to continue this project further, I would attempt this again, and hopefully figure out how I was causing these issues. Nevertheless, I was very happy with the Experience segment I did create. I then realised I could include Figma prototypes I had made in the past, as the website allows users to embed the designs into the code. This was then styled in CSS to match the Experience segment, with round corners and border shadow. I attempted to place a video using the < video > tag and the prior method I had adopted for placing images, however the video itself did not appear in my images folder and therefore I could not actually place it. If I were to continue this further, I would try to understand what I did wrong and ideally resolve the issue so I could add these elements to the website. Finally I made minor cosmetic changes, including adjustments to the header and footer, as well as image sizing. 

If I were to continue this project further, I would try to add more pages and a navigation bar, in order to apply and use the Static Site Generator to its fullest potential. I would additionally try to add other portfolio content such as videos and pdf files. This assignment has been extremely useful, introducing me to new methods of creating websites and how they are operated within the industry. 