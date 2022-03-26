<template>
    <div>
        <p>{{ name }}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Jieun'
        }
    },
    methods: {
        updateName() {
            this.name = 'Jieun Updated';
        }
    }    
}
</script>
