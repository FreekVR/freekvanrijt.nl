<template>
    <article class="wrapper">
        <header>
            <h5 class="company">
                <slot name="company"></slot>
            </h5>
            <h5>
                <slot name="position"></slot>
            </h5>
            <small class="location">
                <slot name="location"></slot>
            </small>

            <small class="period">
                :&nbsp;{{ from }}&nbsp;-&nbsp;{{ to }}
            </small>
        </header>

        <div class="description">
            <slot name="description"></slot>
        </div>
    </article>
</template>

<script setup lang="ts">
defineProps({
    from: {
        type: String,
        required: true,
    },
    to: {
        type: String,
        required: false,
        default: 'now',
    },
});
</script>

<style scoped>
.wrapper {
    margin-top: 28px;
}

h5 {
    margin: 0;
}

h5.company {
    font-size: 18px;
}

small.period,
small.location {
    font-size: 12px;
}

h5.positon {
    font-size: 15px;
}

.description {
    font-size: 14px;
    font-weight: 200;

    margin-top: 14px;
}
</style>
