<script>
    let changeT = "THIS IS MY FIRST APP";
    function chngeText(){
        changeT = "I CHANGED THE TEXT";
    }
</script>
<h1>{changeT}</h1>
<button on:click={chngeText}>Change text</button>