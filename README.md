# React Star Rating

This project is a simple React component for creating star ratings. Users can click on stars to rate items, and the component visually represents the selected rating.

## Features

- Displays star icons for rating.
- Allows users to click on stars to select a rating.
- Updates the display to show the selected rating.

## Getting Started

To use this star rating component in your project, follow these steps:

1. Copy the `StarRating.jsx` file into your project directory.
2. Import the `StarRating` component into your React application.
3. Render the `StarRating` component with the desired number of stars as a prop.

## Example Usage

```javascript
import React from 'react';
import StarRating from './StarRating';

function App() {
  return (
    <div className="App">
      <h1>Star Rating</h1>
      <StarRating noOfStars={5} />
    </div>
  );
}

export default App;
