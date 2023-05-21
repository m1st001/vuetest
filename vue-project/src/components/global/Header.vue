<template>
    <div class="container">
        <nav class="navbar navbar-expand-lg bg-body-tertiary border border-secondary rounded-bottom">
        <div class="container-fluid mx-3">
            <a class="navbar-brand" href="#">m1.Events</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                <a class="nav-link" href="#">About</a>
                </li>
            </ul>
            <form class="d-flex" role="search">
                <button class="btn btn-outline-primary" type="submit"><i class="bi-arrow-bar-right"></i> Log In</button>
            </form>
            </div>
        </div>
        </nav>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { RouterLink } from 'vue-router';

    export default defineComponent({
        
    })
</script>

<style scoped>
</style>