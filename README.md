# tcc_escola_da_nuvem

<p align="center">
  <img src="https://o.remove.bg/downloads/07be0ad6-7c62-43da-b7f4-76712c8e05ef/SIMPLEFLOW_LOGO-removebg-preview.png" alt="Logo" width="200" height="200" />
</p>

<h1 align="center"> Trabalho de Conclusão de Curso em Fundamentos de AWS - Promovido pela Escola da Nuvem </h1>

<a id="Sumário"></a>

<p align="center">
  <b> Criando um site Estatico na Nuvem </b></br>
  <sub> Este projeto visa construir um site estatico na nuvem utilizando Amazon S3, CloudFront, Route 53 e AWS Certificate.
  <sub>
</p>


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<p align="center">
  <a href="#Introdução"> 🧩 Introdução </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Resultados"> 🚀 Resultados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Dependências"> 🧪 Dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Ideias">💡 Possíveis Melhorias </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Creditos"> 🏆 Créditos </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
 
<br/>


### 🚧 PROJETO EM ANDAMENTO 🚧

<br/>

<a id="Introdução"></a>
## 🧩 Introdução 

  ***⠀⠀⠀⠀Bem-vindo a introdução do meu projeto de TCC para Escola da Nuvem - Criando um site Estatico na Nuvem
<br/>


<a id="Resultados"></a>
## 🚀 Resultados 
  > Espero consegui mostrar um pouco do meu conhecimento em nuvem.

<br/> 

## Front-end

<br />   

  ### ***⠀⠀⠀⠀⭐ Este é o nosso site, conheça o mapa do site, Home page, pagina de agradecimentos, de erro e de arquivos não encontrados.
<br />   


⭐ Home Page | ⭐ Agradecimentos | ⭐ Pagina Error | ⭐ Pagina Não Encontrado |
|---|---|---|---|
![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/dc1a49b0-9c62-40f6-a6fa-d8f6dd03caf5) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/d710f9b9-79a8-416b-b3b1-477e5485fb0a) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/ba8aa349-1339-423d-a310-6ddcd7aab516) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/10c42100-b50d-4815-abad-c4bb3675f1db)
![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/219c6fb2-39fd-4d0a-9b06-ff67335a2f38)


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)


### 💻 Desktop 
  
 ⭐ Exemplo de uso | ⭐ Registro | ⭐ Feed |
|---|---|---|
!![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/0940d86c-98b3-47ee-a8c0-0f0e3db58c2c)
 | ![Detalhes]() | ![Detalhes]()


<br/>

## Back-end
>
  
<br/>

### ***⠀⠀⠀⠀⭐ Veja toda a construção do código em detalhes***

  
### 🎯 <head> 
  
### ```Html``` 
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TCC Escola da Nuvem</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
    integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
```
### ```<header>``` 
```<body>
  <header class="header__container">
    <button class="menu-toggle" aria-label="Toggle Menu" onclick="toggleMenu()">&#9776;</button>

        <div class="header__logo">
          <h4>Escola da Nuvem TCC - Grupo 04</h4>
        </div>
        <nav class="header__nav">
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#especialistas">Nossos Especialistas</a></li>
                <li><a href="agradecimentos.html">Agradecimentos</a></li>
              </ul>
            </nav>
        </header>
```
### ```<section>``` 
```
        <section id="inicio" class="main__container">
        <main class="main__container">
            <div class="main__content">
                <h2 class="main__title">Conheça o poder da nuvem<br> Faça seu negócio decolar!</h2>
                <p class="main__p">Encontre profissionais qualificados com apenas alguns cliques. Confira nossos currículos
                e monte seu time de sucesso.</p>
            </div>
            <img src="img/gokunuvem.png" alt="Nuvem" class="main__img" width="1200">
        </main>
    </section>
```
### ```<section>``` 
```
     <section id="especialistas" class="section__division__container">
    <h3 class="division__title"> Nossos Especialistas</h3>
    <div class="section__image__container">
      <img class="cv-image" id="cv1-image" src="img/Alexandre_SF.png" alt="alexandre_sf">
      <img class="cv-image" id="cv4-image" src="img/clayton_sf.png" alt="Clayton" style="max-width: 100%;">
      <img class="cv-image" id="cv2-image" src="img/gabriel_sf.png" alt="Gabriel">
      <img class="cv-image" id="cv3-image" src="img/leivy_sf.png" alt="Leivy">
      <img class="cv-image" id="cv5-image" src="img/jorge_sf.png" alt="Jorge">
      <img class="cv-image" id="cv6-image" src="img/thalia_sf.png" alt="Thalia">
      <img class="cv-image" id="cv7-image" src="img/marcos_sf.png" alt="Marcos">

    </div>
    <div class="profile">
        <a href="https://www.linkedin.com/in/alexandre-da-silva-souza-69699924/" target="_blank">
        <p>Alexandre</p></a>
        <a href="https://www.linkedin.com/in/clayton-oliveira-108787143/" target="_blank">
        <p>Clayton</p></a>
        <a href="https://www.linkedin.com/in/gabriel-leonardo-68329919a/" target="_blank">
        <p>Gabriel</p></a>
        <a href="https://www.linkedin.com/in/leivy-bispo-4224b5142/" target="_blank">
        <p>Leivy</p></a>
        <a href="https://www.linkedin.com/in/jorge-costa-04687983/" target="_blank">
        <p>Jorge</p></a>
        <a href="https://www.linkedin.com/in/thalia-oliveira-de-sousa-16a7b0289/" target="_blank">
        <p>Thalia</p></a>
        <a href="#inicio" target="_blank">
        <p>Marcos</p></a>
    </div>

  </section>
