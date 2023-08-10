Calculator App 🧮

Welcome to the Calculator App! This README will guide you through the application, its features, and the technology stack used to build it.

Table of Contents 📑

1. Introduction
2. Features
3. Technology Stack
4. How to Run
5. License

Introduction 🌟
Calculator App is a simple, user-friendly calculator application built using React Native. It's designed to be used across iOS, Android, and web platforms. The application showcases a modern UI and provides basic arithmetic functions that you would expect from a standard calculator.

Features ✨
Here's a rundown of the application's features:
• Basic Arithmetic Operations: Addition, Subtraction, Multiplication, and Division.
• Percentage Calculation: Easily calculate percentages with a single tap.
• Sign Toggle: Switch between positive and negative numbers.
• Clear Functionality: Reset your current calculation with a clear button.
• Decimal Support: Work with floating-point numbers.
• Memory Functionality: Recent operations and results are easily accessible.
• Responsive Design: Adapts to different screen sizes and orientations.
Technology Stack 🔧
The application is built using modern web technologies and tools. Here's a breakdown of the stack:
Frontend:
• React Native: A popular framework for building native apps using React.
• Expo: A framework used for developing universal React applications.
• Tailwind CSS: A utility-first CSS framework for rapidly building custom designs.
Development Tools:
• Yarn: Package manager that doubles down as project manager.
• Babel: A JavaScript compiler that lets us use next-generation JavaScript today.
Configuration:
The Tailwind CSS configuration can be found below:
javascript
module.exports = {
content: ["./App.{js,jsx,ts,tsx}", "./components/**/*.{js,jsx,ts,tsx}"],
theme: {
extend: {},
},
plugins: [],
}

How to Run 🏃‍♂️

1. Clone the repository: git clone https://github.com/username/calculator-app.git
2. Navigate to the project directory: cd calculator-app
3. Install dependencies: yarn install
4. Start the application: yarn start
5. Run on specific platform:
   o iOS: yarn ios
   o Android: yarn android
   o Web: yarn web

License 📝
This project is licensed under the MIT License.

Happy calculating! 🎉 Feel free to contribute, and don't hesitate to reach out if you have any questions or suggestions.
