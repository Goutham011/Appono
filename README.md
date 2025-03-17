Appono

Responsive Web Design

Description:
This project is a fully responsive website built using HTML, CSS, and JavaScript. The CSS file provided defines the layout, styling, and responsiveness of various sections, including navigation, home, about, card, review, contact, blog, and footer. The design leverages the Google Fonts library and incorporates custom color schemes, animations, and media queries for optimal viewing on different screen sizes.

Features:
- Fully responsive design
- Fixed navigation bar
- Hover effects on buttons and links
- Flexbox-based layout for cards and review sections
- Contact form with input field focus effects
- Media queries for mobile compatibility

Technologies Used
- HTML5
- CSS3
- JavaScript
- Google Fonts (Roboto)
- Folder Structure

project_folder/
│
├── index.html
├── style.css
├── script.js
├── images/
└── README.md

Setup Instructions

Clone the repository:
- git clone <repository_url>
- Open the project folder in your preferred code editor.
- Open index.html in your browser to view the website.

Customization:

To Change Colors:
- Open style.css file.
- Update the root variables:
:root{
  --blue:#0188df;
  --black:#444d53;
  --wight:#fff;
}

To Update Font:
Change the Google Font link in the CSS file:
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

Adding New Sections:
- Add HTML code in index.html.

- Define the respective CSS class in style.css.

Responsive Design

Desktop: Default layout with flex-based sections.

Tablet and Mobile: Adjusts using media queries for better usability.

Known Issues

None

Future Improvements

Adding dark mode toggle.

Integrating backend functionality for form submission.

Enhancing animations and transitions.

License

This project is licensed under the MIT License.

Author

Goutham sai Goparaju
