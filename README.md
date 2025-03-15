Header Component
The Header component is a simple navigation bar designed for use in a React web application. It displays a list of navigation items and highlights the active item. The header supports theming (light and dark) and includes a flexible layout.

Features
Dynamic Navigation: The navigation items are generated dynamically from an array of objects.
Active Tab Highlighting: The active tab is highlighted with a different background color and text color.
Theming Support: The header style changes based on the current theme (light or dark).
Responsive Design: The layout is flexible and adapts to different screen sizes.

Props
activeTab (string)
Type: string
Description: The ID of the currently active tab.
Example: "home", "about", "todo", "profile", "counter"

Customization
You can customize the navItems array to add more navigation items or change the text/ID of existing items.
Modify the headerStyle and navStyle objects to change the appearance of the header.
Add more functionality, such as a theme toggle button or a logo, by expanding the component.
License
This project is open-source and available under the MIT License.
