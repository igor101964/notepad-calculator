# Notepad Calculator

This is a simple single page web-app with no back end allowing you to mix free-form text and calculations, along with the ability to use variables. This code is the prototype of the more fully featured version at [notepadcalculator.com](http://notepadcalculator.com).

## Storage of data

Your calculations are stored within your brower's localStorage so that next time you open the calculator, it will contain your previous calculations.

## Inspiration

OK, so this isn't the most original idea in the world. A year or two ago I heard about [Soulver](http://www.acqualia.com/soulver/) and at the time wasn't using OS-X so it wasn't available to me, and I made this instead. (I still haven't tried Soulver.)

## How I use it

I now use it within [Fluid](http://fluidapp.com/), which creates a separate OS-X application just for this calculator, making it convienient to open using Spotlight instead of the default system calculator. The downside of this is that it doesn't retain the localStorage between sessions.

## Warning

It runs ```eval()``` on arbitrary user provided code. This isn't a problem if it's used as a completely private tool, but if you plan to develop this further to allow sharing of calculations, you'll definitely want to think seriously about the security implications.

## MIT Licenced

I'm releasing this under the MIT licence, so feel free to do whatever you like with it! If you make anything cool, please let me know!

