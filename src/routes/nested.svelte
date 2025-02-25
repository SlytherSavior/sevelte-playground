<script>
    //default values can be assigned as well
    let {answer = 21, question = '3 * 7' , maker = 'teacher'} = $props();
</script>

<p>The question is {question}! The answer is {answer}. The question maker is {maker}!</p>