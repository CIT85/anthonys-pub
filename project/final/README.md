# My Topic
My topic is about pets and how they help us during times of stress and anxiety, bringing more happiness to our lives. I chose this topic not only because I love animals, but also to explore how they can have a positive impact on people’s lives. One thing I’ve noticed personally, and across the internet, is that people who own pets tend to be happier overall. It might sound a bit surprising, but the proof is all over social media. People love sharing posts, photos, and videos of their pets, and their posts often show them looking happier and having a more positive mindset.

# My Content
For my website, I will have three sections that will correspond with my topic.

Section 1: This section will be an introduction to the website and will include a short paragraph about my topic. The paragraph won’t be too detailed, but it will give you a general understanding of what the page is about.

Section 2: This section will have 2-3 paragraphs that explain my topic in more detail. It will dive deeper into how pets can affect us, followed by a list of facts in an unordered list.

- Paragraph One: How pets can improve your lifestyle.
- Paragraph Two: How pets can improve your health.
- Paragraph Three: What to avoid.
Section 3: This section will include a table listing different types of pets and how compatible they are with different people.

# My Text
I want to keep my text simple and easy to read. I will use legible fonts to ensure everyone can easily understand the content. Even with CSS, complicated fonts can still make reading hard. I plan to use:

- Sans Serif
- Times New Roman
- Roboto


# CSS Overview

1. Layout & Structure
Flexbox & Grid: These are used to organize content across the page. Flexbox is great for things like the navigation bar, while Grid keeps everything aligned neatly.
Containers: The .container class is used to keep content centered and ensure that nothing gets too spread out or too cramped.
2. Typography
Fonts: We use modern, easy-to-read fonts. Sizes are adjusted for different sections to make sure the text is clear and readable.
Text Alignment: For certain sections like headings, I used text-align: center to make sure the text is centered and looks neat. Other sections are aligned to the left or justified based on the content’s importance.
Text Decoration: Links get an underline with text-decoration: underline on hover, making it clear they're clickable. This adds a little interactivity to the site.
3. Colors
Color Palette: A simple and consistent color scheme is applied throughout the site, with a main color and a few accent colors to give the site some variety while keeping it visually balanced.
Backgrounds & Text: Backgrounds change depending on the section, while text color adjusts to make sure everything is easy to read.
4. Navigation Styling
Nav Bar: The navigation bar uses Flexbox to align links horizontally, and when you hover over them, they change color, letting users know where they are on the site.
Links: Links are styled to stand out with bold colors, and the text decoration (underlining) is added when hovered to give a nice visual effect.
5. Images & Media
Responsive Images: Images adjust their size depending on the screen size, ensuring they always look good whether you’re on a phone or laptop.
Height & Width: I used specific height and width properties to make sure the images and other elements fit within the layout properly, without overflowing or looking awkward.
6. Buttons & Interactive Elements
Button Styling: Buttons are large and have a color change effect on hover, letting users know they’re interactive.
Hover Effects: Links and buttons use :hover to change their color or add a subtle movement when you hover over them, giving the site a more interactive feel.
7. Spacing & Alignment
Margins & Padding: I used margin and padding to control the space around and inside elements. This helps keep everything organized, with proper spacing between sections, making the content feel balanced and not too cramped.
Justify Content: To ensure everything aligns properly, I used justify-content (with values like center, space-between, and space-around) in Flexbox to space out elements evenly and make sure they’re positioned just right.
8. Borders
Borders on Elements: Some sections and elements have borders around them to make them stand out more. For example, images and cards might have a thin border to define their edges, which adds a nice touch to the design.
Border Radius: To make borders look softer, some elements have a border-radius applied to give them rounded corners, making the site feel more friendly and modern.
9. List Styles
List Styling: Lists, such as the navigation links or items in an article, have been styled to remove the default bullet points with list-style: none. This makes the lists cleaner and ensures that the items are aligned properly.
10. Layout Size Control
Height & Width Adjustments: I used specific height and width values to control how big or small elements are. This ensures images, containers, and other elements fit properly without getting too stretched or squished.
Flexible Sizes: Some elements are set to adjust their size based on the screen size or the container's size, using percentages or relative units. This makes sure the layout is responsive.

