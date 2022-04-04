<template>
    <div class="news container">
       <h2>News</h2>
        <NewsList /> 
    </div>
</template>

<script>
import NewsList from '@/components/NewsList.vue';
export default {
    data() {
        return {};
    },
    components: {
        NewsList
    }
};
</script>

<style>
/* Add any component specific styles here */

.card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    max-width: 300px;
    margin: auto;
    text-align: center;
    font-family: arial;
    border-radius: 5px;
    border: 1px solid #ccc;
    height: 400px;
}
/* .news-container{
    margin-left: auto;
    margin-right: auto;
} */
 .news__item{
    display: inline-block;
    /* display: inline-flex; */
    margin-right: 80px;
    justify-content: center;
}
.blank{
    height: .2rem;
    background-color: #0b5ed7;
    margin-top: .5rem;
}
</style>