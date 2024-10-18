<Html>
    <head>
        <meta charset="utf-8">
        <title>object literals</title>
    </head>
    <body>
        <h1>object with methods</h1>
        <script>
            const ob = {add(a,b)
                {
                    return a+b;
                },
                "greet":function(){
                    document.write("hi, i am greet<br>");
                },
                sub : (a,b) =>{return a-b;}
            };
            ob.greet(0);
            document.write("sum is"+ob.add(12,45) + "<br>");
            document.write("sub is" + ob.sub(33,16)+"<br>");
        </script>
    </body>
</Html>
