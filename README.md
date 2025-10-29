##Book Finder

A simple and elegant **Book Finder Web App** that lets you search for books by title, author, or keyword — powered by the [Google Books API](https://developers.google.com/books/).

![Book Finder Screenshot](https://via.placeholder.com/800x400?text=Book+Finder+Preview)

##Features

 #Search books by title, author, or topic  
 #Displays book cover, title, author, and link to more info  
 #Responsive grid layout  
 #Works directly in your browser — no backend needed  
#Powered by live data from Google Books API  

##How It Works

The app sends a query to the **Google Books API** using JavaScript’s `fetch()` method and displays the results dynamically on the page.
flowchart TD

A[User enters keyword] --> B[JavaScript fetches from Google Books API]
B --> C[API returns JSON with book details]
C --> D[JavaScript creates book cards dynamically]
D --> E[Results shown in browser]

##Technologies Used

HTML5
CSS3
JavaScript (Vanilla)
Google Books API

##projec structure
book-finder/
├── book-finder.html   # Main app file
└── README.md          # Project documentation

## To run locally
download repo
git clone https://github.com/omkaran123/book-finder.git

##Credits

Developed by: Omkaran
Data Source: Google Books API
Icons/Emoji: Unicode
