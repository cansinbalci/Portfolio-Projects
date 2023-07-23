# Portfolio-Projects
This repository houses a compilation of my projects, showcasing my skills and creativity as a developer.

01 **Portfolio Project - Pricing Page**

In this front-end development project, I created a simple and attractive pricing page using HTML and CSS. The goal was to showcase my skills in CSS styling, responsive design, and layout structuring. Below are the key features and concepts I applied in the project:

**1. Box Sizing and Font Styling:**
- I used the `box-sizing: border-box;` property to ensure that padding and border are included in the element's total width and height calculation, leading to a more predictable layout.
- For a clean and modern typography, I selected the 'Open Sans' font from Google Fonts and applied it to the entire HTML document using `font-family: 'Open Sans', sans-serif;`.

**2. Responsive Design and Flexbox:**
- To achieve a responsive layout, I employed `display: flex;` along with `justify-content: center;` and `align-items: center;` on the `body` element, making the pricing panel centered horizontally and vertically on all devices.
- The `.panel` class is set to display as a flex container with a column direction for smaller screens and row direction for larger screens (`@media` query).

**3. Pricing Plan Cards:**
- Each pricing plan is represented by a card with a white background, rounded corners (`border-radius: 10px;`), and a subtle bottom border (`border-bottom: 1px solid #e1f1ff;`).
- The pricing plan cards have a maximum width of 960px (`max-width: 960px;`) to prevent excessive stretching on larger screens.

**4. Styling and Layout:**
- Pricing plan titles are styled with uppercase text (`text-transform: uppercase;`) for a bold and consistent appearance.
- Pricing features are presented in a list format, with each feature separated by a top border (`border-top: 1px solid #e1f1ff;`) to create a clear visual distinction.
- The pricing amount is highlighted with a larger font size (`font-size: 32px;`) and bold weight (`font-weight: 700;`) to draw attention.

**5. Call-to-Action Buttons:**
- Call-to-action buttons are styled with a light blue border and rounded corners (`border: 1px solid #9dd1ff; border-radius: 10px;`).
- On hover or focus, the buttons change their background color slightly (`transition: background-color 200ms ease-in-out;`), providing visual feedback to users.

**6. Featured Pricing Plan:**
- The featured pricing plan is differentiated with a unique blue background and white text (`background-color: #269aff; color: white;`).
- When hovered or focused, the featured plan's button changes to a darker shade of blue (`background-color: #269aff; color: white;`), enhancing its prominence.

**7. Media Query for Responsive Design:**
- For screens with a minimum width of 900px, I used a `@media` query to adjust the layout to a side-by-side arrangement of the pricing plan cards.

By creating this pricing page project, I demonstrated my proficiency in using HTML and CSS to craft visually appealing and responsive web pages. The combination of modern styling techniques, layout structuring, and responsive design ensures an optimal user experience on various devices and screen sizes. I am excited to continue honing my front-end development skills and taking on new challenges in the web development world.
