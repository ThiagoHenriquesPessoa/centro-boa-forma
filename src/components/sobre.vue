<template>
    <section class="sobre bloco scrollspy" id="sobre">
        <div class="row container">
            <div class="col s12 center">
                <h2 class="light">Sobre nós</h2>
            </div>
            <div class="col s12 l6">
                <p class="light">"Venha transformar sua vida no Centro de Treinamento Boa Forma! Aqui, dedicamos todos os
                    nossos esforços para ajudar você a atingir seus objetivos de saúde e bem-estar. Com uma equipe de
                    instrutores altamente qualificados e equipamentos de última geração, oferecemos um ambiente acolhedor e
                    motivador para o seu treinamento.

                    No Boa Forma, a personalização é a chave. Criamos programas sob medida para atender às suas necessidades
                    e metas específicas. Se você busca emagrecimento, ganho de massa muscular, condicionamento físico ou
                    simplesmente um estilo de vida mais saudável, estamos aqui para guiá-lo a cada passo do caminho.

                    Além disso, oferecemos uma variedade de aulas, desde yoga e pilates até treinamento funcional e HIIT,
                    para manter sua rotina sempre desafiadora e interessante. Nossa missão é garantir que você alcance a sua
                    melhor versão.

                    Não espere mais para investir em si mesmo. Junte-se a nós no Centro de Treinamento Boa Forma e descubra
                    o caminho para uma vida mais saudável, feliz e cheia de energia. Sua transformação começa aqui!"</p>
            </div>
            <div class="col s12 l6">
                <div class="carousel carousel-slider" data-indicators="true">
                    <a href="#" class="carousel-item">
                        <img src="../assets/banner-01.jpg">
                    </a>
                    <a href="#" class="carousel-item">
                        <img src="../assets/banner-02.jpg">
                    </a>
                    <a href="#" class="carousel-item">
                        <img src="../assets/banner-03.jpg">
                    </a>
                </div>
            </div>
        </div>
        <div class="row blue-logo missao-visao-valores">
            <div class="container">
                <article class="item col s12 m4 center">
                    <span class="icon"><i class="material-icons medium">directions_run</i></span>
                    <h3 class="light">Missão</h3>
                    <p class="light">O Centro de Treinamento Bem Estar busca capacitar indivíduos a atingir
                        saúde e bem-estar, fornecendo treinamento personalizado e um ambiente motivador.
                        Inspiramos mudanças positivas para vidas mais saudáveis e equilibradas.</p>
                </article>

                <article class="item col s12 m4 center">
                    <span class="icon"><i class="material-icons medium">visibility</i></span>
                    <h3 class="light">Visão</h3>
                    <p class="light">Nossa visão no Centro de Treinamento Bem Estar é ser um farol de
                        inspiração e inovação em saúde e bem-estar, promovendo vidas saudáveis e
                        vibrantes para nossa comunidade. Buscamos liderar pelo exemplo e oferecer as
                        melhores práticas para uma transformação positiva.</p>
                </article>

                <article class="item col s12 m4 center">
                    <span class="icon"><i class="material-icons medium">grade</i></span>
                    <h3 class="light">Valores</h3>
                    <p class="light">No Centro de Treinamento Bem Estar, nossos valores fundamentais
                        incluem comprometimento com a excelência, respeito à diversidade, integridade
                        inabalável, empatia sincera e apoio à comunidade. Estes princípios norteiam
                        nossa jornada de promover uma vida saudável e equilibrada para todos.</p>
                </article>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}

$(document).ready(function () {
    //CAROUSEL
    $(".carousel.carousel-slider").carousel({
        fullwidth: true,
        indicators: true
    });
});
</script>

<style>
.sobre {
    background-image: url('../assets/textura1.png');
}

.sobre h2 {
    font-size: 2rem;
    color: #212121;
    text-transform: uppercase;
}

.sobre h2::after {
    content: '';
    display: block;
    width: 100px;
    border-top: 1px solid #2dc7d0;
    margin: 15px auto;
}

.sobre p {
    line-height: 1.8rem;
    text-align: justify;
}

.sobre .missao-visao-valores {
    padding: 20px 0;
    margin-top: 20px;
}

.sobre .missao-visao-valores .icon {
    color: #fff;
}

.sobre .missao-visao-valores h3 {
    font-size: 1.5rem;
    color: #fff;
    text-transform: uppercase;
}

.sobre .missao-visao-valores p {
    color: #fff;
    text-align: center;
}</style>