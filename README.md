![image](https://github.com/Zaps6000/community-landing/assets/122732007/baaf7fa8-af2c-4061-84ba-989e324dc6fe)
# Community-Landing: HTML5 Landing Page for FiveM RP Community
Discord: [Zaps](https://discord.gg/cfxdev)
## Description

This project is an HTML5 landing page designed for FiveM Role-Playing communities. It's built with HTML5, CSS3, and uses JavaScript and jQuery for interactivity. It also features a preloader and cookie consent banner. This landing page is a perfect starting point for communities who want to have an online presence.

## Features

- Responsive Design
- Cookie Consent Banner
- Dynamic Preloader
- Section for features, contacts, and other information
- Easy customization

## Prerequisites

Make sure you have the following installed:

- A text editor like Visual Studio Code, Sublime Text, or Atom
- Basic understanding of HTML, CSS, and JavaScript

## Installation

1. Clone the repository or download the zip file and extract it.
2. Open the `index.html` file in your text editor of choice.
3. Start editing as per your requirements.

### Header

Find the header tag and replace the title text:

```html
<h1>PutYourHandsUP RP</h1>
```

### Navigation Links

Look for the `nav` section and update the navigation links:

```
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Departments</a>
<a href="#">Contact</a>
<a href="#">Discord</a>
```

### Welcome Section

Navigate to the `.container` section and edit the text and buttons:

```html
<h2>Welcome to PutYourHandsUP !</h2>
<p>This is a place where you can immerse yourself in a role-playing experience.</p>
```

### Server IP

Replace the placeholder `your_server_ip_here` in the JavaScript with your actual server IP.

```javascript
var serverIP = 'your_server_ip_here';
```

### Background Image

Replace the `background-image` URL in the `.background` class to change the background:

```css
.background {
    background-image: url('https://your-image-url-here.jpg');
}
```

## Contributing

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License

Distributed under the MIT License. See `LICENSE` for more information.
