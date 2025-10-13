# Twine Tips and Tricks
https://twine2.neocities.org/  
![The Twine GUI](assets/twine_desk.png)  

These are a few helpful tips and tricks for building your Twine game. 

## Links
The most basic part of making a text adventure is linking passages to one another. The syntax looks like this:

![Twine links](assets/twine_link.png)  

## Styles
Styling your text might also add to the flavor of your game.

 <img src="assets/twine_style.png" alt="Twine styles" width="400"> 
![Twine styles](assets/twine_style.png)  
![Twine styling text](assets/twine_textstyle.png)  

### CSS and styling
This is an example of a CSS stylesheet. You can change the look of an entire story by editing the stylesheet for your Twine game. Go to the menu, find "Story," then # Stylesheet. 
```
@import url('https://fonts.googleapis.com/css?family=Amatic+SC');

tw-story {
   background-image: url("https://fetalcircuit.github.io/teethmonster/imgs/chatter.gif");
   background-repeat: no-repeat;
   background-size: 100% 100%;
  
  color: #ffffff;
  font-size: 20pt;
  font-family: 'Amatic SC', cursive;
}

tw-link, enchantment-link /* sets both base link colors */
{ color: #ffffe6; }
tw-link:hover, enchantment-link:hover /* sets both hover link colors */
{ color: #ffffff; }
.visited /* all visited links */
{ color: #FFFF00; }
.visited:hover /* all visited hover links */
{ color: #ffffff; }
```

## Transitions
You can also change the way one passage transitions to another.

![Twine transitions](assets/twine_transitions.png)  

## Variables and Conditionals
While the functionality of building a text adventure game is mostly in linking one passage to the next, you can create things like variables and branching sequences (conditionals) that change the nature of your game. 

![Twine creating variables](assets/twine_set.png)  
![Twine printing out variables and strings](assets/twine_print.png)  
![Twine if statements](assets/twine_if.png)  
![Twine else-if statements](assets/twine_else-if.png)  
![Twine else statements](assets/twine_else.png)  

## HTML
If you have skills in HTML, you can use that syntax right in the TWINE passages as well.

![alt text](assets/twine_html.png)  

## Images
If you want to add images:

https://www.w3schools.com/tags/tag_img.asp



