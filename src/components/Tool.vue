<template>
    <div class="tool">
        <div class="container">
            <div class="logo">
                Toskia
            </div>
            <din class="but">
                <button class="btn"> try free</button>
            </din>
        </div>
    </div>
</template>
<script>
export default {
    name:'Tool'
}
</script>
<style lang="scss" scoped>
.tool{
    .container{
        display: flex;
        justify-content: space-between;
        padding-top: 20px;
        .logo{
            color: #525FFB;
            font-size: 30px;
            font-weight: bold;
        }
        .but{
            button{
                text-transform: capitalize;
            padding-block-end: 10px;
            border: 1px solid #525FFB;
            border-radius: 20px;
            font-weight: bold;
            color: #525FFB;
            }
        }
    }
}
</style>