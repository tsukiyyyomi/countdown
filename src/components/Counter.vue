<template>
    <div>
        <h3>{{displayDays}}:{{displayHours}}:{{displayMinutes}}:{{displaySeconds}}</h3>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                displayDays: 0,
                displayHours: 0,
                displayMinutes: 0,
                displaySeconds: 0

            }
        }
    }
</script>

<style lang="scss" scoped>

</style>