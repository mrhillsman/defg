# Desktop Entry File Generator

A simple, single-page web application to create `.desktop` files for Linux applications, based on the FreeDesktop.org specification.

[**Live Demo Hosted on GitHub Pages**](https://mrhillsman.github.io/defg)  
*(Replace `your-username` with your actual GitHub username)*

![Screenshot of the Desktop File Generator](https://github.com/user-attachments/assets/f24a1d29-45bc-434c-bf27-924444b09cc5)

## About This Project

This is a lightweight, client-side tool built with HTML and Tailwind CSS. It provides a user-friendly form to generate `.desktop` file content in real-time. You can easily fill in the values, copy the result, or download the final `.desktop` file.

### AI Genesis

This entire application was generated through a conversation with Google's AI, **Gemini (2.5 Pro)**. The process was iterative, showcasing the collaborative potential between humans and AI for software development.

The development conversation included the following steps:

1. **Initial Prompt:** The request was to create a single-page web app to generate `.desktop` files based on the official specification.

2. **First Version:** Gemini provided the initial, fully functional HTML file containing the most common desktop entry fields.

3. **Feature Request:** Upon review, a request was made to include the `Path` and `Keywords` fields from the spec for more complete functionality.

4. **Second Version:** Gemini updated the code to include the requested fields in the form and the output logic.

5. **Deployment & Documentation:** Gemini then provided instructions for deploying the application to GitHub Pages and generated this README file.

This project serves as a practical example of AI-assisted development.

## Features

* **Live Preview:** See the generated `.desktop` file content update in real-time as you type.

* **Comprehensive Fields:** Includes core fields (`Name`, `Exec`, `Icon`) and common optional fields (`Comment`, `Path`, `Keywords`, `Categories`, etc.).

* **Simple Toggles:** Easily set boolean values like `Terminal` and `StartupNotify`.

* **Autostart Support:** Includes fields for enabling and delaying application autostart.

* **Copy & Download:** One-click buttons to copy the content to your clipboard or download the `.desktop` file.

* **No Backend Required:** Runs entirely in your browser. No data is sent to a server.

## How to Use

1. **Open the application** in your web browser via the [live demo link](https://mrhillsman.github.io/defg).

2. **Fill in the fields** on the left-hand form. The `Name` and `Exec` fields are the most important.

3. **Review the output** on the right-hand side.

4. Click **Download** to save the file (e.g., `my-app.desktop`), or click **Copy** to paste the contents elsewhere.

5. Place the downloaded `.desktop` file in the appropriate directory on your Linux system (e.g., `~/.local/share/applications/` for a single user or `/usr/share/applications/` for all users). Make sure the file is executable (`chmod +x my-app.desktop`).

## License

This project is released into the public domain under **The Unlicense**.

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

For more information, please refer to <http://unlicense.org/>
