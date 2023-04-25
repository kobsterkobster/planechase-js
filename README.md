# planechase-js
Learning Javascript with the help of AI by making a Planechase WebApp.

The WebApp on CodePen is here:

https://codepen.io/kobsterkobster/full/mdzWwBo

Editable here:

https://codepen.io/kobsterkobster/pen/mdzWwBo?editors=1111

It fetches the card library from the .json in this repo.


Roadmap:

1. ~~Create a Planechase deck~~ ✅
2. ~~Planeswalk function~~ ✅
3. ~~Shuffle function~~ ✅
4. ~~UI (card display)~~ ✅
5. ~~Migrate card library~~ ✅
6. Toggle for each card ✅
8. Virtual planar die to roll ✅
9. Saving custom lists
10. UI Optimization
   9.1. Full-screen card view
   9.2. Link to rulings
11. Special Cards
   10.1. Stairs to Infinity
   10.2. Interplanar Tunnel
   10.3. Norn's Seedcore
   10.4. Spatial Merging
   10.5. Pools of Becoming
   10.6. Aretopolis
   10.7. Chaotic Aether
   10.8. Furnace Layer



Next step:
Toggle for each card

How to implement:

1. Add a settings button (gear icon) to the HTML, which will be used to open the card selection menu.
2. Create a modal or a separate section in the HTML to display the card list, checkboxes, "Select All", "Deselect All", and "Save" button. Initially, this section should be hidden.
3. When the settings button is clicked, populate the card list with all Plane and Phenomenon cards from the card library, each with a corresponding checkbox. The list should be sorted by card type.
4. Implement the "Select All" and "Deselect All" buttons for both Plane and Phenomenon cards. These buttons should select or deselect all checkboxes within their respective card type sections.
5. When the "Save" button is clicked, gather all checked cards and re-initialize the Planar Deck with the selected cards. Close the card selection menu and return to the main app view.
6. Update the `initializeApp()` function to shuffle the deck after the selected cards have been loaded.

For the add-ons that will be implemented later:
1. Add event listeners to card names in the card selection menu. When clicked/tapped, display the card image in a small pop-up or overlay without leaving the page.
2. Implement cookies to store the user's custom settings in their browser. Load these settings when the app is initialized, and update the cookies whenever the user saves their custom settings.

By following these steps, you can implement the card toggle feature and its enhancements in an organized manner.
