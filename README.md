Project done within the *HTML and CSS* GDU course.
the goal was to create, from a [given presentation](https://github.com/TheRealPikevchu/Atelier-HTML-CSS/blob/master/images/landingpage.jpg), a static and responsive website for the Agenc*eco* company, a factice website creating company that doesn't even do it's own website.

# Files management
This project files are organized as follow :
```
Atelier-HTML-CSS/
|-- index.html
|-- css/
|   |-- colors.css
|   |-- font.css
|   |-- form.css
|   |-- index.css
|   |-- layout.css
|   |-- style.css
|-- images/
|   |-- image1.jpg
|   |-- image2.jpg
|   ...
|-- scss/
|   |-- colors.scss
|   |-- font.scss
|   |-- form.scss
|   |-- index.scss
|   |-- layout.scss
|   |-- style.scss
|-- README.md
```
## index.html
[index.html](https://github.com/TheRealPikevchu/Atelier-HTML-CSS/blob/master/index.html) is the base html file of this project, and contain every element of the web page.
It is split within sections :
- Menu
- Landing
- Team
- Statistics
- Services
- Contact 
- About
- Gallery
- General Info
- Copyrights and Social Networks

### Menu
A simple navigation menu, always displayed when navigating throught the page.
> [!WARNING]
> The menu is hidden when using a smartphone in portrait to ease the navigation.

### Landing
The landing section of the website.
Clicking on the landing section redirect to a [360 photo](https://balades360.simois.ch/vtour-FTU/tour.html).
>[!NOTE]
>It always takes the full viewport to make an impressive landing experience.
A transition effect is present when overing the section on large and medium devices, but is removed from small devices i.e. smartphone to prevent touch screen interactions issues.

### Team & Other sections
Other sections always use the same parttern : presenting content related to the section.
Most elements will switch to a column presentation when using a small portrait device.

### General Info
This section presents information about Agen*eco*, and will only display the most important ones on a small portrait device, namely the phone number and address.

## Images
This folder contains every image type resource used in this project.

## CSS and SCSS
As this project use SCSS, style documents are splits in two folders:
* SCSS : working folder where all style documents are manipulated
* CSS : all compiled SCSS documents go here (autogenerated)

>[!NOTE]
>As CSS docs are autogenerated, we will only reference the scss files here

### Index
[Index.scss](https://github.com/TheRealPikevchu/Atelier-HTML-CSS/blob/master/scss/index.scss) is the main styling document of this project, and style the landing (and only) page of the website.
All unique styling effect of the landing page are implemented here, parted into each specific section.
Index rely ond Style to retrieve common styling elements.

### Style
[Style.scss](https://github.com/TheRealPikevchu/Atelier-HTML-CSS/blob/master/scss/style.scss) is simply used as a document referencing all other style documents of this project.

### Layout
[Layout.scss](https://github.com/TheRealPikevchu/Atelier-HTML-CSS/blob/master/scss/layout.scss) contain all reusable layout elements that are proper to Agen*eco* style, including titles management, links, highlights, and flex layouts.

### Colors, Font and Form
Those three files contains :
- Colors : every color rules and the default swatch of the project
- Font : integration of the font [Poppins](https://fonts.google.com/specimen/Poppins)
- Form : styling for forms

# Deployment
The final website [atelier-html-css.vercel.app](https://atelier-html-css.vercel.app/) is hosted and deployed using [vercel.com](https://vercel.com/).