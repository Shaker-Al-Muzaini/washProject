<script setup>
import { Head, Link } from '@inertiajs/vue3';
import FooterLayout from "@/Layouts/FooterLayout.vue";
import MeunLayout from "@/Layouts/MeunLayout.vue";

</script>

<template>
    <Head title="Home" />

    <div class="wrapper">

        <nav class="main-header navbar navbar-expand navbar-white navbar-light">

            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" data-widget="pushmenu" href="#" role="button"><i class="fas fa-bars"></i></a>
                </li>

            </ul>


        </nav>


       <MeunLayout/>

        <div class="content-wrapper">

            <slot/>

        </div>


        <aside class="control-sidebar control-sidebar-dark">

            <div class="p-3">
                <h5>Title</h5>
                <p>Sidebar content</p>
            </div>
        </aside>

     <FooterLayout/>
    </div>
</template>

<style>

</style>
