# multiplication-table
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Javascript</title>
</head>
<body>
    <div align="center">
    

    <br></br>
    <h1>Please Enter Your Attendance Percentage</h1>    
    <br><br>
    <h5 id="resultmul"></h5>

    


    <script>
        var table = parseInt(prompt("Enter the Multiplication table Number"));
       
       
        var length = 10;
        var i = 1;
        document.write("Multiplication table: "+ table);
        for(i = 1; i<=length; i++)
        document.write("<br>"+i+" *"+table+" *" +(i * table));
        
        </script>

</div>





</body>
</html>
