<template>
    <div class="section-container">

        <div class="left">
            <h3>FARM TO TABLE</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, officia dignissimos</p>

        </div>

        <div class="right">
            <button>READ OUR BLOG!</button>

        </div>



    </div>
</template>

<script>
export default {
    name: 'FarmtoTable'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.section-container {
    width: 65%;
    margin: auto;
    margin-top: 200px;
    margin-bottom: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .left {
        h3 {
            margin-bottom: 30px;
            font-weight: 100;
        }

        p {
            color: #67615a;
            margin-bottom: 40px;
        }

    }

    .right {

        button {
            background-color: #fc7523;
            border: none;
            border-radius: 2px;
            color: white;
            padding: 13px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 14px;
            font-weight: bold;
        }
    }







}
</style>