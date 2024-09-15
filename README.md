# Sign-Up Form

This project is a simple sign-up form created using HTML and CSS. The layout is designed to include a logo, a brief description, and a sign-up form with various input fields such as name, email, phone number, and password. The form also has validation and visual feedback on invalid inputs. This README provides an overview of the project, including the structure, features, and how to run it locally.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contribution](#contribution)
- [Acknowledgement](#acknowledgement)

## Project Overview

The project consists of a two-column layout where the left column displays a logo and the right column contains a sign-up form. The purpose of this form is to collect user information like first name, last name, email, phone number, and password. The design is responsive and uses Flexbox to handle layout arrangements.

## Features

- **Responsive Design**: Uses Flexbox to create a responsive two-column layout.
- **Form Validation**: Includes validation for required fields, email format, and matching passwords.
- **Visual Feedback**:
  - Inputs display a red border if they are invalid.
  - Focused inputs display a blue border with a subtle shadow.
- **Custom Fonts**: Uses a custom "Norse-Bold" font for the logo.

## Project Structure

```bash
Project Folder
│
├── font/              # Font assets folder
│   └── Norse-Bold.otf # Custom font file
├── image/             # Image assets folder
│   ├── green-leaves.jpg  # Background image for logo section
│   └── odin-logo.png  # Logo image
├── index.html         # Main HTML structure
├── README.md          # Project's README
└── style.css          # Styling for the page
```

## Getting Started

1. Clone this repository or download the project files to your local machine.

```bash
git clone git@github.com:Esther-Omono/sign-up-form.git
```

2. Navigate to the project folder.

```bash
cd sign-up-form
```

3. Open the index.html file in your web browser to see the form in action.

### Running on a Local Server

If you prefer to run the project on a local development server, you can use an extension like Live Server for Visual Studio Code or a similar tool.

## Contribution

Contributions are welcome! If you have any suggestions or improvements, feel free to fork the repository and submit a pull request.

## Acknowledgement

This project was inspired by and developed as part of [The Odin Project](https://www.theodinproject.com/), an open-source curriculum for learning web development.
