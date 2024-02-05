# Image Search App

A simple React application that allows users to search for images using the Canberk API.

## Installation

1. Clone the project to your local machine:

```bash
git clone https://github.com/your-username/image-search-app.git
cd image-search-app
```

2. Install dependencies:
```bash
Copy code
npm install
```
3. Start the application:
```bash
Copy code
npm start
```
The application will be available at http://localhost:3000 in your web browser.


# Usage
1. Open the application in your web browser.
2. Enter a search term in the search bar provided by the SearchHeader component.
3. Press Enter or click the search button to retrieve images related to the entered term.
4. View the search results in the ImageList component.

# Components

1. App
The main application component that integrates the SearchHeader and ImageList components.

2. SearchHeader
A component that provides a search input field for users to enter search terms. It triggers a search when a term is submitted.

3. ImageList
A component that displays a list of images based on the search results.

# API Integration
The application uses the Canberk API for image searches. The searchImages function is responsible for fetching images based on the provided search term.

# State Management
The application uses the useState hook to manage the state of retrieved images.

# Contribution
If you would like to contribute to this project, please open an issue or submit a pull request. Your contributions are welcome!

# DEMO Link 
https://search-api-mu.vercel.app/