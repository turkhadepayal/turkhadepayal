<!DOCTYPE html>
<html>
<head>
    <title>Simple Calculator</title>
</head>
<body>
    <h2>Simple Calculator</h2>
    <form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">
        <label for="num1">Enter first number:</label>
        <input type="number" name="num1" id="num1" required><br><br>
        
        <label for="num2">Enter second number:</label>
        <input type="number" name="num2" id="num2" required><br><br>
        
        <label for="operator">Select operation:</label>
        <select name="operator" id="operator">
            <option value="add">Addition (+)</option>
            <option value="subtract">Subtraction (-)</option>
            <option value="multiply">Multiplication (*)</option>
            <option value="divide">Division (/)</option>
        </select><br><br>
        
        <input type="submit" value="Calculate">
    </form>

    <?php
    // Function to perform calculation based on selected operation
    function calculate($num1, $num2, $operator) {
        switch($operator) {
            case "add":
                return $num1 + $num2;
            case "subtract":
                return $num1 - $num2;
            case "multiply":
                return $num1 * $num2;
            case "divide":
                if ($num2 == 0) {
                    return "Cannot divide by zero";
                } else {
                    return $num1 / $num2;
                }
            default:
                return "Invalid operator";
        }
    }

    // Check if form is submitted
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $num1 = $_POST["num1"];
        $num2 = $_POST["num2"];
        $operator = $_POST["operator"];

        // Perform calculation
        $result = calculate($num1, $num2, $operator);

        // Display result
        echo "<h3>Result: $result</h3>";
    }
    ?>
</body>
</html>
