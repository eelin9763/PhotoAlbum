# Photoalbum
Hello, this LT technical showcase is to display the title and photo ids in a photo album.  The data is available at 
"(https://jsonplaceholder.typicode.com/photos)."

I used the fetch api to display json data in an html file.

To access data:
1. Clone the repo.
2. cd Photoalbum.
3. Copy the full path for index.html. (ctrl+shift+c)
4. Paste the full path on the web browser's url.
5. Open developer tools in browser (ctrl+shift+i).
6. Click on console tab (in between elements and sources) and data should be displayed.  If not displayed:

6a. Copy and paste the following into console:
```
fetch('https://jsonplaceholder.typicode.com/photos')
        .then(response => response.json())
        .then(json => console.log(json))
```
        
7. 5000 titles, photoIDs, and IDs should be displayed, click on the arrows to expand and see every albumId, id, and title.
