Boggle Board
=============

Check the demo on https://rahul-sr.github.io/boggle-solve/?rows=5&cols=5&text=somecharactersherefortesting

A 3x3 boggle board that looks like this:

y o x
r b a
v e d

Has exactly the following words on it:
bred, yore, byre, abed, oread, bore, orby, robed, broad, byroad, robe, bored, derby, bade, aero, read, orbed, verb, aery, bead, bread, very, road
Note that it doesn't have “robbed” or “robber” because that would require reusing some letters to form the word. And it doesn’t have “board” or “dove” because that would require using letters which aren’t neighbours. Also note that there only 4 or more letter words because that is the constraint on word length used here.

Instructions
------------
Just fill in the puzzle and then click Solve, or hit Enter. You can also feed
data using query parameters, e.g. `...?rows=4&cols=4&text=somecharactershere`.
The characters will populate the puzzle one row at a time, filling columns from
left to right.

Dictionary Size
---------------
Note that the dictionary included in the demo contains words up to length 7.
This is so the demo loads quickly.


Setup
-----
To check the application on local machine, just open the index.html in browser