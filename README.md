# CSC225-Project3
There is an API collection of books available @ the following endpoint (no trailing slash): http://csc225.mockable.io/books

The individual resources (books) are available at the following endpoint scheme: http://csc225.mockable.io/books/{ID} where {ID} is the ID from the API collection endpoint

The collection has limited data, just the ID, Title, and Author. The individual resource endpoints have more data, including the release year and a cover or associated image.

Your assignment is to use a bootstrap starter template (https://getbootstrap.com/docs/4.4/getting-started/introduction/#starter-template) as a starting point and create a site that does the following:

    When a user first loads the site, they should see a loading notification and make an AJAX (e.g., preferably using axios.get()) request to the API Collection. 
    When you get the response back, hide the loading notification and output the listing of books.

    When a user clicks on an individual book in the listing created in the previous bullet, the application should display loading notification, retrieve the book data (using the resource endpoint scheme) and then replace the loading notification with a card containing the book meta (author, country, language, link, pages, title, year, cover). 
    See https://getbootstrap.com/docs/4.4/components/card/ as a starting point for what is meant by a card.

Important notes:

    – If you are having issues getting the images to appear, please contact me and do not let that hold you up.
    – After the page loads the first time, there should be no subsequent page reloads; everything should happen with AJAX (e.g., preferably using axios.get()) and JavaScript.
    – You should submit a link to a GitHub repository that contains 1 HTML file, 1 CSS file, and 1 JavaScript file. Bootstrap 4 CSS + all JavaScript libraries and dependencies come from the Bootstrap Starter
