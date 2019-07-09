---
path: "/email"
cover: "../email/Picture1.png"
date: "2019-07-04"
title: "Stacking table head Technique"
tags: ['dell', 'MSC', 'mobile']
published: true
---
#Vendor funding
The funding section can be hidden from the header section for mobile devices, but must in that case be displayed directly below the hero. Funding requirements allow for this change to be made for emails viewed on mobile, and do not require the MDF area to be on the first viewing pane.

##Desktop code example:
####(above the hero)

###HTML
```html
<div class="jss1">
    <header class="jss15 jss21 jss6 jss10 jss13 jss3">
        <div class="jss42 jss44 jss43">
            <a aria-current="page" class="jss46 jss63 jss75 jss4" href="/">Home</a>
            <a class="jss108 jss82 jss84 jss87 jss2" tabindex="0" role="button" href="/media">
                <span class="jss83">Video</span>
                <span class="jss111"></span>
            </a>
            <a class="jss108 jss82 jss84 jss87 jss2" tabindex="0" role="button" href="/games">
                <span class="jss83">Gamejams</span>
                <span class="jss111"></span>
            </a>
        </div>
    </header>
</div>
```
###CSS
```css
body {
    color: white;
    box-sizing:border-box;
}
```
#Hero CTA
**CTAs in the hero section should be extended so that links are easy to press on a mobile device.** CTAs must not overlap with a product image, but it is possible for them to overlap with a background image in some cases (as long as the CTA is still legible and does not blend into the background). See examples of the code below for guidance on how to optimize this for mobile devices
###HTML
```html
<div class="jss1">
    <header class="jss15 jss21 jss6 jss10 jss13 jss3">
        <div class="jss42 jss44 jss43">
            <a aria-current="page" class="jss46 jss63 jss75 jss4" href="/">Home</a>
            <a class="jss108 jss82 jss84 jss87 jss2" tabindex="0" role="button" href="/media">
                <span class="jss83">Video</span>
                <span class="jss111"></span>
            </a>
            <a class="jss108 jss82 jss84 jss87 jss2" tabindex="0" role="button" href="/games">
                <span class="jss83">Gamejams</span>
                <span class="jss111"></span>
            </a>
        </div>
    </header>
</div>
```
###CSS
```css
body {
    color: white;
    box-sizing:border-box;
}
```