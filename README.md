# Photoalbum
Hello, this technical showcase is to display the title and photo ids in a photo album.  The photos are available at 
"(https://jsonplaceholder.typicode.com/photos)."

I used the fetch api to display json data in an html file.

To access data:
1. Clone the repo.
2. Copy the full path for index.html. (ctrl+shift+c)
3. Paste the full path on the web browser's url.
4. Open developer tools in browser (ctrl+shift+i).
5. Click on console tab (in between elements and sources) and paste the following into console:
fetch('https://jsonplaceholder.typicode.com/photos')
        .then(response => response.json())
        .then(json => console.log(json))
        
6. 5000 titles, photoIDs, and IDs should be displayed, click on the arrows to expand and see every albumId, id, and title.