# Media Queries
1. For screens up to 480px (small mobile devices):
## Font size and layout adjustments:
- The body font size is reduced to 12px, optimizing readability for very small screens like older phones or compact devices.
- The body is set to take full width and auto height to ensure that it scales properly within the viewport, with no margin (default margin is removed).
- The display is set to block, ensuring that elements like text, sections, and images display vertically.
Header and navigation:
The header font size is reduced to 30px to make it suitable for small screens.
- The navigation is displayed in a column layout using flex-direction: column, stacking the menu items vertically to avoid a horizontal overflow.
- Links in navigation are set to a smaller font size (15px) for better scaling on small screens.
Image and section adjustments:
Images are scaled to 70% of their container size, ensuring they are visible but don't take up too much space.
- Sections and articles are given padding of 2px and a full width (100%) to ensure content fits neatly in the limited space.
Container and footer:
- The .container class has padding set to 10px and ensures it spans the full width of the screen.
- The footer content is centered and stacked vertically using flex-direction: column.
2. For screens between 481px and 768px (medium mobile to small tablet devices):
## Font and layout:
- The font size for the body increases to 20px to improve readability on slightly larger screens (small tablets or larger phones).
- The body still takes up the full width, and the layout remains block-level with no default margins.
## Images:
- Images now scale with a max-width: 100%, ensuring they are responsive and can resize with the screen width, without overflowing.
## Navigation and section:
- The header font remains at 30px, but the navigation links' font size adjusts slightly to make them more legible (15px).
- Section and article elements are adjusted to have padding of 2px with 100% width.
Container and inputs:
- Containers maintain a width of 100%, but padding is set to 10px to give some spacing without taking up too much space.
- The .inputs container still uses a full width and has padding of 10px to ensure form fields fit within the screen width.
3. For screens between 769px and 1024px (tablets and small desktops):
Font and layout:
- The body text remains responsive, adjusting the font size to 11px for smaller sections within the screen size.
The sections and articles maintain their width at 100%, with padding of 2px to ensure readability.
Navigation and links:
Links are kept at 19px for readability across devices of this size, making them accessible without being overwhelming.
## Images:
- The images remain responsive, ensuring they fit their container width with no set height, allowing them to scale proportionally.
## Header and footer:
- The header font size is set to 30px to ensure it remains clear and readable on devices like tablets.
Footer settings are adjusted to center the content with padding of 10px, maintaining readability.
4. For screens between 1025px and 1200px (larger desktops):
## Font and layout:
- The font size for general body content and headings is increased significantly to make content easy to read on larger screens (1.5rem for body text, 60px for headers).
- Sections, articles, and list items are all adjusted to ensure the text appears larger and better spaced for these medium-to-large desktop screens.
## Header and navigation:
-Header font sizes are increased to 60px to fill the space and make titles stand out.
- Navigation font sizes (for links) are set to 13px, giving a balance between large and small devices.
## Images and sections:
- Image sizes increase to 40% width and height, making them more prominent on large screens.
Footer:
The footer font is adjusted, and content is kept centered and padded for a clean layout.
Links in the footer are also set to 13px for consistency with navigation.
5. For screens over 1200px (extra-large desktops):
## Font and layout:
- The body text increases again to 3.5rem to make it large and clear on very wide screens like extra-large desktops or TVs.
- Sections, paragraphs, and other text content increase to 24px for paragraphs and headers to maintain a clear structure and make use of the available screen space.
## Images:
- The image size is set to 40% of the container's width and height, keeping it visually appropriate for large screens without overwhelming the layout.
Container adjustments:
- The .inputs container and form fields maintain readability with larger font sizes (20px) and adjusted padding.
Navigation and links:
Navigation font size stays at 14px for readability, ensuring it doesn't take up too much space in the header.
Links in the footer are similarly adjusted to 14px for consistency.