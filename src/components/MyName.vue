<template>
    <div>
        <p> Welcome, {{ name }}! </p>
    </div>    
</template>

<script>
export default {
    name: 'MyName',
    props: {
        name: {
            type: String,
            required: true
        }
    }
}
</script>

<style scoped>
p {
    font-weight: 1000;
    font-size: 1.5rem;
    color: #5e1010;
}
</style>