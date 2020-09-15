<script>
  let name = "bharath";

  setTimeout(() => {
    name = "Ranga";
  }, 3000);

  let a = 10;
  let b = 20;

  let myHtml = "<strong>bharath</strong>"


</script>

<style>
</style>

<h1>Hello, {name}</h1>

<h1>{a} + {b} = {a + b}</h1>

<div>some text {@html myHtml}</div>
