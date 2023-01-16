# x
Objects created with an array index
<!DOCTYPE html>
<html>
<body>

<button id="1" onclick='test(event)'>The Element Object</button>




<p id="demo"></p>
<p id="demo1"></p>
<p id="demo2"></p>

<script>
var y;
function test(event) {
let temp = event.target;
y = temp.id;
const xx = {};
xx[y] = 'sasuke';
xx.stronzo = 'kk';
document.getElementById("demo").innerHTML = xx.stronzo + ' +  ' + xx[y];
document.getElementById("demo1").innerHTML = xx[y];
document.getElementById("demo2").innerHTML = xx.y;
}
/*the object now should be
xx = {
stronzo: 'kk',
y:'sasuke'
or not?
}*/

</script>

</body>
</html>
