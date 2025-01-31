Three ways by which I can add CSS to an HTML Document:

<!-- 1. By linking an external CSS file using the <link> tag -->

By creating a seperate file named "styles.css" and writing my css code there
For example;
<head>
<link rel="stylesheet" href="styles.css" />
</head>

       <!-- 2. Internal CSS -->
       This is by adding CSS code within the HTML Document using the <style> tag
       For example;
           <head>
           <style>
           header{
             background-color: red;
             padding: 1rem;
           }
           </style>
           </head>

           <!-- 3. Inline styles -->
           By adding CSS Styles directly to an HTML element using the "style" attribute
           For example;
           <body>
           <p style="color: blue; font-size: 20px;>
           </body>
