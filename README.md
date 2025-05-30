# Test
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Porfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <nav>
       <h1>Emmanuel</h1>
        <ul>
             <li><a href="#">Home</a></li>
              <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                
  </ul>
</nav> 
 
     <section class="hero">
         <h2>Welcome to my Portfolio</h2>
         <p>I'm a front-end developer passioinate  about creating  userfriendly website</p>
         <button>Show date</button>
      </section>
        <section class="date">
       <button onclick="">Show date</button>
        <p id="date"></p>
    <script>
       
        document.querySelector('button').addEventListener('click', function() {
            const date = new Date();
            document.getElementById('date').textContent = date.toLocaleDateString();
        });
</script>
</body>
</html>
