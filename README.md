Anima--o
========

&lt;canvas id="tela" width="1000" height="400" >&lt;/canvas>  &lt;script>  var tela= document.getElementById("tela"); var c = tela.getContext("2d");  var circulo= function(x,y,raio){ c.strokeStyle="orange"; c.beginPath(); c.arc(x,y,raio,0,2*Math.PI); c.stroke(); }  var x=1;   var desenha= function(){ circulo(x,100,x/2); x=x+1; }  setInterval(desenha, 30);    &lt;/script>
