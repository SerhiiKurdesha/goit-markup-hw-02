# goit-markup-hw-02
:root {
 --primary-text-color: #757575;
 --title-text-color: #212121;
 --accent-color: #2196f3;
}

body {
    background-color: #fff;
    color: var(#757575);
    font-family: roboto, sans-serif;   
}

/* Скрытые заголовки h1, h2 */

.visually-hidden {
    position: absolute;
    clip: rect(0 0 0 0);
    width: 1px;
    height: 1px;
    margin: -1px;
}

/* Белый #FFFFFF */

.section-titles {
    color: #fff;
    font-family: Roboto;
    font-style: normal;
    font-weight: 900;
    font-size: 44px;
    line-height: 60px;

    text-align: center;
    letter-spacing: 0.06em;
    text-transform: uppercase;
}

/* Цвета секций #E5E5E5 */

.section-description,
.section-pictures,
.section-portfolio {
    color: #E5E5E5;
}

/* Акцент голубой #2196F3 */

/* Site nav */

.site-nav .link {
    color: #212121;
    font-weight: 500;
    font-size: 14px;
    line-height: 1.14;
}

.site-nav .link:hover,
.site-nav .link:focus {
    color: var(--accent-color);
}

.site-nav .link.current {
    color: greenyellow;
}

.section-top {
    width: 1600px;
    height: 600px;
    left: 0px;
    top: 80px;
    background: #2F303A;
}

/* Цвет секции и подвала */

.section,
.footer {
    background-color: #2F303A;
}

.team {
    background-color: #F5F4FA;
}

/* Лого */

.logo {
    font-family: raleway, cursive;
    font-size: 26px;
    line-height: 1.2;
}

.logo:hover,
.logo:focus {
    color: #2196F3;
}

/* home button */

.button {
    color: #fff;
    width: 200px;
    height: 50px;
    left: 700px;
    top: 430px;

    background: #2196F3;
    box-shadow: rgba(0, 0, 0, 0.15);
    border-radius: 4px; 

/* Заказать услугу */

    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 1.87;

/* identical to box height, or 187% */

    align-items: center;
    text-align: center;
    letter-spacing: 0.06em;
}

/* button-list */

.button-list {
    background: #F5F4FA;
    font-weight: 500;
    font-size: 16px;
    line-height: 1.62;
    border-radius: 4px;
}

.button-list:hover {
    background: #2196F3;
    color: #fff;
}

/* Address-list */

.site-nav .list {
    color: #757575;
    font-weight: 500;
    font-size: 14px;
    line-height: 1.14;
}

.site-nav .list:hover,
.site-nav .list:focus {
    color: #2196F3;
}

.title {
    color: rgba(255, 255, 255, 0.6);
    font-style: normal;
    font-size: 14px;
    line-height: 1.7;
}

.title:hover,
.title:focus {
    color: #2196F3;
}

 width: 200px;
    height: 50px;
    left: 700px;
    top: 430px;
    background: #2196F3;
    border-radius: 4px;
    cursor: pointer; 
    color: #ffffff;

    font-weight: bold;
    font-size: 16px;
    line-height: 1.87;

    align-items: center;
    text-align: center;
