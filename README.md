# Pixelate.css

Pixelate.css is a lightweight, Sass-based CSS framework that provides a clean, consistent, and customizable UI foundation. It includes themed styles for common HTML elements and utility classes for faster layout and styling.

## Team Members
- Antonio Fernando (Team Leader)
- Riyansi Donga
- Mihir Patel
- Edward Owusu Boafo

## Features
- Sass partials structure (`scss/` folder)
- Customizable theme using Sass variables (`scss/_variables.scss`)
- Themed elements: typography, buttons, forms, tables
- Utility classes: spacing, typography helpers, colors, borders

## Installation
Link the compiled CSS file in your HTML:

```html
<link rel="stylesheet" href="dist/pixelate.css">
```
## Usage

## Typography
```html
<h1>Pixelate Heading</h1>
<p>This is a paragraph using the base typography.</p>

<ul>
  <li>List item one</li>
  <li>List item two</li>
</ul>
```
## Buttons
```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
```

## Forms
```html
<form>
  <label for="name">Name</label>
  <input id="name" type="text" placeholder="Enter your name" />

  <label for="email">Email</label>
  <input id="email" type="email" placeholder="Enter your email" />

  <label for="message">Message</label>
  <textarea id="message" rows="4" placeholder="Type your message"></textarea>

  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

## Tables
```html
<table class="table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
      <th>Role</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Antonio Fernando</td>
      <td>fern0225@algonquinlive.com</td>
      <td>Team Leader</td>
    </tr>
    <tr>
      <td>Mihir Patel</td>
      <td>pate1568@algonquinlive.com</td>
      <td>Team Member</td>
    </tr>
    <tr>
      <td>Riyansi Donga</td>
      <td>dong0083@algonquinlive.com</td>
      <td>Team Member</td>
    </tr>
    <tr>
      <td>Edward Owusu Boafo</td>
      <td>boaf0002@algonquinlive.com</td>
      <td>Team Member</td>
    </tr>
  </tbody>
</table>
```


## Customization
Edit theme variables in:

`scss/_variables.scss`

Then rebuild the compiled CSS.

## Build / Compile

### One-time build
```bash
sass scss/main.scss dist/pixelate.css
```


