<template>
    <div
        :class="textColorClass"
    >
        Hello {{name}}
    </div>
</template>

<script>
export default {

    name: 'hello-world',

    props: {
        textColorClass: {
            type: String,
            default: 'text-blue-500'
        }
    },

    data() {
        return {
            name: 'World',
        }
    },

    methods: {}

}
</script>