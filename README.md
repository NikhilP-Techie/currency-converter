# Currency Converter

This is a simple currency converter application built using React and Tailwind CSS. It allows users to convert amounts between two selected currencies. The application features a clean and user-friendly interface.

## Features

- Convert currency amounts from one type to another.
- Swap the "From" and "To" currency types with a single button.
- Responsive and intuitive design using Tailwind CSS.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **Vite**: For bundling and serving the application.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/currency-converter.git
   cd currency-converter
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the application in your browser at `http://localhost:5173`.

## Usage

1. Select the "From" currency type and enter the amount to convert.
2. Select the "To" currency type.
3. Click the **Convert** button to see the converted amount.
4. Use the **Swap** button to interchange the selected currencies.

## Folder Structure

```
06currencyConverter/
├── node_modules/          # Project dependencies
├── public/
│   └── vite.svg           # Favicon
├── src/
│   ├── assets/            # Static assets
│   │   └── react.svg      # React logo
│   ├── components/        # Reusable components
│   │   ├── InputBox.jsx   # Input box component
│   │   └── index.js       # Component entry point
│   ├── hooks/             # Custom hooks
│   │   └── useCurrencyInfo.js # Hook for managing currency information
│   ├── App.css            # Styles for the App component
│   ├── App.jsx            # Root App component
│   ├── index.css          # Global styles
│   ├── main.jsx           # Application entry point
├── .gitignore             # Files to ignore in Git
├── eslint.config.js       # ESLint configuration
├── index.html             # # Main HTML file
├── package-lock.json      # Package lock file
├── package.json           # Project metadata and dependencies
├── postcss.config.js      # PostCSS configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.js         # Vite configuration
└── README.md              # Project documentation
```

## Example Code

Here’s an example of how the **Swap** functionality works:

```javascript
const handleSwap = () => {
  setFromCurrency(toCurrency);
  setToCurrency(fromCurrency);
};
```

## Deployment

To deploy the application:

1. Build the project:

   ```bash
   npm run build
   ```

2. Deploy the contents of the `dist` folder to your preferred hosting service (e.g., Vercel, Netlify).

## Future Improvements

- Add real-time currency exchange rates using an API.
- Implement error handling for invalid inputs.
- Add more styling and animations.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to fork and contribute to this project!

