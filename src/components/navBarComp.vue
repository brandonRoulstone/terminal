<template lang="">
    <div id="newNav">
        <span id="icX">⛅️ <span id="icT">sunny</span>
    </span>
        hello world
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    #newNav{
        background: rgb(249, 249, 249);
        padding-top: 0px;
        padding-bottom: 16px;
        padding-left: 16px;
        padding-right: 16px;
        display: flex;
        width: 100%;
        position: absolute;
        bottom: -5%;
        border-top: 1px solid rgb(0, 110, 253);
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    #newNav:hover{
        background: rgb(249, 249, 249);
        /* padding-top: 0px;
        padding-bottom: 16px;
        padding-left: 16px;
        padding-right: 16px; */
        display: flex;
        width: 100%;
        position: absolute;
        bottom: 0%;
        transition: 0.3s ease-in-out;
        border-top: 1px solid rgb(0, 110, 253);
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    #icX{
        text-align: start;
        font-size: 25px;
        color: black;
    }

    #icT{
        font-size: 15px;
    }
</style>