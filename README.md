# google-books-ruby-client

A Ruby client for the <a href='https://developers.google.com/books/docs/overview'> Google Books API <a>.
  
<h2>ENDPOINTS</h2>
There are five endpoints for this client, namely:
  <ul>1. Books - gives a list of books containing keywords from the search parameters.</ul>
  <ul>2. Downloads - similar to #1, however, search is limited to books that can be downloaded and accessed thru an ebook reader.</ul>
  <ul>3. Volume ID - gives a single book from the given volume ID. Since each volume ID is unique, is must be explicitly entered by the user.</ul>
  <ul>4. Bookshelves - gives the list of bookshelves of a user. Each bookshelf ID is specific to a user and must be explicitly entered as well.</ul>
  <ul>5. Shelf Volumes - gives the list of books from a user's bookshelf. Parameters should include bookshelf ID and shelf ID.</ul>
  
<h2>USAGE</h2>
<p>Before anything else, <a href='https://cloud.google.com/docs/authentication/api-keys?visit_id=637652443905382742-2139937274&rd=1'> generate an API key<a></p>
<p>In general, user may generate an API key and fork this repo. Otherwise instructions are as follows: </p> 
<ul>2. Generate a new rails app.</ul>
<ul>3. Bundle install Faraday and OJ(optional) gems.</ul>
<ul>4. Create a client.rb file in the apps directory. Example: apps/google_books/v1/client.rb. 
  <div> Example: apps/google_books/v1/client.rb</div
</ul>
<ul>1. Books - gives a list of books containing keywords from the search parameters.</ul>

<h3>Tips: Try the API in the console to see if it is working correctly. </h3>
