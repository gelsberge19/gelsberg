<!DOCTYPE html>
<html>
<head>
    <title>Styling Example</title>
    <style>
        
        body {
            background-color: #0a0a0bbb;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        
        .styled-div {
            background-color: #00000007;
            color: #000000;
            padding: 20px;
        }

        
        h1, h2 {
            font-family: 'Roboto', sans-serif;
        }

       
        section {
            border: 2px solid #cccccc;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
        }

        section.skills li:hover {
            color: #b6530b; 
            cursor: pointer;
        }
    </style>
</head>
<body>
  
    <div class="styled-div">
        <h1> Gelsberge </h1>
        <p> B.TECH CSE(Spcl.in Data Analytics)</p>
    </div>


   
    <section>
        <h2> Education </h2>
        <p> Karunya University.</p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>python</li>
        </ul>
    </section>


</body>
</html>




<!DOCTYPE html>
<html>
<head>
  <title>Product Showcase</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #333;
      padding: 20px 0;
      text-align: center;
      color: #fff;
    }

    nav {
      background-color: #555;
      display: flex;
      justify-content: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      padding: 0;
    }

    nav li {
      margin: 0 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      padding: 10px 20px;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }

    .product-card {
      width: 300px;
      border: 1px solid #ccc;
      margin: 10px;
      padding: 20px;
      text-align: center;
    }

    .product-card img {
      max-width: 100%;
    }

    aside {
      background-color: #eee;
      padding: 20px;
    }

    aside ul {
      list-style: none;
      padding: 0;
    }

    aside li {
      margin: 10px 0;
    }

    footer {
      background-color: #333;
      padding: 20px 0;
      text-align: center;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Product Showcase</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Products</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section class="product-card">
      <img src="product1.jpg">
      <h2>Iphone 14 pro</h2>
      <p> $1000 </p>
    </section>
    <section class="product-card">
      <img src="product2.jpg" >
      <h2>Apple watch ultra</h2>
      <p> $800 </p>
    </section>
    <section class="product-card">
      <img src="product3.jpg" >
      <h2>Macbook air</h2>
      <p> $1000 </p>
    </section>
  </main>

  <aside>
    <ul>
      <li><a href="#">Related Link 1</a></li>
      <li><a href="#">Related Link 2</a></li>
      <li><a href="#">Related Link 3</a></li>
    </ul>
  </aside>

  <footer>
    <p>&copy; 2023 Your Company. All rights reserved.</p>
  </footer>
</body>
</html>

