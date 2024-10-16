
![dogoogfetcher](https://github.com/user-attachments/assets/51e020ca-97a0-48f4-8c79-5e6a5afe1e86)

Features

Fetches random dog images with a single click.

Displays the fetched dog image in an image container.

Uses async/await for clean, readable code.

Technologies Used

HTML: Structure of the web page.

CSS: Basic styling for image display.

JavaScript: Handles fetching data from the Dog API and updating the image.


Usage

Click the Get Doggo button.

A new random dog image will be fetched and displayed.

Enjoy an endless stream of cute dog pictures!

Code Explanation

The getDoggo function is an asynchronous function that:

Fetches a random dog image from the Dog CEO API.

Parses the response into JSON format.

Updates the src attribute of the image element with the new dog image URL.

The button with ID get-doggo listens for a click event and triggers the getDoggo function.
