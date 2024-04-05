<template lang="">
    <div id="box" class="">
        <div id="boxsm">
            <div class="mainBx">
                <div data-top>
                    <div class="dotOne"></div>
                    <div class="dotTwo"></div>
                    <div class="dotThree"></div>
                </div>
            </div>
            <div>
                <textarea class="t-editor">
                </textarea>
            </div>
        </div>
        <navBarCompVue />
    </div>
</template>
<script>
import navBarCompVue from './navBarComp.vue';
import TextEditorCompVue from './TextEditorComp.vue';
// import navBarCompVue
export default {
    components : {
        TextEditorCompVue,
        navBarCompVue
    }
}
</script>
<style scoped>

#box{
    min-height: 100vh;
    background: linear-gradient(rgb(0, 57, 93), rgb(26, 3, 152));
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    flex-direction: column;
}


#boxsm{
    border: 1px solid rgb(3, 146, 234);
    height: 600px;
    width: 801px;
    z-index: 23 !important;
    overflow: hidden;
    border-radius: 20px;
}

[data-top]{
    padding: 20px;
    display: flex;
    border-bottom: 1px solid white;
    flex-direction: row;
    gap: 30px;
    background: rgb(1, 1, 1);
}

.dotOne{
    height: 20px;
    width: 20px;
    background: red;
    border-radius: 50%;

}

.dotTwo{
    height: 20px;
    width: 20px;
    background: rgb(0, 242, 255);
    border-radius: 50%;
}

.dotThree{
    height: 20px;
    width: 20px;
    background: rgb(43, 255, 0);
    border-radius: 50%;
}

.t-editor{
    height: 537.5px;
    border: none;
    width: 800px;
    z-index: 0;
    background: rgb(25, 25, 25);
    color: whitesmoke;
}
.t-editor:hover{
    border: 1px solid rgb(47, 0, 255);
}
    
</style>