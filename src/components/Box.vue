<template>
    <div class="box has-text-wight-bold" :style="estilos">
        <slot></slot>
    </div>
</template>


<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'box-component',
    data() {
        return {
            estilos: {
                backgroundColor: '#FAF0CA'
            }
        }
    }
})
</script>