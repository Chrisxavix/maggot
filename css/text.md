P+AGINA WEB 

/* Letra de google fonts */
@import url('https://fonts.googleapis.com/css2?family=Castoro:ital@0;1&family=Raleway:wght@300;400;700&display=swap');

:root {
    /* Variables */
    --background: linear-gradient(135deg, #667eea7e 0%, #764ba298 100%);
    --color-primary: #667eea;
    --color-secundary: #764ba2;
    --boton-padding: 20px 40px
}

body {
    font-family: 'Raleway', sans-serif, 'Castoro', serif;
}

.container {
    width: 90%;
    margin: 0 auto;
    overflow: hidden;
    padding: 80px 0;
    max-width: 1200px;
}

.subtitle {
    color: var(--color-primary);
    font-size: 2.5rem;
    margin-bottom: 35px;
}

.hero {
    height: 100vh;
    background-image: var(--background), url('../assets/computer.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
    position: relative;
}

.hero .container {
    padding: 0;
}

.nav {
    display: flex;
    justify-content: flex-end;
    height: 70px;
    align-items: center;
    font-weight: 700;
}

.nav--footer {
    font-weight: 300;
    justify-content: flex-start;
}

.nav__items {
    color: #fff;
    text-decoration: none;
    margin-right: 20px;
    padding: 10px 15px;
    font-weight: inherit;
}

.nav__items--cta {
    border: 1px solid;
}

.nav__items--footer {
    padding: 10px;
}


.hero__container {
    display: flex;
    height: calc(100vh - 70px);
    align-items: center;
    color: #fff;
}

.hero__texts {
    width: 80%;
    margin-bottom: 50px;
}

.hero__title {
    font-size: 3.2rem;
}

.hero__subtitle {
    font-size: 2rem;
    font-weight: 300;
    margin: 15px 0;
}

.hero__cta {
    display: inline-block;
    background: #fff;
    padding: var(--boton-padding);
    color: var(--color-primary);
    text-decoration: none;
    border-radius: 40px;
}

.hero__wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100px;
}

/* About */

.presentation {
    text-align: center;
    padding-top: 0;
}

.presentation__picture {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
    object-fit: cover;
} 

.presentation__copy {
    width: 80%;
    margin: 0 auto;
}

.presentation__cta {
    display: inline-block;
    margin-top: 30px;
    background-color: var(--color-primary);
    color: #fff;
    text-decoration: none;
    padding: var(--boton-padding);
    border-radius: 40px;
}

.about {
    min-height: 400px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    row-gap: 80px;
    justify-items: center;
    align-items: center;
}

.about__img {
    text-align: center;
}

.about__img--left {
    text-align: left;
}

.about__picture {
    max-width: 80%;
    /* width: 150px;
    height: 150px; */
}

.about__paragraph {
    margin-bottom: 20px;
    line-height: 1.5;
    font-weight: 300;
}

/* Projects */

.projects {
    background: #f2f2f2;
}

.projects__grid {
    display: grid;
    height: 550px;
    grid-template-areas: 
    "img1 img1 img2 img3"
    "img1 img1 img4 img5";
    gap: 1opx;

}

.project__item {
    position: relative;
    width: 100px;
    height: 100px;
    overflow: hidden;
}

.project__img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    cursor: pointer;
}

.project__item:nth-of-type(1) {
    grid-area: img1;
}

.testimony__grid {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    /* gap: 10px; */
}
/* 
.testimony__item {
    width: 95%;
    margin: 0 auto;
    background: var(--color-secundary);
    box-shadow: 0 8px 10px rgba(66, 66, 66, .5);
    border-radius: 7px;
    padding: 30px 25px;
    color: #fff;
    margin-bottom: 50px;
}

.testimony__person {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.testimony__img {
    width: 100px;
    min-width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid #fff;
    margin-right: 30px;
} */

.test-grid {
    background: #667eea;
    display: grid;
    grid-template-columns: 1fr 1fr;
}

.img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}