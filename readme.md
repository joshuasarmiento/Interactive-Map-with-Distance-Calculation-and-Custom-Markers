# Interactive Map with Distance Calculation and Custom Markers

This repository contains an HTML file that creates an interactive Google Maps interface with distance calculation and custom markers. The map allows users to visualize predefined locations, calculate routes between these locations, and display the distance and duration information for each route.

## Features

- **Map Setup**: The map is centered on a specific location with a custom zoom level and map styles applied for a unique visual appearance.
- **Markers and Pins**: A main marker and four fixed pins (labeled A, B, C, and D) are placed on the map with custom icons.
- **Distance Calculation and Display**: The code uses the Google Maps Directions Service to calculate the route between the main marker and a selected fixed pin. The calculated route is rendered on the map, and an InfoWindow displays the distance in kilometers and duration in minutes.
- **Map Interactions**: Users can click on the fixed pins to calculate and display the route between the main marker and the clicked pin. Clicking on the map away from any fixed pin or the main marker will clear the current route and recenter the map.
- **Customizations**: The InfoWindow appearance is customized with specific background colors and styles.

## Usage

1. Clone the repository or download the HTML file.
2. Open the HTML file in a web browser.
3. The interactive map will load, displaying the main marker and fixed pins.
4. Click on any of the fixed pins to calculate and display the route to the main marker, along with the distance and duration information.
5. Click on the map away from any fixed pin or the main marker to clear the current route and recenter the map.

## Prerequisites

This code relies on the Google Maps JavaScript API and requires an API key to function correctly. You'll need to replace the existing API key in the script source URL with your own valid API key.

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap&libraries=places,geometry" async defer></script>
