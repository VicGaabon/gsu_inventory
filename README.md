# GSU Property Inventory System

A modern property inventory management system built with React, Vite, and Tailwind CSS.

## Features

- **Property Management**: Add, edit, and delete properties
- **Search & Filter**: Search properties by name, category, location, or description
- **Local Storage**: Data persists locally in the browser
- **Modern UI**: Clean, responsive design using Tailwind CSS
- **Real-time Updates**: Instant updates to property listings

## Property Categories

- Furniture
- Electronics
- Rooms
- Vehicles
- Equipment
- Supplies
- Other

## Property Status Options

- Available
- In Use
- Maintenance
- Retired

## Condition Ratings

- Excellent
- Good
- Fair
- Poor

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Usage

1. **View Properties**: The main dashboard shows all properties in a table format
2. **Add Property**: Click the "Add Property" button to create a new property entry
3. **Edit Property**: Click the "Edit" button next to any property to modify its details
4. **Delete Property**: Click the "Delete" button to remove a property (with confirmation)
5. **Search**: Use the search bar to filter properties by various criteria

## Data Storage

The application uses localStorage to persist data locally in the browser. Initial mock data is provided for demonstration purposes.

## Project Structure

```
src/
  components/
    PropertyList.jsx    # Main property table component
    PropertyForm.jsx    # Add/Edit property form
    SearchBar.jsx       # Search functionality
  context/
    PropertyContext.jsx # Global state management
  App.jsx              # Main application component
  main.jsx             # Application entry point
  index.css            # Tailwind CSS imports
```

## Technologies Used

- **React 18** - UI framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript ES6+** - Modern JavaScript features

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