```
### ```<section>``` 
```
    <section id="agradecimentos" class="section__container">
    <div class="section__select__container">
      <label for="section__select__text">Visualize o curriculo de cada Especialista:</label>
      <select id="curriculos">
        <option value="curriculos/CV-Alexandre.Souza.pdf">Alexandre Souza</option>
        <option value="curriculos/CV-Clayton.Oliveira.pdf">Clayton Oliveira</option>
        <option value="curriculos/CV-Gabriel.Leonardo.pdf">Gabriel Leonardo</option>
        <option value="curriculos/CV-Leivy.Bispo.pdf">Leivy Bispo</option>
        <option value="curriculos/CV-Jorge.Costa.pdf">Jorge Costa</option>
        <option value="curriculos/CV-Thalia.Sousa.pdf">Thalia Sousa</option>
        <option value="curriculos/CV-Marcos.Andre.pdf">Marcos André</option>
      </select>
      <button id="section__btn" class="pdf-view-button">Visualizar</button>
    </div>

  </section>
```
### ```<footer>``` 
```
    <footer>
    <section id="contato" class="footer">
    <div class="container-footer">
      <div class="row-footer">
        
        <div class="footer-col">
          <h4></h4>
          <ul>
            <li><a target=_blank href="https://escoladanuvem.org/">Escola da Nuvem</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/cursos">Cursos</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/doe">Doe</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/voluntario">Volunatário</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/parcerias">Parcerias</a></li>

            </li>
          </ul>
        </div>
       
        <div class="footer-col">
          <h4></h4>
          <ul>
            <li><a target=_blank href="https://escoladanuvem.org/depoimentos/">Cases</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/sobre-nos/">Sobre</a>
            <li><a target=_blank href="https://escoladanuvem.org/na-midia/">Midia</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/blog/">Blog</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/transparencia/">Transparência</a></li>
          </ul>
        </div>
        
      <div class="footer-col">
        <h4></h4>
        <ul>
          <li><a target=_blank href="https://www.udemy.com/terms/">Termos</a></li>
          <li><a target=_blank href="https://www.udemy.com/terms/privacy/">Política de privacidade</a></li>
          <li><a target=_blank href="https://www.udemy.com/pt/sitemap/">Mapa do Site</a></li>
          <li><a target=_blank href="https://about.udemy.com/pt-br/declaracao-de-acessibilidade-da-udemy/">Declaração de acessibilidade</a></li>
        </ul>
      </div>

      <div class="footer-col">
        <h4>Redes Sociais</h4>
        <div class="medias-socias">
          <a target=_blank href="https://web.facebook.com/EscolaDaNuvemOficial?_rdc=1&_rdr"> <i
              class="fa-brands fa-facebook-f"></i> </a>
          <a target=_blank href="https://www.instagram.com/escola_da_nuvem/"> <i class="fa-brands fa-instagram"></i>
          </a>
          <a target=_blank href="https://www.linkedin.com/company/escola-da-nuvem/"> <i
              class="fa-brands fa-linkedin-in"></i> </a>
          <a target=_blank href="https://escoladanuvem.org/"> <i class="fa-regular fa-at"></i> </a>
        </div>   
    </div>
    </section>
<script src="script.js"></script>
<!-- Adicione este script no seu HTML -->
<script>
    function toggleMenu() {
      var nav = document.querySelector('.header__nav');
      nav.classList.toggle('active');
    }
  
    document.addEventListener("DOMContentLoaded", function () {
      // ... (seu código JavaScript existente)
    });
  </script>
  
</body>
</html>
```
### ```CSS``` 
```
   @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;600&display=swap');

:root {
  --primary-color: #06204250; /* Vermelho */
  --secondary-color: #4CAF50; /* Verde */
  --text-color: #333; /* Preto */
  --text-color2: #fffdfd; /* Preto */
  --background-color: #f4f4f4; /* Cinza claro */
  --hover-color: #FFCE45; /* Amarelo (cor de destaque ao passar o mouse) */
}
