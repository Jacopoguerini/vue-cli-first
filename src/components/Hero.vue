<template>
    <div id="jumbotron">
        <div>
            <h2>Hello World!</h2>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    #jumbotron {
        width: 100%;
        height: 500px;
        position: relative;
        background-color: rgba(33, 56, 54, 0.404);
        box-shadow: 0 0 10px rgba(33, 56, 54, 0.404);
    }

    h2 {
        color: whitesmoke;
        font-size: 50px;
        text-shadow: 0 0 10px black;
    }
    #jumbotron > div {
        position: absolute;
        top: 30%;
        left: 30%;
        transform: translate(-50%, -50%);
    }
</style>