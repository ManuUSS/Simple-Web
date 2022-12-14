<template>
    <nav class="uk-navbar-container uk-navbar-transparent" uk-navbar>
        <div class="uk-navbar-left">
            <ul class="uk-navbar-nav">
                <li class="uk-main">Manuel's Web</li>
            </ul>
        </div>
        <div class="uk-navbar-right">
            <ul class="uk-navbar-nav">
                <li class="uk-active"><a href=""></a></li>
                <li class="uk-parent"><a href="">Sections</a></li>
                <li class="uk-parent"><a href="">About me</a></li>
            </ul>
        </div>
    </nav>
</template>
<style lang="scss" scoped>
    uk-navbar-container {
        position: absolute;
        color: #000;
    }

    .uk-navbar-nav {
        li {
            a {
                color: #fff;
            }
        }

        .uk-main {
            font-size: 1.5rem;
            font-weight: 600;
            color: #fff;
            margin: 0 1rem;
        }
    }




    nav {
        padding: 0;
    }
</style>