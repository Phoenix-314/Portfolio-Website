# Portfolio-Website

<!-- Step 1: include our secure javascript file -->
<script src="https://www.desmos.com/api/v1.11/calculator.js?apiKey=43d977e4842645a3af10774fdc89d42c"></script>

<!-- Step 2: add an element to the page -->
<div id="calculator" style="width: 600px; height: 400px;"></div>

<!-- Step 3: add the following lines of javascript -->
<script>
    var elt = document.getElementById('calculator');
    var calculator = Desmos.GraphingCalculator(elt);
</script>
