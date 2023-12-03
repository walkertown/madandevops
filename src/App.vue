<template>
    <!-- <navbar
        :pages="pages"
        :active-page="activePage"
        :nav-link-click="(index) => activePage = index"
    ></navbar> -->

    <page-viewer
        :page="pages[activePage]"
    ></page-viewer>
</template>

<script>
import Navbar from './components/Navbar.vue';
import PageViewer from './components/PageViewer.vue';


export default {
    components: {
        Navbar,
        PageViewer
    },
    data() {
        return {
            activePage: 0,
            pages: [
                {
                    link: {text: 'Home', url: 'index.html'},
                    pageTitle: 'Home Page',
                    content: 'This is the home content'
                },
                {
                    link: {text: 'About Us', url: 'about.html'},
                    pageTitle: 'About Us Page',
                    content: 'This is the about content'
                },
                {
                    link: {text: 'Courses', url: 'courses.html'},
                    pageTitle: 'Courses Page',
                    content: 'This is the courses page'
                },
                {
                    link: {text: 'Contact Us', url: 'contact.html'},
                    pageTitle: 'Contact Page',
                    content: 'This is the Contact Us page'
                }
            ]
        };
    },
}    
</script>