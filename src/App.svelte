<script>
  let name = "bharath";

  setTimeout(() => {
    name = "Ranga";
  }, 3000);

  let a = 10;
  let b = 20;

  let myHtml = "<strong>bharath</strong>";

  let src = "/favicon.png";
  let channelName = "favicon";

  let disabled = false;
</script>

<style>
</style>

<img {src} width="150" alt="{channelName}" />

<input type="text" value="Text" {disabled}>


<h1>Hello, {name}</h1>

<h1>{a} + {b} = {a + b}</h1>

<div>
  some text
  {@html myHtml}
</div>
