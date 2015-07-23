# RT_14_Tonenchuk
<!DOCTYPE html> 
<html> 
<head> 
<script src="http://code.jquery.com/jquery-latest.js"> 
</script> 
<script>
var m = prompt("Введите число","");
m = parseInt(m);
var res = 0;
var bin_m="";
var rev_m="";
while (m>0)
{
rev_m = rev_m + (m%2);
bin_m = (m%2) + bin_m;
res = res*2 + (m%2);
m=Math.floor(m/2);
}
document.write("Результат : "+bin_m+" bin<br/> Обратный код: "
+ rev_m+" bin<br/> Десятичный вид: "+res + " dec");
</script> 
</head> 
<body> 
</body> 
</html>
