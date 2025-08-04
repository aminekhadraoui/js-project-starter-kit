# 🚀 Full Stack Framework 

> Build complete web applications with custom HTML-like tags - from UI to database!

## 🌟 Features

- **Unified Tag System** - Create frontend UI and backend logic with custom tags
- **15+ Predefined Components** - Sliders, forms, product cards, CRUD operations
- **Real-time Preview** - Instantly test your application
- **Multi-file Export** - Generates HTML, CSS, JS, PHP & SQL files
- **Responsive Design** - Works on all device sizes
- **Database Integration** - Define tables and operations with simple tags
- **Modern UI** - Sleek dark theme with interactive elements

## 🛠️ Getting Started

1. Download `index.html`
2. Open in any modern browser
3. Start coding in the editor panel
4. Click "Build Application" to generate files
5. Click "Start Application" to preview

```html
<!-- Sample Application -->
<navbar color="#2c3e50" 
        logo="logo.png" 
        links="Home,Products,About" 
        hrefs="#home,#products,#about">
</navbar>

<slider images="product1.jpg,product2.jpg" 
        interval="4000" 
        controls="true"
        height="450px">
</slider>

<backend name="db_config">
  <connection host="localhost" 
             user="admin" 
             password="securepass" 
             dbname="app_db">
  </connection>
</backend>
