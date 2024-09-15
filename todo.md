Goal: create a light, easy way to create text-only, choice-based games using ink scripts.

1) Implement the build process. Someone should be able to put their ink source file (not the compiled JSON) in the `public/` folder, run `npm run package`, and get a nice zipped HTML package in `dist/`, ready for itch.io. This process should also try to extract metadata from the ink source file and embed it into the index.html file.

2) ~~draw the rest of the owl~~ Implement the barebones engine. This should be a text interface friendly to both mobile and desktop displays, with smooth text transitions, scrolling, and choice menus. This should also be implemented entirely in vanilla JS, HTML, and CSS. 

    Note: shamelessly rip off the disco elysium text column.

3) Implement special syntax support that would allow things like:
    - pop-up flavor text for choices
    - twine-esque hyperlink text expansion 
    - etc.

4) Implement quirky save system. While browser cookies are _fine_, what if we let players download a data-embedded image file?

5) Polish the interface. 