# exportJPGFromIllustratorLayers
Small javaScript that export all Layers of an Illustrator CS3 file as independent jpgs

## lazyness as motivation
This javaScript is tailored to a very specific Illustrator CS3 file but I think it could be usable for a variety of situations in which you need to produce several different files from one master file.
I know, I know Illustrator CS3 can use variables but what the hell, I did this just for fun.

## The Illustrator file
If you open the .eps file you can see that the structure is very straight forward it has a layer called *cancha.eps* that contains all the basic template of the file
Then each layer on top contain the variable stuff particular to each final .jpg file it is as simple as that.

## Usage
Prepare your .eps file following the structure of the *cancha.eps* file then inside Illustrator CS3 -I wonder if someone is still using it?- go to scripts>other scripts and look for the file *exportJPGFormLayers.jsx*. Follow the steps and relax.
