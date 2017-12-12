## Writing Your First Spell

When you find a magik word in Minecraft, you can type it as a Minecraft command to add it to your spellbook.

To issue a Minecraft command, press the '/' key on your keyboard, then type the magik word. Press Enter, and you get a link to the spellbook. 

If your spellbook is already open in your web browser, you don't need to click on this link - you can just use the keyboard short cut `Alt-Tab` (on Windows) or `Command-Tab` (on Mac) to switch to your already open spellbook.

To use the link to the spellbook, press 'T', then click on the link with your mouse. This opens the spellbook in your web browser.

If Minecraft is full-screen, switch out of full-screen to see your browser.

Note that the spellbook works best in Google Chrome. At the moment this is the only officially supported browser. We develop on, test, and use Google Chrome.

You can also do a tour of the spellbook with Garry Pottr. Click on the "Help & Tours" button in the spellbook:

![Help & Tours.png](//media.corilla.com/magikcraftio/Screen%20Shot%202017-06-19%20at%209.10.20%20pm.png)

To have Garry Pottr walk you through creating a spell, select the "Feedme Spell" tour:
![Feedme_Spell.png](//media.corilla.com/magikcraftio/Screen%20Shot%202017-06-19%20at%209.10.26%20pm.png)

Here's an explanation of that spell.

1. The first thing you need is magik. You get that from magikcraft.io. Type the following into the spellbook:
```
const magik = magikcraft.io;
```	

2. Now you will create a **function**. A function is a magik spell that allows you to do things using special words. We are going to create a **feedme** spell - this is the name of the function, and the name you use to cast the spell in Minecraft:
```
function feedme(){

}
```
The parens **()** and the curly braces **{}** are important parts of spells in JavaScript. If they are not done right, then the spell will fail! So take care.

3. Now we will put the magik word `magik.satio` into our new spell:
```
function feedme(){
	magik.satio();
}
```
You've got parens **()** again, and a semi-colon **;**
The semi-colon goes at the end of a line in a spell, just like a full-stop goes at the end of a sentence.

4. Press the Save button to save your spell. You will see: 
```
Go to Minecraft and type /cast feedme
```
## Congratulations!
You just wrote your first spell. Now you can go to Minecraft and cast it.