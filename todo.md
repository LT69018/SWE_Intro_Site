- [X] Populate about me page + make a folder for images (i.e. my **headshot**, a )
    - add resume, linkedIN, maybe twitter    

- [X] Format: 
    - [X] Once **we make the links go to the relevant pages on index**, make sure the page content goes on the right side of that.
    - [X] Reformat pages to use left-most sidebar. 
    - [X] main container: want gap between the h1 and the navbar.


If time permits:
- [ ] Add preview image to ReadME.md
- [ ] *find a way to have the header appear on each page. Is there a way to load/inject html from a **common header**.html?*
    - [X] Use Bootstrap to create a header.
    https://getbootstrap.com/docs/5.3/examples/headers/#
    - [ ] Probably use JS to populate the same header across multiple pages. So I don't have to keep copy and pasting it between files!: JQuery
- [ ] Collapsable side-bar (i.e. click a === on the top left to make it appear.)
Resolved:
(If we go with the bootstrap source sidebar, we don't need this.)
    - [ ] navbar active link (Want light purple with white text instead of completely white and black)
- [X] index.html: Fix formatting of body container. (wondering why it doesn't look the same as the about-me.html)
    - Figured it out, I accidentally closed the div container class before I put the header and paragraph in it.
- [X] Link the about me page back to the main html (index.html)
    - as of 2/9 this is happening by just copying and pasting a `<nav>` between html pages.