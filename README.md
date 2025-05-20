# Pokémon TCG Dex

A simple, single-page web application to search for and view Pokémon Trading Card Game (TCG) cards. Enter a Pokémon name or a Set name to browse cards, view their images, and get a direct link to their TCGplayer market page.

Try It Out Here!: https://pokemontcghub.me/
## Features

*   **Card Search:** Search for cards by Pokémon name (e.g., "Pikachu", "Charizard") or Set name (e.g., "Base Set", "Evolving Skies", "151").
*   **Card Display:** View results as a grid of card images.
*   **Card Details:** Displays the Set Name and Rarity below each card image.
*   **TCGplayer Link:** Provides a direct link button for each card to its corresponding page on TCGplayer.com for market prices and listings.
*   **Image Modal:** Click on any card image to view a larger version in a modal overlay.
*   **Pagination:** Navigate through search results using "Previous" and "Next" buttons.
*   **Loading Indicator:** Displays a Poké Ball themed spinner while fetching data.
*   **Responsive Design:** Adapts layout for different screen sizes (desktop, tablet, mobile).
*   **Visually Appealing:** Uses Pokémon-themed colors and fonts.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **CSS3:** Styling, layout, responsiveness, and animations.
    *   Google Fonts (`Press Start 2P`, `Lato`)
    *   CSS Variables for theming
*   **Vanilla JavaScript (ES6+):**
    *   Fetching data from the API (`fetch` API, `async/await`).
    *   DOM manipulation to display cards, loader, pagination, and modal.
    *   Handling user input and events.
    *   AbortController for cancelling pending fetch requests.
*   **Pokécard TCG API:** ([pokemontcg.io](https://pokemontcg.io/)) - Provides the card data, images, and TCGplayer links.

## API Credits

This application relies heavily on the fantastic **Pokémon TCG API** provided by [pokemontcg.io](https://pokemontcg.io/). Please refer to their documentation for API usage details and terms.

## Author

*   **Amadou** - *Initial work*

## License

This project is licensed under the MIT License - feel free to use and modify!
