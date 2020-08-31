<template>
    <div>
        <div class="progress-container">
            <div class="progress-bar" :style="{ width: progress + '%' }">
                {{progress + '%'}}
            </div>
        </div>
    </div>
</template>
<script>
    export default{
        props:['progressEl'],
        data(){
            return{
                progress:20,
            }
        },
    }
</script>