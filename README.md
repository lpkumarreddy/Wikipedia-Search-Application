# Wikipedia Search Application

A dynamic web application that allows users to search Wikipedia articles in real-time using a clean and intuitive interface.

## Features

- **Real-time Search**: Get instant Wikipedia search results as you type and press Enter
- **Dynamic Loading**: Smooth loading transitions with a spinner indicator
- **Responsive Design**: Clean and mobile-friendly interface
- **Rich Results**: Each result includes:
  - Article title with direct link
  - Full URL to the article
  - Brief description of the content

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 4.5.2
- jQuery 3.5.1
- Popper.js
- Google Fonts (Roboto)

## Live Demo

The application interacts with the `apis.ccbp.in/wiki-search` endpoint to fetch Wikipedia search results.

## Setup and Installation

1. Clone the repository
2. Open `index.html` in your browser
3. No additional setup required as the project uses CDN links for all dependencies

## How It Works

1. User enters a search term in the input field
2. Upon pressing Enter:
   - The spinner is displayed
   - Previous results are cleared
   - A GET request is made to the Wikipedia search API
   - Results are dynamically rendered on the page

## Code Structure

### HTML
- Clean, semantic markup
- Bootstrap integration for responsive design
- Search input field
- Results container
- Loading spinner

### CSS
- Custom styling for search components
- Responsive design elements
- Google Fonts integration
- Consistent color scheme and spacing

### JavaScript
- Event listeners for user input
- Async API calls using Fetch API
- Dynamic DOM manipulation
- Error handling
- Results rendering logic

## API Integration

The application uses a GET request to fetch search results:
```javascript
fetch('https://apis.ccbp.in/wiki-search?search=' + userSearch, {
    method: 'GET'
})
```

## Styling Details

- Font: Roboto (Google Fonts)
- Color Scheme:
  - Border: #d5cdcd
  - URL Color: #006621
  - Description Text: #444444
- Responsive padding and margins
- Smooth transitions

## Features Breakdown

### Search Input
- Placeholder text for user guidance
- Real-time input handling
- Enter key detection for search triggering

### Results Display
- Title with clickable link
- URL display
- Description paragraph
- Proper spacing between results

### Loading State
- Bootstrap spinner
- Show/hide functionality
- Smooth transitions

## Future Enhancements

Potential improvements that could be added:

1. Autocomplete suggestions
2. Search history
3. Advanced search filters
4. Category-based searching
5. Save favorite articles
6. Share functionality
7. Dark mode toggle

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is open source and available under the MIT License.

MIT License

Copyright (c) 2025 lpkumarreddy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

- Wikipedia API for providing search functionality
- Bootstrap team for the responsive design framework
- CCBP for API endpoint hosting
