Comp 20
Lab 4: Responsive Design
02_13_2019
William Varteresian

Time Spent: Approximately 2 hours

Files:
index.html:     An HTML page provided for the lab. Defines a div
                with the class "homer" in the body.

responsive.css: A style sheet for index.html. Defines the "homer" class
                for a number of specified ranges of screen widths
                such that a different section of homer.jpg is displayed
                depending on screen width.

homer.jpg:      A sprite sheet provided for the lab. Four frames
                of Homer Simpson entering or leaving a hedge.

Acknowledgements: I referenced the online tutorials linked on the lab
                  assignment page for details on implementing sprites
                  in CSS and for setting different rules for different
                  device widths.

Issues: I initially used "max-device-width" instead of "max-width"
        in my CSS, which of course did not work with resizing the
        browser window. A little experimentation fixed the issue.
        I would ideally have liked to add CSS rules for more devices,
        but the resolutions provided for the lab only seem to make sense
        for a laptop screen and I do not want to deviate from the specs
        by experimenting with widths for other devices.