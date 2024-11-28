# border-spinning-animation 
Creates a visually appealing card element with a spinning animated border effect using modern CSS techniques like custom properties, @property, and conic-gradient.

Key Features: Font and Layout:

The @import rule integrates the "Poppins" font from Google Fonts, giving the text a clean, modern appearance. Global styles ensure a consistent layout with zero margins, padding, and smooth scrolling enabled. Dark Theme:

The background of the page (body) is set to black (#000), creating a dark theme with contrast for the glowing card effect. The card itself has a deep blue background (rgb(1, 22, 38)) with white text for readability. Card Design:

The card (.card) is centered vertically and horizontally on the page using Flexbox. Rounded corners (border-radius: 10px) and internal padding make the card visually pleasing and easy to read. Spinning Border Animation:

The .card::after pseudo-element is used to create the animated border. A conic-gradient background generates the spinning effect, starting from the custom property --angle. The pseudo-element is slightly larger than the card itself (calc(100% + 20px)) to simulate a glowing border. Custom Property and Animation:

The --angle property is defined using the @property rule, specifying its syntax (), default value (0deg), and non-inheriting behavior. The @keyframes rule animates the --angle property from 0deg to 360deg, creating a smooth, continuous rotation. Smooth Rotation Effect:

The animation property on .card::after applies the spinning effect in a linear manner, looping infinitely with a duration of 3 seconds.
