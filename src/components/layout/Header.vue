<template lang="pug">
    section.hero.is-dark
        .hero-head
            nav.nav
                .container
                    .nav-left
                        router-link.navbar-item(to="/")
                            h1.title Daniel Pereira
                    .nav-right
                        span.tabs
                            span.container
                                ul
                                    li
                                        router-link.navbar-item(to='/about') Sobre mi
                                    li
                                        router-link.navbar-item(to='/projects') Proyectos
                                    li
                                        router-link.navbar-item(to='/articles') Articulos
                                    li
                                        router-link.navbar-item(to='/certifications') Certificaciones
</template>

<style lang="sass" scoped>
.hero
    margin-top: 5px
</style>