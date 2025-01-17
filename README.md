## Page Purpose:
This page is designed to provide seamless navigation assistance for staff and patients within Nairobi Hospital. Using a combination of QR codes and interactive maps, the page will help users locate specific buildings, floors, and offices within the hospital's premises.

<br>

## Core Functionalities and Workflow:
1. QR Code for Accessing the Map
	○ Scan QR Code: Provide strategically placed QR codes throughout the hospital premises. Users scan the code using their smartphone to access the navigation page.
	○ Geofence Validation: The QR code will only work within Nairobi Hospital's boundaries. This can be enforced using geofencing technologies, ensuring users are on-site before accessing the navigation map.
2. User Location Detection:
	○ Upon accessing the page, the user's current position within the hospital premises is displayed on the map using GPS or Wi-Fi-based location tracking.
	○ Privacy Compliance: Notify the user that their location data is temporarily accessed for navigation purposes.
3. Selecting the Desired Destination:
	○ Users can select their destination from a dropdown list or an interactive map. Destinations include buildings, floors, and specific offices.
	○ Search Functionality: Add a search bar for easy identification of locations, especially for first-time users.
4. Calculating and Displaying the Shortest Route:
	○ Once the destination is selected, the system calculates the shortest path to the chosen building using pathfinding algorithms (e.g., Dijkstra's algorithm or A*).
	○ Display turn-by-turn directions visually on the map and provide optional text or voice navigation.
5. Navigation Inside the Building:
	○ When the user reaches the building, allow them to choose the desired floor.
	○ Filter the map to display only the selected floor.
	○ Highlight offices on the chosen floor and provide detailed information (e.g., department names, room numbers).
6. Final Navigation to the Office:
	○ After selecting the office, the map calculates and displays the shortest route from the user's current position to the office.
	○ Provide dynamic updates in case the user takes a wrong turn or changes location.

<br>

 ## Additional Steps and Enhancements:
1. Backend Infrastructure:
	○ Develop a geospatial database with detailed mappings of the hospital's layout, including buildings, floors, pathways, and rooms.
	○ Integrate APIs for location services, such as Google Maps or custom indoor navigation solutions.
2. User Authentication (Optional):
	○ Allow staff or patients to log in for personalized navigation, such as pre-booked appointment locations or staff-only areas.
3. Accessibility Features:
	○ Add accessibility-friendly navigation for individuals with mobility impairments (e.g., wheelchair-accessible paths).
	○ Offer text-to-speech functionality for visually impaired users.
4. Error Handling:
	○ Provide clear error messages if the QR code is scanned outside the hospital boundaries or if location tracking is disabled.
	○ Allow manual entry of the starting position for users with older devices that may not support GPS or Wi-Fi-based location tracking.
5. Multilingual Support:
	○ Include language options to accommodate diverse patients and staff.
6. Feedback Mechanism:
	○ Offer a feedback option so users can report inaccuracies in the navigation system or suggest improvements.
7. Maintenance and Updates:
	○ Regularly update the map and office listings to reflect changes in the hospital layout or department locations.
	○ Test the geofencing and QR code functionality periodically to ensure seamless user experience.
