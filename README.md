**Frontend App using React.js** 

The Frontend App built with React.js provides users the capability to generate tooltips dynamically on a mobile screen preview. This app serves as a tool to visualize tooltip positions, styles, and text changes in real-time.

**Live Preview: https://deeparsh7.github.io/Frontend-app-Using-React.js/**

**Functionalities:**

Tooltip Customization: Users have the flexibility to select the target element for the tooltip, set its position, customize its style (including text size, padding, color, background color, corner radius, width), and input the tooltip text.

Real-time Mobile Screen Preview: A mobile screen mockup is provided where button elements serve as potential target points for the tooltip. These buttons, once selected, will showcase the tooltip as customized by the user in real-time.

Pure CSS Positioning: This tooltip system is built without relying on any additional libraries, ensuring lightweight and efficient rendering.

**Project Structure:**

TooltipForm Component: This component contains the form elements allowing users to customize the tooltip's target, position, style, and text.

MobilePreview Component: This component displays a mobile screen preview with button elements. Tooltips are rendered on this component based on the specifications provided in the TooltipForm.

Code Maintenance and Version Control:

The project's development progress can be tracked through its commit history. Each commit serves as a checkpoint, detailing the changes made, ensuring easy rollback if needed, and maintaining a clear development timeline.

**How to Run:**

README
Frontend App using React.js
The Frontend App built with React.js provides users the capability to generate tooltips dynamically on a mobile screen preview. This app serves as a tool to visualize tooltip positions, styles, and text changes in real-time.

Live Preview: https://deeparsh7.github.io/Frontend-app-Using-React.js/

Functionalities:
Tooltip Customization: Users have the flexibility to select the target element for the tooltip, set its position, customize its style (including text size, padding, color, background color, corner radius, width), and input the tooltip text.

Real-time Mobile Screen Preview: A mobile screen mockup is provided where button elements serve as potential target points for the tooltip. These buttons, once selected, will showcase the tooltip as customized by the user in real-time.

Pure CSS Positioning: This tooltip system is built without relying on any additional libraries, ensuring lightweight and efficient rendering.

Robustness:
Dynamic State Management: The app efficiently manages and updates the state based on user input, ensuring that the mobile preview reflects changes in real-time.

Responsive UI: While the main focus is a mobile screen preview, the app itself is designed to be viewed on various screen sizes.

Fallback Defaults: In cases where certain style attributes aren't specified by the user, the app resorts to predefined defaults ensuring the tooltip is always rendered.

Project Structure:
TooltipForm Component: This component contains the form elements allowing users to customize the tooltip's target, position, style, and text.

MobilePreview Component: This component displays a mobile screen preview with button elements. Tooltips are rendered on this component based on the specifications provided in the TooltipForm.

Code Quality:
Clarity and Readability: The codebase is structured in a way that promotes easy comprehension. Components are modularized, and variable/function names are descriptive.

Best Practices: The application follows React's best practices, including the use of functional components and hooks.

Efficiency: By leveraging React's state and props, the app ensures efficient DOM updates without unnecessary re-renders.

UI Accuracy:
The application's UI has been designed to be user-friendly, with intuitive form elements and clear visual feedback on the mobile preview. Every effort has been made to ensure the UI adheres closely to the provided design file.

Code Maintenance and Version Control:
The project's development progress can be tracked through its commit history. Each commit serves as a checkpoint, detailing the changes made, ensuring easy rollback if needed, and maintaining a clear development timeline.

How to Run:
Clone the Repository:
git clone https://github.com/deeparsh7/Frontend-app-Using-React.js.git

Navigate to the project directory:
cd Frontend-app-Using-React.js
Install Dependencies:

If you're using npm:
npm install

If you're using yarn:
yarn install
Run the App:

If you're using npm:
npm start

If you're using yarn:
yarn start

This will start the development server, and the app should automatically open in your default browser.
 If not, you can manually navigate to http://localhost:3000/.
