
<!-- sevelte doesnt provide any sanitization for html strings inserted into the DOM -->
<script>
    let string = 'This is a test html string <b>hiii hello</b>'
</script>

<p>{@html string}</p>