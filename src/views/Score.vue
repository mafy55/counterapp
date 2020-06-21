<template>
 <div class="page">
<h1>スコア表示</h1>
<p>{{ score }}</p>
 </div>
</template>

<script>
export default {
    data (){
        return {
            
        }
    },
    computed:{
        score(){
            return this.$store.getters.count
        }

    }
}
</script>