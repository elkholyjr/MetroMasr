# The Metro Navigation App is designed to provide users with accurate metro route directions, travel times, ticket prices, and the number of stations between two metro stations.
The app supports multiple metro lines and dynamically calculates and displays the best available routes. It features a clean, user-friendly interface for metro navigation.

![Screen_Recording_٢٠٢٤٠٩١٧_٠٠٣٧٢٣_metroMasr](https://github.com/user-attachments/assets/90b3c898-2f61-47cb-9de2-204e2e360f40)

# Features:
-Multi-line Metro Navigation: Supports navigation across various metro lines, including transitions between lines.
-Route Calculation: Provides multiple route options based on the start and end stations, sorted by the number of stations.
-Real-time Location Detection: Integrates real-time location detection to show nearby metro stations.
-Detailed Directions: Displays step-by-step instructions for each route, including line changes and directions.
-Dynamic UI: A swipeable card-based UI for navigating through different route options.

# Libraries and Tools Used:
-AirLocation: For accessing the user's current location.
-ViewPager2: To create a card-based UI for displaying multiple routes.
-YoYo Animation: For visual animations like shaking or rotating elements.
-AndroidX and ViewCompat: For handling window insets and edge-to-edge layouts.
-Geocoder: For converting addresses to geographic coordinates.

# Project Structure:
-Activity: Handles user interface elements, route display, and swipe navigation between routes.
-Metro Graph: A graph-based data structure representing the metro stations and routes.
-Route Calculation: Uses Depth-First Search (DFS) to find all possible routes between two stations and sorts them by the number of stations.
-UI Components: Dynamic UI components for displaying time, stations, and price based on selected routes.

# Challenges Faced:
-Fragment Lifecycle: Ensuring location permissions are granted correctly and restarting the fragment without restarting the entire app.
-Location Fetching: Ensuring accurate location detection and retrieving nearby stations in real-time, especially handling cases where permissions are initially denied or not granted correctly.
-Route Calculation: Implementing efficient algorithms to calculate multiple routes between stations while considering line transitions.
-Dynamic UI Management: Updating UI elements based on user interactions with ViewPager2 and ensuring the correct data is displayed for each route.

# Future Improvements:
-Offline Mode: Enable users to get route data without requiring an internet connection.
-Live Train Status: Integrating live train updates and schedules.
-Better Error Handling: Enhancing the user experience in cases where no route is found or location retrieval fails.

# App link:
https://www.amazon.com/gp/product/B0F4NXL714

https://drive.google.com/file/d/1y4UqNaxs1E_yC3rzFnsaamS6ex25my4S/view
