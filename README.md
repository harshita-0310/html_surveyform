const README_CONTENT: string = `
# The Digital Horizon: Future Tech Adoption Survey

## 🚀 Project Overview

This project is a static, basic HTML survey form designed to gather public opinion on emerging technologies and future tech adoption trends, specifically focusing on Artificial Intelligence (AI), Augmented Reality (AR), and autonomous systems.

This form was created purely using foundational HTML elements, strictly adhering to core form structure requirements without the use of external CSS (like Tailwind) or JavaScript.

## ✨ Features

The survey incorporates all essential HTML form input types and structural elements required for a comprehensive assignment:

* **Header Elements:** Includes a main title (\`<h1>\` with \`id="title"\`) and a description (\`<p>\` with \`id="description"\`).

* **Form Structure:** Uses a primary \`<form>\` element (\`id="survey-form"\`) with the \`POST\` method.

* **Standard Inputs:** Fields for Name (type \`text\`), Email (type \`email\`), and Age (type \`number\`), all utilizing \`placeholder\` and \`required\` attributes.

* **Labeling:** All inputs are clearly labeled using associated \`<label>\` elements with required \`id\`s (\`name-label\`, \`email-label\`, \`number-label\`).

* **Dropdown:** A \`<select>\` element (\`id="dropdown"\`) with multiple selectable \`<option>\` choices.

* **Radio Buttons:** A group of radio inputs to ensure only one choice can be selected, each with \`name\`, \`value\`, and \`required\` attributes.

* **Checkboxes:** Multiple independent \`<input type="checkbox">\` elements allowing users to select multiple options, each with a \`value\`.

* **Textarea:** A multi-line \`<textarea>\` for open-ended feedback.

* **Submission:** A final \`<button type="submit">\` element (\`id="submit"\`) to complete the form.

## 🛠️ How to Run

Since this project consists of a single, basic HTML file, it requires no special tools or web server to view.

1. **Save the file:** Ensure the code is saved as \`index.html\`.

2. **Open in Browser:** Navigate to the saved file location on your computer and double-click the \`index.html\` file.

3. **View:** The form will open instantly in your default web browser. Since no CSS is applied, it will display with the browser's default styling, highlighting the pure structure of the HTML.
`;

export default README_CONTENT;
