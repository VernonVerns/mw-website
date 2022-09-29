<script lang="ts" setup>
    const reloadPage = () => {
        window.location.reload();
    }
</script>
<template>
    <nav class="navbar navbar-expand-md navbar-light" id="navigation_bar">
        <div class="container-fluid">
             <a class="navbar-brand" href="#">
                <img src="@/assets/img/icon-logo.png" alt="">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
           
            <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" @click="reloadPage">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about_us">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#our_services" >Services</a>
                    </li>
                    <li class="nav-item contact-btn">
                        <a class="nav-link main-btn" href="#contact_us" >Contact Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>