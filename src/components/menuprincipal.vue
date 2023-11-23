<template>
    <header>
        <!-- MENUMOBILE -->
        <ul class="sidenav" id="menu-mobile">
            <li><a class="hide-menu" href="#home">Home</a></li>
            <li><a class="hide-menu" href="#sobre">Sobre a Boa Forma</a></li>
            <li><a class="hide-menu" href="#servicos">Serviços</a></li>
            <li><a class="hide-menu" href="#unidades">Unidades</a></li>
            <li><a class="hide-menu" href="#contato">Contatos</a></li>
        </ul>

        <div class="navbar-fixed">
            <nav class="navbar z-depth-0">
                <div class="nav-wrapper container">

                    <h1 class="logo_text">Centro Boa Forma - Seu espaço de saúde</h1>

                    <a href="#">
                        <img class="logo_img" src="../assets/logo.png" alt="Centro Boa Forma">
                    </a>

                    <ul class="right light hide-on-med-and-down">
                        <li><a class="hide-menu" href="#home">Home</a></li>
                        <li><a class="hide-menu" href="#sobre">Sobre a Boa Forma</a></li>
                        <li><a class="hide-menu" href="#servicos">Serviços</a></li>
                        <li><a class="hide-menu" href="#unidades">Unidades</a></li>
                        <li><a class="hide-menu" href="#contato">Contatos</a></li>
                    </ul>

                    <a href="#" class="sidenav-trigger right" data-target="menu-mobile">
                        <i class="material-icons">menu</i>
                    </a>
                </div>
            </nav>
        </div>
    </header>
</template>
  
<script>
export default {
    name: 'menuprincipal',
    components: {

    }
}
</script>

<style>
.navbar {
    background-color: transparent;
    transition: background 0.5s linear;
}

.navbar ul a:hover {
    background-color: transparent;
    color: #2dc7d0;
}

.nav-color {
    background-color: rgba(0, 0, 0, 0.7);
    transition: background 0.5s linear;
}

nav { color: #fff; background-color: #ee6e73; width: 100%; height: 94px; line-height: 94px;}
  nav.nav-extended .nav-wrapper { min-height: 94px; height: auto; }
  .navbar-fixed { position: absolute; height: 94px; z-index: 997; }  
  nav i,
  nav [class^="mdi-"], nav [class*="mdi-"],
  nav i.material-icons, nav a.button-collapse i { display: block; font-size: 24px; height: 94px; line-height: 94px; }

.sidenav{ background: url('../assets/textura2.png'); }
.sidenav li>a{color: #fff; font-weight: 100; }

.logo_text{ font-size: 0; margin: 0;}
.logo_img{ width: 100px; margin-top: 15px;}

</style>