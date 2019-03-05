<template>
    <header class="header-global">
        <base-nav class="navbar-main" type="" effect="light" expand fixed>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                Pupapedia
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#">
                        Home
                    </a>
                </li>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Services</span>
                    </a>
                    <router-link to="/landing" class="dropdown-item">Post your Puppy!</router-link>
                    <router-link to="/profile" class="dropdown-item">Service 2</router-link>
                    <router-link to="/login" class="dropdown-item">Service 3</router-link>
                </base-dropdown>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#">
                        Find a Puppy
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.facebook.com/creativetim" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.instagram.com/creativetimofficial"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
