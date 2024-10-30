<template>
    <div>
        <h1>Wbe02</h1>
        <UiBtttn></UiBtttn>
        key: {{ key }}
    </div>
</template>

<script setup>
import { key } from "~ui/constants/key";

const _key = ref(key);
</script>
