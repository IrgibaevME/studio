
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
</head>
 <body>
</body>
</html>


<SCRIPT SRC="jsMath/plugins/noImageFonts.js"> </SCRIPT>

<SCRIPT SRC="jsMath/jsMath.js"> </SCRIPT>

<DIV CLASS="math" >

\displaystyle V(x,t)=\int_0^t\int{{{f(\varepsilon\,r)}\over{R^n[{2a\sqrt{\pi(t-r)}]^n}}}*{\exp*\{{-\|x-\varepsilon\|^2\over{4a^2(t-r)}}\}}d\varepsilon}dr  
</DIV>
<br/>
<DIV CLASS="math">
0\,≤\,r\,≤\,t, \varepsilon\,\in\,R^n
</DIV>

<script type="text/javascript"> 
   jsMath.Process(document);
</script>



<DIV CLASS="math" id = "formula" >
   формула
<DIV CLASS="math" id = "formula2">
</DIV>
</DIV>

<input type="button" onClick="mathem()" value="В формулу">


 <script type="text/javascript"> 

   
   function mathem()
{
   var cg = '\\displaystyle V(x,t)=\\int_0^t\\int{{{f(\\varepsilon\\,r)}\\over{R^n[{2a\\sqrt{\\pi(t-r)}]^n}}}*{\\exp*\\{{-\\|x-\\varepsilon\\|^2\\over{4a^2(t-r)}}\\}}d\\varepsilon}dr'+ '<br>' +
    '0\\,≤\\,r\\,≤\\,t, \\varepsilon\\,\\in\\,R^n';
    document.getElementById("formula").innerHTML = cg;
jsMath.Process(document);


}

</script>




	
