# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I struggled the most with the icon, label and score. I tried a variety of ways, but I went back to just using a table driven approach. When I first started this I created the summary sections as basically duplicate CSS coding, but I realized after I was done, there wer probably a lot of overlapping things that could have been handled with one CSS coding portion. I sort of incorporated that with the table drive data cells utilizing the same class to drive the styling. So here is a snippet of the code i used:

```html
<div class="reaction">
        <table>
          <tr>
            <td class="logo1"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#F55" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M10.833 8.333V2.5l-6.666 9.167h5V17.5l6.666-9.167h-5Z"/></svg></td>
	          <td class="label1"><b>Reaction</b></td>
	          <td class="score1"><b>80</b> / 100</td>
          </tr>
        </table>
      </div>
```
```css
td.logo1 {
	text-align: left;
	padding-right: 8px;
	}

td.label1 {
	text-align: left;
	width: 100px;
	padding-left: 10px;
}

td.score1 {
	text-align: right;
	width: 140px;
	padding-right: 10px;
    color: black;
}
.reaction {
    background-color:hsla(0, 100%, 67%,0.1);
    color:hsl(0, 100%, 67%);
    width: 300px;
    border-radius: 15px;
    margin: 15px 25px 15px 25px;
    text-align: right;    
    font-size: 20px;;
    }
```

### Continued development

I started to dabble in divs, spans, classes, and trying to get the logo/label/score all on one line. These are all areas that I think I will continue to investigate on how best to utilize each of those components. Plus when to use HTML tables vs CSS Grid or Flex.


### Useful resources

- [Example resource 1 - Adding shadow](https://www.w3schools.com/css/css3_shadows_box.asp) - I googled how to add the shadow around the item and found this.
- [Example resource 2 - first time using grids](https://www.w3schools.com/css/css_grid.asp) - with the large "card" and dividing it into 2 columsn I knew about using CSS to create a grid, so I followed along with some of this.
[Example resource 3 - getting icons and text onto the same line](https://stackoverflow.com/questions/15172520/advantages-of-using-displayinline-block-vs-floatleft-in-css)(https://css-tricks.com/tips-aligning-icons-text/) - Before I abandoned hope on the multi line endeavor to just use a table drive approach, I looked at these websites and could get it to work with an icon and one portion of text; but I could get things to line up the way I wanted, so I scrapped it.

## Author

- Website (In Progress) - [Mitchell Lazore](https://wwwebsbymitchell.wordpress.com/)
- Facebook - [Mitchell Lazore](https://www.facebook.com/mitchell.lazore/)




