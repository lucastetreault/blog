I stumbled on [these](https://www.cse-cst.gc.ca/en/puzzles-enigmes/) challenges recently and thought I would share some insight in to how I solved the my first one.  

### [Puzzle 14](https://www.cse-cst.gc.ca/en/puzzles-enigmes/puzzle-enigme-14)
The puzzle is simple a gif file that you can download. No real hints at glance. 

![](https://www.cse-cst.gc.ca/sites/default/files/qrackthecode_e_0.png)

I tried unzip'ing, untar'ing and un7zip'ing the file but none of that lead anywhere. I opened up my trusty old hex editor and scrolled through hoping I would find something meaningful... Nothing! 

It wasn't until I read through some of the solutions to older problems that I realized there MUST have been a clue that I was missing. Every puzzle had a clue that would lead to the solution! 

It finally dawned on me that "Qrack the code" wasn't misspelled to be cute... The pixelated stuff in the background of the gif kind of looks like a QR code! Get it? QRack the code? Oh boy... 
 
To solve the puzzle, I opened up my trusty GIMP editor and grabbed just the black pixels (after some trial and error) that ended up forming a readable QR code! Frames 5, 9, 17, 21, 29 and 33 formed a readable QR code.

Following the link in the QR code lead me to a page with the following Dad joke: 

>  You: I have lost an electron.
>  Them: are you positive?
>  You: Yah, I really need to keep an ion them.