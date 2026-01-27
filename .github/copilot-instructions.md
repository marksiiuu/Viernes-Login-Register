# Copilot Instructions for LoginRegisterApp

## Overview
This project is a web application for user login and registration, built using HTML, CSS, and Bootstrap. The architecture is straightforward, focusing on user interface and experience.

## Architecture
- **Components**: The application consists of two main HTML files: `login.html` and `register.html`. The `style.css` file is used for custom styling, while Bootstrap provides responsive design elements.
- **Data Flow**: User inputs from the forms in `login.html` and `register.html` are processed on the client side. Ensure to validate inputs before submission.

## Developer Workflows
- **Building**: No specific build process is required as this is a static web application. Simply open the HTML files in a browser to view.
- **Testing**: Manual testing is performed by filling out the forms and checking for proper validation and error messages.
- **Debugging**: Use browser developer tools (F12) to inspect elements and debug JavaScript if needed.

## Project-Specific Conventions
- **File Structure**: Maintain the current file structure for clarity. All styles should be in `style.css`, and Bootstrap files should remain in their respective directories.
- **Naming Conventions**: Use lowercase for file names and separate words with hyphens (e.g., `login.html`, `register.html`).

## Integration Points
- **External Dependencies**: The project relies on Bootstrap for styling. Ensure that the Bootstrap files are correctly linked in the HTML files.
- **Cross-Component Communication**: Currently, there is no backend integration. Future enhancements may include connecting to a server for user authentication.

## Examples
- **Form Validation**: Ensure that all fields in the forms are validated before submission. Use JavaScript for client-side validation.
- **Responsive Design**: Utilize Bootstrap classes to ensure the application is mobile-friendly. Use max-width and auto height for containers to adapt to different screen sizes.
- **Styling**: Apply modern CSS techniques such as box-shadow for depth, full viewport height for centering, and consistent padding/borders for form elements. Style inputs with full width and proper spacing, and buttons with hover effects.

## Conclusion
This document serves as a guide for AI coding agents to understand the structure and workflows of the LoginRegisterApp. For any further questions, refer to the README.md for additional context.