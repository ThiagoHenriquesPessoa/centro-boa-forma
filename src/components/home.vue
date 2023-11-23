<template>
    <section class="home bloco scrollspy" id="home">
        <div class="row container banner">
            <div class="col s12 center">
                <h2 class="white-text">O melhor treinamento funcional da região.</h2>
                <p class="white-text light">Um novo conceito em prevenção, promoção e reabilitação da saude para quem busca
                    melhora do
                    condicionamento e emagrecimento, alem de ser divertido e desafiador. Quer experimentar?</p>
                <div class="row">
                    <a href="#sobre" class="btn btn-large blue-logo">Sobre nós</a>
                    <a href="#contato" class="btn btn-large white black-text">Contato</a>
                </div>
            </div>
        </div>
    </section>
</template>
  
<script>
export default {
    name: 'home',
    components: {
    }
}
</script>

<style>
.blue-logo {
    background-color: #2dc7d0;
}

.bloco {
    min-height: 100%;
    min-width: 100%;
    padding-top: 94px;
    padding-bottom: 94px;
}

.home {
    animation: mudarbg 20s infinite;
    background-image: url('../assets/bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

.banner {
    display: flex;
    align-items: center;
    justify-content: center;
}

.banner h2 {
    font-size: 2.5rem;
    font-weight: 900;
    text-transform: uppercase;
}

.banner p {
    font-size: 1.2rem;
    line-height: 1.8rem;
}

/* home animation */
@keyframes mudarbg {
    40% {
        background-image: url('../assets/bg2.jpg');
    }

    80% {
        background-image: url('../assets/bg3.jpg');
    }

    100% {
        background-image: url('../assets/bg.jpg');
    }
}</style>