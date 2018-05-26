<template>
    <span :class="[btnClass,cname]">
        <slot/>
    </span>
</template>

<script>
export default {
    props: {
        cname: {
            type: String,
            default: "",
        },
    },
    data () {
        return {
            btnClass: "btn",
        }
    },
}
</script>

<style lang="scss">
@import "../css/element.scss";
.btn {
  @include btn;
}
</style>
