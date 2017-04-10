# top-deck-web-design
Fully Responsive Web design for the travel company - Topdeck


I am so happy to have learnt Sketch 3. It allowed me to build a brand new logo for Topdeck as showcased within the project files.

Biggest challenge was obviously designing to smaller size.

I made an error at the start by starting to design at the desktop size and then scale it down to mobile.

This caused the obvious space issues. But I battled through them and made it work.

From now on, I will be doing mobile first approach.

Also to keep in mind is to use "em" as the unit for defining the size in media-queries instead of "px". This is to help the design stay in shape even in the case where the user might zooms in.

.scss format helped greatly by letting me define variables and nesting saved my life so many times in making the code look structured to read even when it grew to about 500 odd lines.

window.matchMedia.matches in Javascript is a great nifty way to manipulate the media queries especially with background pictures since they will be in different sizes but some times at some specific points, the picture size may not be enough or maybe too big. This can be adjusted with JavaScript.

Background position property comes to rescue if the images used are only available in a single large size. Instead of trying to cut it out, We can use the above mentioned javascript function together with this property to manage the section that is displayed on the screen.

