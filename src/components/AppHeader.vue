<script>
export default {
    name:'AppHeader',
};
</script>
<template>
    <!--Inizio Header-->
    <header>
        <!--Contenitore interno all'header-->
        <div class="container1">

            <div class="row1">
                <!--Tre colonne (due da 25% e una da 50%)-->
                <div class="col-25">

                    <div class="header-content text-left py-10 unstyled-list">

                        <ul>
                            <li>
                                <a href="#">Donna</a>
                            </li>

                            <li>
                                <a href="#"> Uomo</a>
                            </li>

                            <li>
                                <a href="#">Bambini</a>
                            </li>
                        </ul>

                    </div>

                </div>

                <div class="col-50">

                    <div class="header-content text-center">

                        <img src="/img/boolean-logo.png" alt="Logo">
                    </div>

                </div>
                
                <div class="col-25">

                    <div class="header-content">

                        <div class="header-content text-right py-10 unstyled-list">
                            <ul>

                                <li>
                                    <i class="fa-solid fa-user"></i>
                                </li>

                                <li>
                                    <i class="fa-regular fa-heart"></i>
                                </li>

                                <li>
                                    <i class="fa-solid fa-bag-shopping"></i>
                                </li>

                            </ul>

                        </div>

                    </div>

                </div>
            </div>
        </div>
    </header>

    <!--Fine Header-->

</template>