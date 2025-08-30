// script.js

// 3D Book Feature
const bookContainer = document.querySelector('.book-container');
const book = document.querySelector('.book');

// Generate book pages dynamically
for (let i = 0; i < 10; i++) {
  const page = document.createElement('div');
  page.classList.add('book-page');
  page.style.background = `url('page-${i}.jpg')`;
  book.appendChild(page);
}

// Sign-up/Login Functionality
const signupForm = document.getElementById('signup-form');
const signupBtn = document.getElementById('signup-btn');
const googleLoginBtn = document.getElementById('google-login-btn');

// Add event listeners for sign-up and login
signupBtn.addEventListener('click', () => {
  // Handle sign-up functionality
});

googleLoginBtn.addEventListener('click', () => {
  // Handle Google login functionality
});

// Book Release Section
const releaseBookBtn = document.getElementById('release-book-btn');
const bookList = document.querySelector('.book-list');

// Add event listener for releasing new book
releaseBookBtn.addEventListener('click', () => {
  // Handle releasing new book functionality
});

// Search Bar Functionality
const searchInput = document.getElementById('search-input');
const searchBtn = document.getElementById('search-btn');

// Add event listener for search
searchBtn.addEventListener('click', () => {
  // Handle search functionality
});

// Write and Release Book Feature
const bookEditor = document.getElementById('book-editor');
const saveBookBtn = document.getElementById('save-book-btn');
const publishBookBtn = document.getElementById('publish-book-btn');

// Add event listeners for saving and publishing book
saveBookBtn.addEventListener('click', () => {
  // Handle saving book functionality
});

publishBookBtn.addEventListener('click', () => {
  // Handle publishing book functionality
});

// Book Library
const libraryContainer = document.querySelector('.library-container');
const bookShelf = document.querySelector('.book-shelf');

// Generate book shelf dynamically
for (let i = 0; i < 10; i++) {
  const bookCover = document.createElement('div');
  bookCover.style.background = `url('book-${i}.jpg')`;
  bookShelf.appendChild(bookCover);
}
