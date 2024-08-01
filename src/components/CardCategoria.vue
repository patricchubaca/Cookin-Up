<script lang="ts">
import type ICategoria from '@/interfaces/ICategoria';
import type { PropType } from 'vue';
export default {
    props: {
        categoria: { type: Object as PropType<ICategoria>, required: true }
    }
}
</script>

<template>
    <article class="categoria">
        <header class="categoria_cabecalho">


        </header>

    </article>
    {{ categoria.nome }}
    {{ categoria.ingredientes }}
</template>
