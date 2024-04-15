
    This is our FHIR Implementation Guide. It contains the specifications developed by our community, etc etc.


---

<h1>Now with some JavaScript</h1>

<button id="demoButton">Click me!</button>
<p id="demoText"></p>

<script>
document.getElementById("demoButton").addEventListener("click", function() {
    document.getElementById("demoText").innerHTML = "See? This page contains JavaScript, and that can be dangerous!";
    this.setAttribute("disabled", "true");
});
</script>

