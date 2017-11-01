# Forgery: An Idea

## Intent 

Turning a handwritten j-program organized in a tree like form with color/style annotations into something executable.

## Inspiration 

[An article](https://www.hillelwayne.com/post/handwriting-j/) where the author described his experience handwriting a `j` program as "drawing binary tree transformations, marking glyphs in a rainbow of colors and annotating them with lines and curves, I suddenly felt like I was scribing a spell. I got to imagine I was a crazy old wizard". 

According to the [Realmatics of Forgery](https://coppermind.net/wiki/Forgery#Realmatics_of_Forgery), this system uses symbols to represent linguistic concepts as a focus for selish investiture.

Using [ligatures](https://en.wikipedia.org/wiki/Typographic_ligature#Ligatures_in_Unicode_.28Latin_alphabets.29) for the first time this year. 

## Implementation 

Now, we don't have any investiture outside the cosmere, but we do have technology. 

So combining [an ascii array language](https://en.wikipedia.org/wiki/J_(programming_language)), [hand writing recognition](https://en.wikipedia.org/wiki/Handwriting_recognition), and k-ary tree recognition, we can have *real* Forgery. 

## Roadmap 

First off is getting anything working. 

This would be image-of-handwritten-j-program $=>_{handwriting\ recognition}$ text $=>_{standard\ compiler}$ executable.