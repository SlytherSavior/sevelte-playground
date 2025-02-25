<!-- props in svelte-->
 <script>
    import Nested from './nested.svelte';
    const question =  {
        details : "3 * 7",
        answer : " 21" ,
        maker :'Shrijan'
    };
 </script>

 <Nested  {...question}/>