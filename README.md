WEBSITE STRUCTURE:
HOME PAGE/
│
├── index.html           # Homepage
├── songs.html           # favorite songs page
├── add.html         # add songs to favorite songs page
│
├── css/
    └── lemonade.css   


    ## Button Descriptions and User Actions

### Home Page (index.html)
- **Menu Button:** Opens the left navigation panel.
- **View Favorite Songs:** Takes the user to the Songs page.
- **Add a Song:** Takes the user to the Add Song page.
- **Category Boxes (Top Hits, Pop Favorites, etc.):** Visual buttons only — no active links yet.

### Songs Page (songs.html)
- **Back Button:** Returns to the previous page.
- **Song List Items:** Display song names; no additional action.
- **Add a Song:** Opens the Add Song page.
- **Home:** Returns to the Home page.

### Add Song Page (add.html)
- **Save Song:** Saves the entered song details into Web Storage and redirects to the Songs page.
- **Back to List:** Returns to the Songs page without saving.
- **Back Button:** Goes to the previous page.
