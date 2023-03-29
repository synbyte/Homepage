<form onSubmit="javascript:goS();">
<input id='q' type="text">
<button type="submit">Go</button>
</form>
<script>
const q = document.getElementById("q").value
function goS() {
  window.open("https://google.com/search?="+q);
}
</script>
<style>
form {
  width:100%;
}
input {
  
}
</style>