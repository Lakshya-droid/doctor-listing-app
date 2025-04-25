# Doctor Listing Application

![Doctor Listing App Screenshot](./screenshot.png)

A responsive doctor listing application with advanced filtering and search capabilities, built with React.js.

## Features

- **Autocomplete Search**: Search doctors by name with intelligent suggestions
- **Comprehensive Filters**:
  - Consultation type (Video/In-Clinic)
  - Multiple specialty selection
  - Sorting by fees or experience
- **URL Persistence**: All filters are maintained in URL query parameters
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, professional interface with blue/white/grey color scheme

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/doctor-listing-app.git
   cd doctor-listing-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
src/
├── components/          # React components
│   ├── DoctorCard.js    # Individual doctor card component
│   ├── FilterPanel.js   # Main filter panel component
│   ├── SearchBar.js     # Search with autocomplete
│   └── SpecialityFilter.js # Specialty filter component
├── App.js               # Main application component
├── App.css              # Global styles
├── index.js             # Application entry point
└── utils/
    └── api.js           # Mock API service
```

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App (advanced)

## Testing

The application includes `data-testid` attributes for all key components to support automated testing:

```javascript
// Example test IDs
data-testid="autocomplete-input"
data-testid="doctor-card"
data-testid="filter-video-consult"
data-testid="sort-fees"
```

## Deployment

To deploy to production:

```bash
npm run build
```

This creates an optimized production build in the `build` folder that can be deployed to any static hosting service.

## Technologies Used

- React.js
- CSS (no external UI libraries)
- HTML5
- JavaScript ES6+

## Future Enhancements

- Add pagination for large result sets
- Implement "Clear All Filters" functionality
- Add doctor rating system
- Integrate with real backend API

