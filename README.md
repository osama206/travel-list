# Travel List

## Overview

The Travel List Application is a React-based web app designed to help users create and manage a packing list for their trips. Users can add items to their list, mark them as packed, sort the list, and view statistics about their packing progress.

## Features

- Add items with descriptions and quantities to the packing list.
- Mark items as packed or unpacked.
- Sort items by input order, description, or packed status.
- Clear the entire list with a confirmation prompt.
- View statistics about the number of items and packing progress.

## Demo

You can see a live demo of the application [here](https://osama206.github.io/travel-list).

## Components

### App Component
The main component that encapsulates all other components and handles the state and logic of the application.

### Logo Component
Displays a static logo for the application.

### Form Component
Provides the user interface for adding new items to the packing list.

### Item Component
Represents a single item in the packing list with options to mark it as packed/unpacked and delete it.

### PackingList Component
Displays the list of items and provides functionalities for sorting and clearing the list.

### Stats Component
Shows statistics about the packing list, including the total number of items, the number of packed items, and the percentage of packed items.

## Getting Started

### Prerequisites
- Node.js (version 14.x or later)
- npm (version 6.x or later)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/osama206/travel-list.git
   ```
2. Navigate to the project directory:
   ```bash
   cd travel-list
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Application
To start the application, run:
```bash
npm start
```
This will start the development server and open the application in your default web browser.

### Building for Production
To create a production build, run:
```bash
npm run build
```
This will generate a `build` directory containing the optimized application.

## Project Structure
The project structure is as follows:
```
travel-list/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── App.js
│   │   ├── Logo.js
│   │   ├── Form.js
│   │   ├── Item.js
│   │   ├── PackingList.js
│   │   └── Stats.js
│   ├── index.js
│   ├── index.css
│   └── ...
├── package.json
└── README.md
```

## Usage

### Adding an Item
1. Enter the item description in the text input field.
2. Select the quantity from the dropdown.
3. Click the "Add" button to add the item to the packing list.

### Marking an Item as Packed
1. Check the checkbox next to the item to mark it as packed.
2. Uncheck the checkbox to mark it as unpacked.

### Deleting an Item
1. Click the ❌ button next to the item to delete it from the list.

### Sorting Items
1. Select the sorting criteria from the dropdown menu (Input order, Description, Packed status).

### Clearing the List
1. Click the "Clear list" button.
2. Confirm the action in the prompt to clear all items from the list.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

---

Enjoy your trip and happy packing! 🧳✈️
