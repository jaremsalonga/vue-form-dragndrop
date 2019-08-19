<template>
   <div class="wrapper">
        <div id="background"></div>
        <div id="fab">&#43;</div>
        <header id="page-header"><a id="hamburger" href="#sidebar-nav" target="_self"><span class="line"></span><span class="line"></span><span class="line"></span></a></header>
        <nav id="sidebar-nav">
        <header id="sidebar-header"><a id="codepen-link" href="https://www.codepen.io/seanfree" target="_blank"></a>
            <div id="profile-info">
            <h3 id="profile-name">Sean Free</h3>
            <h4 id="blurb">Rogue Webonaut</h4>
            </div><a id="btn-more"><span class="dot"></span><span class="dot"></span><span class="dot"></span></a>
            <ul id="sidebar-nav-list">
            <li class="sidebar-nav-item" id="nav-item-home"><a href="#"><i class="material-icons">home</i>Home</a></li>
            <li class="sidebar-nav-item" id="nav-item-social"><a href="#"><i class="material-icons">people</i>Social</a></li>
            <li class="sidebar-nav-item" id="nav-item-mail"><a href="#"><i class="material-icons">mail</i>Mail</a></li>
            <li class="sidebar-nav-item" id="nav-item-pictures"><a href="#"><i class="material-icons">photo_library</i>Pictures</a></li>
            <li class="sidebar-nav-item" id="nav-item-music"><a href="#"><i class="material-icons">library_music</i>Music</a></li>
            <li class="sidebar-nav-item" id="nav-item-files"><a href="#"><i class="material-icons">folder</i>Files</a></li>
            <li class="sidebar-nav-item" id="nav-item-settings"><a href="#"><i class="material-icons">settings</i>Settings</a></li>
            <li class="sidebar-nav-item" id="nav-item-close"><a href="#"><i class="material-icons">close</i>Close</a></li>
            </ul>
        </header>
        </nav>
        <section>
            <three-column-layout></three-column-layout>
        </section>
        <a id="nav-screen-overlay" href="#" target="_self"></a>
    </div>
</template>
<script lang="ts">
import {Vue, Component} from 'vue-property-decorator';
import ThreeColumnLayout from '@/components/layouts/three-column-layout';
@Component({
    name: 'Home',
    components: {
        ThreeColumnLayout,
    },
})
export default class Home extends Vue {

}
</script>
<style lang="sass">

</style>