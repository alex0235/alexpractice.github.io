<!DOCTYPE html>
<head>
    <meta charset = "UTF-8">
    <meta name="author" content="Iesha">
    <meta name="description" content="Warmth" >
    <meta name="keywords" content="thank you">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>decembre</title>

    <link rel=stylesheet type="text/css" href="decembre.css">

    <script>
        //https://www.w3schools.com/jsref/met_win_prompt.asp
        //https://www.w3schools.com/js/js_popup.asp

        function verify() {
            let person = prompt("enter YOUR name");
            
            if (person.toUpperCase() == "GINO") {

                document.getElementById("id1").innerHTML  = "61n0 &#129416";
                document.getElementById("id2").innerHTML  = "Snowflakes of Love";

            } else if (person.toUpperCase() == "IESHA"){
                alert("hi that's me "); 
            }else
                alert("pardon qui etes vous???")
                window.close();    

        }
    </script>

</head>
<body onload="verify()">
<header> 
    
    <h1 id="id1"></h1>
    <nav>
        <a href="decembre2.html" id="id2"></a>
        
    </nav>
    
</body>
</html>
