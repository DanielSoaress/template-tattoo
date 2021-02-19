<template>
    <div class="button">
        <a href="#">
            <img src="../assets/img/whatsapp.png" alt="Whatsapp" width="20" height="20"> 
        Faça seu Orçamento</a>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .button {
        position: fixed;
        bottom: 20px;
        right: 20px;
    }

    .button a {
        text-decoration: none;
        padding: 10px 20px;
        color: #ca9e67;
        border-style: solid;
        border-width: 1px;
        border-color: #ca9e67;
        text-transform: uppercase;
    
        background-color: rgba(0, 0, 0, 0.8);  
        box-shadow: 5px 5px 20px black;
        font-weight: 300;
        font-size: 0.875em;
        font-family: 'Roboto', Helvetica, Arial, sans-serif;

        display: flex;
        align-items: center;
    }
    .button a:hover {
        text-decoration: underline 2px;
    }

    .button a img {
        display: block;
        margin-right: 5px;
    }


</style>