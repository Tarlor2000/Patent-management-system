<template>
    <header>
        <div class = 'logo one'>
            <img src="../assets/icons/ze-star 1.svg" />
        </div>
        <h2>专利管理系统</h2>
        <div class = 'people'>
            <h4>吱吱</h4>
            <h4>业务录入人员</h4>
        </div>
        <div class = 'logo two'>
            <img src="../assets/icons/fa-user.svg" />
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<script setup lang="ts">

</script>

<style scoped>
    header {
        width: 100%;
        height: 68px;
        background-color: #000000;
        color :#ffffff
    }
    header h2 {
        font-weight: normal;
        line-height: 68px;
        font-size: 28px;
        float: left;
    }
    .logo {
        height: 68px;
        margin:0 15px;
        line-height: 68px;
    }
    .one {
        float: left;
    }
    .people {
        float: right;
        font-size: 12px;
        margin: auto 0;
        display: flex;           /* 新增 */
        flex-direction: column;  /* 新增 */
        justify-content: center; /* 新增 */
        height: 68px;            /* 新增，确保与 header 高度一致 */
        margin-right: 40px;
    }
    .people h4 {
        margin:0 auto;
        font-size:10px;
        color:rgba(159, 184, 236, 1)
    }
    .two {
        float: right;
    }
</style>