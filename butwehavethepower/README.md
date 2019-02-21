Comp 20
Lab 5: Union Strike Folk Song
02_21_2019
William Varteresian

Time spent: Approximately an hour and a half.

Files:
index.html: Contains HTML code provided on the course website,
            with the addition of javascript written by me that
            adds a timeUpdate listener to the video element
            provided and displays subtitles the lyrics of the
            song on screen as they are sung.

style.css: A style sheet for index.html. Defines simple rules
           for the color and appearance of elements, as well
           as one additional rule for a "pow" class that I
           added to make the lyrics look a little more interesting
           by changing the appearance of the word "power."

Acknowledgements: I referred to the doublerainbow example on GitHub
                  for a concrete example of using a timeUpdate
                  listener. I referred to w3schools.com for lists
                  of font and color options in CSS.

Issues: Everything worked as intended when I tested the page,
        but part of me thinks I should have added more features.
        For example, I could have gone through the audio in Aegisub
        to get the precise timecodes for the start and end of every
        line instead of eyeballing it based on the in-browser player.
        I could also have added additional classes and javascript code
        to highlight individual words as they are sung,
        like in a singalong.
        I originally just had the lyrics display, but then I thought
        I might be able to point a variable at a div created within
        my javascript code, so I rewrote my code using that to
        display the name of the singer separately from the lyrics.
        There's a bit in between two of Lisa's verses where Burns
        talks, but I'm only subtitling the lyrics, so I left her name
        on screen during it.