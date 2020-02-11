<template>
    <div>
        <nav class="navbar navbar-default">
            <div class="containter-fluid">
                <router-link to="/" class="navbar-brand"> Stock Trader </router-link>
                <div class="collapse navbar-collapse">
                    <ul class="navbar-nav nav">
                        <!-- <router-link to="/" activeClass="active" tag="li"><a>Home</a></router-link> -->
                        <router-link to="/portfolio" tag="li" activeClass="active"><a>Portfolio</a></router-link>
                        <router-link to="/stocks" tag="li" activeClass="active"><a>Stocks</a></router-link>
                    </ul>
                    <ul class="nav navbar-nav navbar-right">
                        <li><a href="#">End Day</a></li>
                        <li class="dropdown">
                            <a 
                                href="#" 
                                class="dropdown-toggle" 
                                data-toggle="dropdown" 
                                role="button"
                                aria-haspopup="true"
                                aria-expanded="false"> Save & Load <span class="caret"></span>
                            </a>
                            <ul class="dropdown-menu">
                                <li><a href="#">Save Data</a></li>
                                <li><a href="#">Load Data</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

     
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>