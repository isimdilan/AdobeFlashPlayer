# AdobeFlashPlayer
This application I made using Adobe flash player, with using actions.

There is a list on the phone screen and some fruits on the screen. When the fruit is clicked, a check tick appears next to the fruit in the list.

![flash2](https://user-images.githubusercontent.com/72500382/99132048-fa4e1a00-2625-11eb-997c-8a6c8233b0f3.png)

/* Mouse Click Event
Clicking on the specified symbol instance executes a function in which you can add your own custom code.

Instructions:
1. Add your custom code on a new line after the line that says "// Start your custom code" below.
The code will execute when the symbol instance is clicked.
*/

muz1.addEventListener(MouseEvent.CLICK, mz);

function mz(event:MouseEvent):void
{
	// Start your custom code
	// This example code displays the words "Mouse clicked" in the Output panel.
	trace("");
	tk1.visible=true;
	muz1.visible=false;
	
}
ananas.addEventListener(MouseEvent.CLICK, ana);
function ana(event:MouseEvent):void
{
	// Start your custom code
	// This example code displays the words "Mouse clicked" in the Output panel.
	trace("");
	tk2.visible=true;
	ananas.visible=false;
}

çilek.addEventListener(MouseEvent.CLICK, clk);
function clk(event:MouseEvent):void
{
	// Start your custom code
	// This example code displays the words "Mouse clicked" in the Output panel.
	trace("");
	tk3.visible=true;
	çilek.visible=false;
}
![flash3](https://user-images.githubusercontent.com/72500382/99132053-ff12ce00-2625-11eb-9150-8079cee8d9b6.png)

tk1.visible=false; //Check tick
tk2.visible=false; //Check tick
tk3.visible=false; //Check tick

![flash4](https://user-images.githubusercontent.com/72500382/99132061-033eeb80-2626-11eb-97d7-263e615dc9a5.png)

![flash5](https://user-images.githubusercontent.com/72500382/99132067-076b0900-2626-11eb-9c7e-e4a6700ad497.png)
