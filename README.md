# calculator
Creating a simple calculator

<div id="display-field">
<?php
if (isset($_GET['submit'])){
$result1= $_GET['num1'];
$result2= $_GET['num2'];
$operator= $_GET['operator'];
switch($operator){
case"+";
echo $result1 + $result2;
case"-";
echo $result1 - $result2;
case"*";
echo $result1 * $result2;
case"/";
echo $result1 / $result2;

}

}

</div>
