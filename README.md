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
