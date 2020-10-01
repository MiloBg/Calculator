# Calculator
Fancy Working Calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Fancy Calculator</title>
</head>
<body>
   
   <form class="calculator" name="calc">
   
        <input type="text" placeholder="0" class="value" name="txt" readonly="">
   
        <div class="calculator-buttons">
   
        <span class="calc-button clear" onclick="document.calc.txt.value =''">C</span>
        <span class="calc-button" onclick="document.calc.txt.value +='/'">&divide;</span>
   
        <span class="calc-button" onclick="document.calc.txt.value +='7'">7</span>
        <span class="calc-button" onclick="document.calc.txt.value +='8'">8</span>
        <span class="calc-button" onclick="document.calc.txt.value +='9'">9</span>
        <span class="calc-button" onclick="document.calc.txt.value +='*'">&times;</span>
        
        <span class="calc-button" onclick="document.calc.txt.value +='4'">4</span>
        <span class="calc-button" onclick="document.calc.txt.value +='5'">5</span>
        <span class="calc-button" onclick="document.calc.txt.value +='6'">6</span>
        <span class="calc-button" onclick="document.calc.txt.value +='-'">&minus;</span>

        <span class="calc-button" onclick="document.calc.txt.value +='1'">1</span>
        <span class="calc-button" onclick="document.calc.txt.value +='2'">2</span>
        <span class="calc-button" onclick="document.calc.txt.value +='3'">3</span>
        <span class="calc-button" onclick="document.calc.txt.value +='+'">&plus;</span>

        <span class="calc-button zero" onclick="document.calc.txt.value +='0'">0</span>
        <span class="calc-button equals" onclick="document.calc.txt.value = eval(calc.txt.value)">&equals;</span>
        
    </div>
</form>
    
</body>
</html>
