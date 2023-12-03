<template>
    <nav
        :class="[`navbar-${theme}`, `bg-${theme}`, `navbar`, `navbar-expand-lg`]">

        <div class="container-fluid">
            <a class="navbar-brand" href="#">RAM IT</a>
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li v-for="(page, index) in pages" class="nav-item" :key="index">
                    <a
                        class="nav-link"
                        :class="{active: activePage == index}"
                        aria-current="page"
                        :href="page.link.url"
                        :title="`This link goes to the ${page.link.text} page`"
                        @click.prevent="navLinkClick(index)"
                    >{{ page.link.text }}</a>    
                </li>
            </ul>            
        </div>
    </nav>
</template>

<script>
export default {
    props: ['pages', 'activePage', 'navLinkClick'],
    data() {
        return {
            theme: 'dark',
        }
    },
}
</script>