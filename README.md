<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudoku Solver</title>

    <link href="sudokustyle.css" rel="stylesheet" ></link>
</head>

<body>
    <h1 align="center">9 x 9 Sudoku Solver</h1>
    <p id="alert-msg">Input Some Values!</p>
    <p id="invalid-input-msg" style="color: red; display: none;">Invalid input! Please enter a number between 1 and 9.</p>
    <div id="content-div">
    <table id="grid">
        <tbody>
        <tr><td><input type="number" class="top-row col-start" id="00"></td>
            <td><input type="number" class="top-row"id="01"></td>
            <td><input type="number" class="top-row col-end"id="02"></td>
            <td><input type="number" class="top-row col-start"id="03"></td>
            <td><input type="number" class="top-row"id="04"></td>
            <td><input type="number" class="top-row col-end" id="05"></td>
            <td><input type="number" class="top-row col-start"id="06"></td>
            <td><input type="number" class="top-row"id="08"></td>
            <td><input type="number" class="top-row col-end"id="09"></td>
            </tr>
        <tr><td><input type="number" class="col-start"id="10"></td>
            <td><input type="number"id="11"></td>
            <td><input type="number" class="col-end"id="12"></td>
            <td><input type="number"class="col-start"id="13"></td>
            <td><input type="number"id="14"></td>
            <td><input type="number" class="col-end"id="15"></td>
            <td><input type="number"class="col-start"id="16"></td>
            <td><input type="number"id="17"></td>
            <td><input type="number" class="col-end"id="18"></td>
            </tr>
        <tr><td><input type="number" class="col-start bottom-row" id="20"></td>
            <td><input type="number" class="bottom-row"id="21"></td>
            <td><input type="number"class="bottom-row col-end"id="22"></td>
            <td><input type="number" class="col-start bottom-row"id="23"></td>
            <td><input type="number" class="bottom-row"id="24"></td>
            <td><input type="number"class="bottom-row col-end"id="25"></td>
            <td><input type="number" class="col-start bottom-row"id="26"></td>
            <td><input type="number" class="bottom-row"id="27"></td>
            <td><input type="number"class="bottom-row col-end"id="28"></td>
           </tr>
           <tr><td><input type="number" class="top-row col-start" ></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            <td><input type="number" class="top-row col-start"></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            <td><input type="number" class="top-row col-start"></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            </tr>
        <tr><td><input type="number" class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            <td><input type="number"class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            <td><input type="number"class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            </tr>
        <tr><td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
            <td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
            <td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
           </tr>
           <tr><td><input type="number" class="top-row col-start" ></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            <td><input type="number" class="top-row col-start"></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            <td><input type="number" class="top-row col-start"></td>
            <td><input type="number" class="top-row"></td>
            <td><input type="number" class="top-row col-end"></td>
            </tr>
        <tr><td><input type="number" class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            <td><input type="number"class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            <td><input type="number"class="col-start"></td>
            <td><input type="number"></td>
            <td><input type="number" class="col-end"></td>
            </tr>
        <tr><td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
            <td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
            <td><input type="number" class="col-start bottom-row"></td>
            <td><input type="number" class="bottom-row"></td>
            <td><input type="number"class="bottom-row col-end"></td>
           </tr>
        </tbody>
        </table>
      
    </div>
    <button type="submit" id="submit">Solve</button>
<script src="sudokuscript.js"></script>
</body>
</html>
