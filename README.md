Php -Sort functions for array

1)sort()-It sorts array in ascending order.
<!DOCTYPE html>
<html>
<body>

<?php
$names = array(rita,sita,gita);
sort($names);

$arrlength = count($names);
for($c = 0; $c < $arrlength; $c++) {
  echo $names[$c];
  echo "<br>";
}
?>

</body>
</html>



2)rsort()-sorts array in descending order

<!DOCTYPE html>
<html>
<body>

<?php
$names = array(rita,sita,gita);
rsort($names);

$arrlength = count($names);
for($c = 0; $c < $arrlength; $c++) {
  echo $names[$c];
  echo "<br>";
}
?>

</body>
</html>

3)asort()-sorts the associative array in ascending order according to the value

<!DOCTYPE html>
<html>
<body>

<?php
$age = array("Puspa"=>"35", "Alina"=>"37", "Tauko"=>"43");
asort($age);

foreach($age as $x => $x_roll) {
  echo "Name=" . $x . ", Rollno=" . $x_roll;
  echo "<br>";
}
?>

</body>
</html>


4)ksort()-sorts the associative array in ascending order according to the key

<!DOCTYPE html>
<html>
<body>

<?php
$age = array("Puspa"=>"35", "Alina"=>"37", "Tauko"=>"43");
ksort($age);

foreach($age as $x => $x_roll) {
  echo "Name=" . $x . ", Rollno=" . $x_roll;
  echo "<br>";
}
?>


5)arsort()-sorts the associative array in descending order according to the value
<!DOCTYPE html>
<html>
<body>

<?php
$age = array("Puspa"=>"35", "Alina"=>"37", "Tauko"=>"43");
arsort($age);

foreach($age as $x => $x_roll) {
  echo "Name=" . $x . ", Rollno=" . $x_roll;
  echo "<br>";
}
?>

6)krsort()-sorts the associative array in descending orrder according to the key
<!DOCTYPE html>
<html>
<body>

<?php
$age = array("Puspa"=>"35", "Alina"=>"37", "Tauko"=>"43");
krsort($age);

foreach($age as $x => $x_roll) {
  echo "Name=" . $x . ", Rollno=" . $x_roll;
  echo "<br>";
}
?>


