<template>
    <div class="alert alert-success" role="alert">{{ message }}</div>
    <br/>
</template>

<script>
export default {
    props: ['message'],
};
</script>