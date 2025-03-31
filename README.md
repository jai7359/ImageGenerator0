# Image Generation Website using Hugging Face API
![image](https://github.com/user-attachments/assets/b2cb14e6-a36a-490d-8beb-bcdb6e447df9)

This project is a simple website that allows users to generate images using the Hugging Face Inference API. It's built with HTML, CSS, and JavaScript, and provides a user-friendly interface to generate and download images.

## Features

-   **Image Generation:** Uses the Hugging Face Inference API to generate images based on user prompts.
-   **User Prompt Input:** Allows users to enter text prompts to guide image generation.
-   **Image Display:** Displays the generated image on the website.
-   **Easy Download:** Provides a button to easily download the generated image.
-   **Simple and Clean UI:** Designed with a clean and intuitive user interface.

## Technologies Used

-   HTML
-   CSS
-   JavaScript
-   Hugging Face Inference API

## Prerequisites

-   Hugging Face API Key: You'll need a valid Hugging Face API key to use the image generation API.
-   Web Browser: A modern web browser (Chrome, Firefox, Safari, etc.) to view the website.

## How to Use

1.  **Obtain Hugging Face API Key:**
    -   Sign up for a Hugging Face account (if you don't have one).
    -   Go to your Hugging Face settings and create an API key.

2.  **Clone or Download the Project:**
    -   Clone the repository or download the project files to your local machine.

3.  **Replace API Key:**
    -   Open the `script.js` file.
    -   Find the line where the API key is defined (e.g., `const API_TOKEN = "YOUR_API_KEY";`).
    -   Replace `"YOUR_API_KEY"` with your actual Hugging Face API key.

4.  **Open the Website:**
    -   Open the `index.html` file in your web browser.

5.  **Generate Image:**
    -   Enter a text prompt in the input field.
    -   Click the "Generate Image" button.
    -   The generated image will be displayed on the page.

6.  **Download Image:**
    -   Click the "Download Image" button to download the generated image.

## Project Structure

<project_directory>/
├── index.html     # Main HTML file
├── style.css      # CSS styling file
├── script.js       # JavaScript logic file
└── ...            # Other assets (if any)


## Setup Instructions

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    cd <project_directory>
    ```

2.  Replace the API key in `script.js`.

3.  Open `index.html` in your browser.

## Important Notes

-   **API Key Security:** Be careful not to expose your Hugging Face API key in public repositories or client-side code. Consider using server-side implementations for better security.
-   **API Usage Limits:** Be aware of the Hugging Face Inference API usage limits.
-   **Error Handling:** The provided script may lack robust error handling. Consider adding error handling for API requests and other potential issues.
-   **Model Selection:** Currently, the script may use a default model. Consider adding options for users to select different image generation models.

## Future Improvements

-   Add options for users to select different image generation models.
-   Implement progress indicators during image generation.
-   Add error handling for API requests and other potential issues.
-   Enhance the UI with more advanced features.
-   Implement server-side API key handling for improved security.
-   Add image size and aspect ratio selection.
-   Add image editing options.
