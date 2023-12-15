# Lab 10

1.Create angular project with routing support
2. Add primeng library to project
3. Add 2 feature modules: Admin module(lazy loaded) and Customer module. Add navigation with links to admin and customer areas of app.
4. Create store product search service (with paging) and use json-server as backend api. Each product has title, price, price and image(url)
5. Implement product management page in Admin module using service created earlier. All product are displayed as a table. Use primeng table component for creating table. Table contains columns: title and small preview of image. Each row has activate/deactivate button which updates product status (available/not available). Add route to module's routing module.
6. Implement product listing page(with paging) in Customer module using service created earlier. Use primeng DataView component. Each product tile has follwing fileds: title, price and image. Display price using currency pipe. Add route to module's routing module.
7. Implement add to favorites feature: each product has button add to favorites which is active if product is not already in favorites.
Store user favorite products in browser localstorage (use ngx-webstorage library)


