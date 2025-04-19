# Bar Chart Visualization Project

## Overview
This project is a data visualization application that displays US GDP data in an interactive bar chart using D3.js. The project fulfills the requirements set by freeCodeCamp's Data Visualization certification.

## Features
- Interactive bar chart visualizing US GDP data over time
- Responsive design that adapts to different screen sizes
- Hover tooltips displaying detailed information for each data point
- Properly scaled axes with tick marks
- Compliant with all 13 user stories from freeCodeCamp

## User Stories Implemented
1. Chart with title (id="title")
2. X-axis (id="x-axis")
3. Y-axis (id="y-axis")
4. Multiple tick labels on both axes (class="tick")
5. Rect elements for each data point (class="bar")
6. Data attributes (data-date and data-gdp) for each bar
7. Correct order of data-date properties
8. Correct order of data-gdp properties
9. Accurate height representation of GDP values
10. Proper alignment of bars with x-axis values
11. Proper alignment of bars with y-axis values
12. Interactive tooltip (id="tooltip") on hover
13. Tooltip with matching data-date property

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- D3.js (v7 or higher)

## Data Source
The project uses GDP data provided by freeCodeCamp:
```
https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json
```

## Installation
No installation is required. Simply open the `index.html` file in a modern web browser.

## Usage
1. Open the application in your browser
2. Hover over any bar to see detailed GDP information for that time period
3. The tooltip will display the date and GDP value

## Testing
To verify all requirements are met, include the freeCodeCamp test script:
```html
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```

## Customization
You can easily customize:
- Color scheme by modifying the CSS
- Chart dimensions by adjusting the D3.js configuration
- Tooltip styling in the CSS

## License
This project is open source and available under the MIT License.
