<template>
    <div>this is 1-2-2
        <input type="text">
        <router-link :to="'/nested/menu1/menu1-2/edit'">进入详情页</router-link>
    </div>
</template>
<script>
export default {
  name: 'menu122',
};
</script>