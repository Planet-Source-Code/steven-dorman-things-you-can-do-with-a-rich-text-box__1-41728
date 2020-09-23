<div align="center">

## things you can do with a Rich Text Box


</div>

### Description

This Will Teach You How To Do Many Things With A RTB.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Steven Dorman](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/steven-dorman.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/steven-dorman-things-you-can-do-with-a-rich-text-box__1-41728/archive/master.zip)





### Source Code

<BR>
<HR size=1 color=red>
<marquee bgcolor=red>Welcome to the unknown coders Rich Text Box Tutorial</marquee><BR>
<hr size=1 color=red>
<BR>
<font color=green>1.Have you ever wondered how to format etc. using RTB's?</font>
<BR>
In Visual basics, there is a control called a RichText Box<BR>
This RichText Box allows you to <font color=blue><b> Syntax Color </b></font>, change <font color=blue><b> font color , </b></font>
change <font color=blue><b> font size , </b></font> as well as allowing text to be <font color=blue><b> bold,italisized,underlined,have strikethrough,size,type </b></font>
and MUCH more!<BR><BR>
<font color=red size=1><b> through out the tutorial we will refer to richtext boxes as " rtb " or "rtb's" </b></font><BR><BR>
there will be a few sections , explaing how to do these things , along with some helpful info along the way.
<BR>
<BR>
<font color=green>2.Possible Uses...</font><BR>
there some possible uses for RTB's , like :
<BR>
A html editor , the use could be syntax coloring.<BR>
a text editor ( like wordpad ) so you can use font types , colors and sizes <BR>
or just to make your programs look nicer!<BR>
<BR>
<font color=green>3.the bare basic's ( bold etc )</font><BR>
First we will need to make the rtb.<BR>to get one:<BR>
start a .exe project and :<BR>
press and hold ALT and then press p this will open the menu , <BR>
now ( still holding alt ) press N , this will open the " refrences " menu.<BR> <BR>
scroll down the list untill you find some sort of thing says rich text box.select it and click ok.<BR>
<hr>
for newbie programmers:<BR>
ALOT of functions and controls are not in the list to your left , <BR>
to get more , simply repeat the previus selecting a diffrent one.<BR>
<hr>
<BR>
first thing : use that newfound rtb control and make a rtb on your form and name it rtb.<BR>
next i would create some sort of button etc. , name is cmdbold and attach this code to it:<BR>
<font color=orange><b> if rtb.selbold = false then<br>rtb.selbold = true <br>else <br>rtb.selbold = false<BR> end if </b></font> <BR>
explanation:<BR>
rtb.selbold is the formation to make the rtb well <b>bold</b><BR>
the if procedure checks to see if its bold , if it isnt turns it on , and vica verca ( i think i spelt taht wrong ) <BR>
<BR>
here are some other things you can do to change the formating in an rtb.<BR>
replace selbold with:<BR>
selitalic , this makes it <i> italisized </i> <BR>
selunderline , this makes it <u> underlined </u><BR>
selstrikethru , this makes is striked ( cant do that one :P ) <BR>
<font color=green>4.colors and sizes!</font>
<BR><BR>
its the same structure for color and sizes<BR>
add a new button called cmdcolor , and add a commondialog control and name it cd.<BR>
attach this code to cmdcolor : <BR>
<font color=orange><b> on error resume next<BR>cd.showcolor<BR>rtb.selcolor = cd.color </B><BR></font> <BR>
this simply opens a color dialog box and sets the rtb's color ( the line is rtb.selcolor = cd.color )
<BR>
size is the same except this is all you need: <BR>
make a new button and name it cmdsizeto40 , then add this code to the button <BR>
<font color=orange><B>on error resume next<BR>rtb.selfontsize = 40 </B></font><BR>
this simply sets the rtb size to 40! <BR>
thanx for reading this article , i will make it better , but i have to go.
<BR>
visit my site <a href="httP://www.h-g-p.tk">CLICK HERE!</a>

