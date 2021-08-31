JS Commerce

1. Create Folder Structure
   1. create root directory as jscommerce
   2. add frontend and backend directory
   3. create src in frontend directory
   4. run npm init in frontend directory
   5. npm install -D live-server
   6. add start command as live-server src --verbose
   7. run npm start

2. Design Website
   1. create css/main.css
   2. link main.css to index.html
   3. create div.grid-container
   4. create header, main, and footer
   5. style html and body
   6. style grid-container, header, main, and footer

3. Create Static Homepage
   1. create ul.products
   2. create li
   3. create div.product
   4. add .product-image, .product-name, .product-brand, .product-price
   5. style ul.product and internal divs
   6. duplicate 2 items to show 3 items

4. Render Dynamic Homepage
   1. create data.js
   2. export an array of 6 products
   3. create js/homepage.js
   4. export homepage as an object with render() method
   5. implement render()
   6. import data.js
   7. return products mapped to <li>s inside <ul>
   8. create app.js
   9. link app.js to index.html as module
   10. set main id to main-container
   11. create router() function
   12. set main_container innerHTML to homepage.render()
   13. set load event of window to router() function