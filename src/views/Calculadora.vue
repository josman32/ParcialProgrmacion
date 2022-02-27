<template>
    <div class="h-screen bg-gray-100 text-default">
        <header-title title="CALCULADORA"/>
        <Calculador/>
    </div>
</template>
<script>
import HeaderTitle from'../components/HeaderTitle.vue'
import Calculador from'../components/Calculador.vue'
export default {
    components:{
        HeaderTitle,
        Calculador
    }
}
</script>