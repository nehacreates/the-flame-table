# The Flame Table – Gastronomic Luxury HTML Template Documentation

The Flame Table is a premium, high-end, responsive HTML template built with HTML5, CSS3, JavaScript, Bootstrap 5, Font Awesome, and Google Fonts, specifically crafted for upscale restaurants, steakhouses, fine dining venues, and culinary hospitality brands.


## 1. Package Structure


the-flame-table/
│
├── index.html          # Homepage with dynamic hero carousel and luxury sections
├── menu.html           # Menu showcase page with split-row layouts
├── about.html          # Our story and brand philosophy page
├── gallery.html        # Photography gallery and reviews page
├── booking.html        # Table reservation page
├── contact.html        # Contact us page with interactive form
│
├── css/
│   ├── style.css       # Main global and homepage stylesheet
│   └── menu.css        # Menu page specific stylesheet
│
├── images/             # Restaurant imagery, background slides, and brand logos
│   └── logo_restaurent.png # Brand logo
│
└── documentation.md    # Official documentation file

    Note: Keep the original filenames unchanged because the navigation links and cross-page references rely on these exact filenames.


## 2. Installation and Setup

    Extract the downloaded project ZIP file.

    Open the extracted project folder in your code editor (such as Visual Studio Code).

    Keep the original folder structure and filenames unchanged.

    Open index.html in any modern browser, such as Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari.

    Navigate between the website pages using the professional navbar or mobile slide-in drawer.

    Local Development: Open the project folder in Visual Studio Code and run it using the Live Server extension.

    Internet Requirement: Bootstrap, Font Awesome, and Google Fonts are loaded through CDN links. An active internet connection is required to load these external resources correctly.


## 3. Configuration and Customization

The Flame Table is a static HTML template and does not require a separate backend configuration file.

A. Page Content

Open the relevant HTML file in a code editor to update page content, headings, menu items, pricing, and other interface elements.

    Edit index.html to customize the homepage, luxury moments, and philosophy of fire sections.

    Edit menu.html to customize signature grills, oceanic delicacies, artisanal pastas, and craft cocktails.

    Edit booking.html to customize table reservation forms.

    Edit contact.html to customize location details and contact info.

B. Brand Logo

The logo image is located at: images/logo_restaurent.png

    To replace the logo, add your image to the images folder and keep the filename logo_restaurent.png.

    If you use a different filename or location, update the corresponding image path in the HTML files.

C. Styles and Fonts

The main custom stylesheets are style.css and menu.css. Edit these files to customize:

    Colors and gold accent themes (#dfb24e)

    Typography and font sizes

    Spacing and layout

    Buttons, cards, and glassmorphism UI elements

    Responsive styling for mobile and desktop

    The template uses Playfair Display and Plus Jakarta Sans from Google Fonts.

D. Booking and Contact Forms

The booking and contact forms feature interactive success notifications and validation. Relevant element IDs and classes can be customized directly within the respective HTML files.

To connect forms to a live backend (PHP/Email service), update the onsubmit attributes or bind them via AJAX to your mail script.

E. JavaScript

The template includes built-in scripts for preloader fade-outs, navbar scroll effects, hero carousel synchronization, and horizontal Guest Ledger drag/arrow controls. Use script blocks within the HTML files or external custom scripts to modify or extend interactions.

    Tip: When changing form element IDs or classes, check whether the corresponding selectors are also used in inline scripts and update them as needed.

F. Navigation

The pages use a unified responsive navbar with numbered links (01 to 06) and a mobile slide-in drawer. To change navigation labels or destinations, edit the corresponding navbar markup in the relevant HTML files.

The navigation uses these exact page filenames:

    index.html

    menu.html

    booking.html

    about.html

    gallery.html

    contact.html

Keep the filenames and relative paths consistent to ensure the navigation links work correctly.


## 4. External Dependencies

Dependency        Version / Resource    Purpose
Bootstrap         5.3.0                 Responsive layout and UI components
Font Awesome      6.5.1                 Icons
Google Fonts      Playfair Display & Plus Jakarta Sans    Typography

These resources are loaded through CDN links in the HTML files. If you change a dependency version, update the relevant CDN URL.


## 5. Backend Integration

The Flame Table is a frontend UI template. It does not include a backend server or database configuration. To implement live application functionality (such as table booking management, newsletter signups, or contact form submissions), you can connect the frontend to your own backend using technologies such as Node.js, PHP, Python, or another suitable framework.

Possible integrations include:

    Table reservation and booking calendar management

    Newsletter subscriber database storage

    Contact form email delivery

    Note: Backend integration requires additional development. Configure your form handlers and API requests and connect them to your backend endpoints as needed.


## 6. Troubleshooting

Page or navigation link does not open

    Confirm that the relevant HTML file exists.

    Check that its filename matches the link exactly.

    Keep all HTML files in the same root project folder unless you update the relative paths.

Logo does not appear

    Confirm that the image exists at images/logo_restaurent.png.

    Check the image path in the relevant HTML file.

Styles or icons do not load

    Confirm that style.css or menu.css exists in the css/ folder.

    Check your internet connection for CDN-hosted resources.

    Verify the dependency URLs in the HTML files.

Interactive elements (Carousel, Ledger, Preloader) do not work

    Check that the HTML files reference the correct script paths and Bootstrap bundle.

    Inspect the browser developer console for JavaScript errors.