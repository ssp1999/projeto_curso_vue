<script>
import Banner from '../components/Banner.vue';
import BurguerForm from '../components/BurguerForm.vue';

export default {
    components: {
    Banner,
    BurguerForm
}
}
</script>

<template>
    <Banner />
    <div class="main-container">
        <h1>Monte o seu burguer:</h1>
        <BurguerForm />
    </div>
</template>
