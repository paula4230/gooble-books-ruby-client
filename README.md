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
<ul>1. Before anything else, <a href='https://cloud.google.com/docs/authentication/api-keys?visit_id=637652443905382742-2139937274&rd=1'> generate an API key<a>.</ul>
<ul>2. Fork or download this repo.</ul> 
<ul>3. In your command line, <strong>cd</strong> into the repo and bundle install Faraday and OJ(optional) gems.</ul>
<ul>4. Run the database migrations thru <strong>rake db:migrate</strong>.</ul>
<ul>  
  5. In the <strong>client.rb</strong> file under the apps/apis/google_books/v1 directory, input your generated API key here
  <img>initialize.png</img>

</ul>
  
