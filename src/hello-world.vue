<template>
    <div
        :class="textColorClass"
    >
        Hello {{whom}}
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
            whom: 'World',
        }
    },

    methods: {}

}
</script>