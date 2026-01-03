## Dynamic Footer

This footer shows the current date dynamically using JavaScript.

```html
<footer class="site-footer">
  <p>© <span id="current-date"></span> CloudAdvisory. All rights reserved.</p>
</footer>

<script>
  const today = new Date();
  document.getElementById("current-date").innerText =
    today.toDateString();
</script>

