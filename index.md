##calculadora javascript 

desenvolvemos um calculadora simples em javascript para a aula de desenvolvimento colaborativo de software



```markdown
<html>
<input type="number" id="num1">
<input type="number" id="num2">
<button onclick="Myfunction()">adicionar</button>
    <button onclick="Myfunction1()">subtrair</button>
    <button onclick="Myfunction2()">dividir </button>
    <button onclick="Myfunction3()">multiplicar </button>
    <script>
    function Myfunction(){
    var num1= document.getElementById("num1").value;
       var num2= document.getElementById("num2").value;
        var conta=(num1*1+num2*1);
         
        window.alert(conta);}
        
         function Myfunction1(){
    var num1= document.getElementById("num1").value;
       var num2= document.getElementById("num2").value;
        var conta=(num1*1-num2*1);
         
        window.alert(conta);}
        function Myfunction2(){
    var num1= document.getElementById("num1").value;
       var num2= document.getElementById("num2").value;
        var conta=(num1*1/num2*1);
         
        window.alert(conta);}
        function Myfunction3(){
    var num1= document.getElementById("num1").value;
       var num2= document.getElementById("num2").value;
        var conta=(num1*1*num2*1);
         
        window.alert(conta);}
    </script>
</html>
```

