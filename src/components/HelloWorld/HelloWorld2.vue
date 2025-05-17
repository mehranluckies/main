<template>
    <h1>
        salam {{ msg }} khoshumadi be {{ notif }}
    </h1>
</template>



<script>
export default {
    props:{
        msg : String,
        notif: String
    }
}

</script>