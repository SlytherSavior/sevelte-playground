<!--deep reactivity in svelte-->

<script lang="ts">
    let num = $state([1,2,3,4,])
    function addNumber(){
        num.push(num.length + 1);
    }
    function removeNumber(){
        num.pop();
    }
</script>


<p>{num.join(' + ')} ...</p>
<button onclick={addNumber}>Add Number</button>
<button onclick={removeNumber}>Remove Number</button>