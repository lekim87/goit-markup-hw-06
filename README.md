 <p class="modal-title">Заголовок модального окна</p>
        <form class="modal-form">
          <div class="form-field">
            <label for="user-name" class="modal-label">Введите имя*</label>
            <input
              type="text"
              name="user-name"
              class="modal-input"
              placeholder="John Dou"
              required
              id="user-name"
            />
          </div>
          <div class="form-field">
            <label for="user-email" class="modal-label">Введите почту</label>
            <input
              type="email"
              name="user-email"
              class="modal-input"
              placeholder="test@mail"
              required
              id="user-email"
            />
          </div>

          <div class="form-field">
            <label for="user-tel" class="modal-label">Введите телефон*</label>
            <input
              type="tel"
              name="user-tel"
              class="modal-input"
              placeholder="+380"
              required
              id="user-tel"
            />
          </div>
          <div class="form-field">
            <label for="user-text" class="modal-label">Коментарий</label>
            <textarea
              name="user-text"
              id="user-text"
              class="modal-text"
              placeholder="коммент"
            ></textarea>
          </div>
          <fieldset>
            <legend>Size</legend>
            <label for="big-size">40sm</label>
            <input type="radio" name="size" id="big-size" value="big-size" />
            <label for="small-size">30sm</label>
            <input
              type="radio"
              name="size"
              id="small-size"
              value="small-size"
            />
          </fieldset>
          <fieldset>
            <legend>add</legend>
            <label for="cheese">cheese</label>
            <input
              type="checkbox"
              checked
              name="add"
              id="cheese"
              value="cheese"
            />
            <label for="peperoni">peperoni</label>
            <input type="checkbox" name="add" id="peperoni" value="peperoni" />
          </fieldset>
          <div class="form-field">
            <label for="city">City</label>
            <select name="pizza-city" id="city" class="modal-input">
              <option value="London"></option>
              <option value="Paris">Paris</option>
              <option value="Novyy Rozdil">Novyy Rozdil</option>
            </select>
          </div>
          <button type="submit">Submit</button>
          <button type="reset">Reset</button>
        </form>

<symbol id="icon-person-black" viewBox="0 0 32 32"><path d="M16 16c2.946 0 5.333-2.388 5.333-5.333s-2.388-5.333-5.333-5.333v0c-2.946 0-5.333 2.388-5.333 5.333s2.388 5.333 5.333 5.333v0zM16 18.667c-3.561 0-10.667 1.787-10.667 5.333v1.333c0 0.732 0.599 1.333 1.333 1.333h18.667c0.732 0 1.333-0.601 1.333-1.333v-1.333c0-3.547-7.108-5.333-10.667-5.333z"></path></symbol>
<symbol id="icon-email-black" viewBox="0 0 32 32"><path d="M26.667 5.333h-21.333c-1.467 0-2.652 1.2-2.652 2.667l-0.014 16c0 1.467 1.2 2.667 2.667 2.667h21.333c1.467 0 2.667-1.2 2.667-2.667v-16c0-1.467-1.2-2.667-2.667-2.667zM26.133 11.001l-9.426 5.892c-0.201 0.126-0.446 0.2-0.708 0.2s-0.506-0.075-0.713-0.204l0.006 0.003-9.426-5.892c-0.336-0.201-0.557-0.562-0.557-0.975 0-0.625 0.507-1.132 1.132-1.132 0.233 0 0.449 0.070 0.629 0.19l-0.004-0.003 8.933 5.586 8.933-5.588c0.176-0.118 0.392-0.188 0.624-0.188 0.625 0 1.132 0.507 1.132 1.132 0 0.413-0.221 0.775-0.552 0.972l-0.005 0.003z"></path></symbol>
<symbol id="icon-phone-black" viewBox="0 0 32 32"><path d="M24.882 19.774l-3.268-0.373c-0.090-0.011-0.194-0.018-0.3-0.018-0.707 0-1.347 0.287-1.81 0.75l-2.368 2.368c-3.669-1.894-6.585-4.81-8.427-8.372l-0.051-0.108 2.382-2.377c0.463-0.463 0.75-1.103 0.75-1.81 0-0.106-0.006-0.21-0.019-0.312l0.001 0.012-0.373-3.243c-0.155-1.287-1.24-2.276-2.557-2.276-0.001 0-0.002 0-0.003 0h-2.226c-1.454 0-2.663 1.209-2.574 2.661 0.683 10.987 9.47 19.762 20.444 20.444 1.452 0.089 2.663-1.12 2.663-2.574v-2.226c0-0.004 0-0.008 0-0.012 0-1.308-0.985-2.386-2.253-2.532l-0.012-0.001z"></path></symbol>
<symbol id="icon-icon-send" viewBox="0 0 32 32"><path fill="#fff" style="fill: var(--color1, #fff)" d="M32 0l-32 18 10.227 3.787 15.773-14.787-11.997 16.187 0.009 0.003-0.012-0.003v8.813l5.735-6.691 7.267 2.691 4.999-28z"></path></symbol>

Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore

@lekim87
Eldiwr
/
goit-markup-hw-06
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
goit-markup-hw-06/css/styles.css
@Eldiwr
Eldiwr Update styles.css
Latest commit 19818f1 11 hours ago
History
1 contributor
1089 lines (787 sloc) 16.6 KB

:root {
--primary-background-color: #ffffff;
--secondary-background-color: #f5f4fa;
--footer-background-color: #2f303a;
--focus-color: #2196f3;
--primary-font-color: #757575;
--secondary-font-color: #212121;
--icon-color: #AFB1B8;
}

body {

    background-color: var(--primary-background-color);
    color: var(--primary-font-color);

    font-family: "Roboto", sans-serif;
    font-size: 14px;
    line-height: 1.71;
    letter-spacing: 0.03em;

}
/_ Обнуление/Скрытие элементов/общие стили _/

.list {
margin: 0px;
padding: 0px;
list-style: none;
}

.no-title {
display: none;
}

.link {
color: inherit;
text-decoration: none;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
margin: 0px;
}

.container {
width: 1200px;
padding: 0px 15px;
margin: 0 auto;
display: flex;
align-items: center;
}

img {
display: block;
}

/_ .is-hidden {
opacity: 0;
pointer-events: none;
} _/

.title {
margin-bottom: 50px;
color: var(--secondary-font-color);

    font-weight: 700;
    font-size: 36px;
    line-height: 1.7;
    text-align: center;
    letter-spacing: 0.03em;

}

.section {
padding-top: 94px;
padding-bottom: 94px;
}

.current {
color: var(--focus-color);
}

.nav-item {
position: relative;
}

.current::after {

    position: absolute;

    display: block;

    content:'';

    width: 100%;
    height: 4px;
    left: 0;
    bottom: -1px;

    background: var(--focus-color);
    border-radius: 2px;


}

.item:not(:last-child){
margin-right: 30px;
}

.item.thumb {
position: absolute;
}

/_ ----------header-page---------- _/
.header-page {

    width: 100%;

    top: 0;
    left: 0;

    background-color: var(--primary-background-color);

}
.header-page {
border-bottom: 1px solid #ececec;
}

/_ -----For logo----- _/

.logo-header {
margin-right: 93px;
color: var(--secondary-font-color);

    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    font-size: 26px;
    line-height: 1.2;
    letter-spacing: 0.03em;

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.logo-header {
padding-top: 24px;
padding-bottom: 25px;
}

.logo-header span {
color: var(--focus-color);
}

.logo-header:hover{
color: var(--focus-color);
}

/_ -----Navigation----- _/

    .nav-list {
    display: flex;

    color: var(--secondary-font-color);

    font-weight: 500;
    font-size: 14px;
    line-height: 1.4;
    letter-spacing: 0.02em;

}

.nav-list .link:hover,
.nav-list .link:focus {
color: var(--focus-color);
}

.nav-item:not(:last-child) {
margin-right: 50px;
}

.nav-item .link {
display: block;

    padding-top: 32px;
    padding-bottom: 28px;

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

/_ -----Contacts----- _/

.contacts-header {
display: flex;
margin-left:auto;

    font-weight: 500;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.02em;

}

.contact-item .link {
display: flex;
align-items: center;
padding-top: 32px;
padding-bottom: 32px;

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.contact-item {
display: flex;
}

.contacts-header .link:hover,
.contacts-header .link:focus{
color: var(--focus-color);
}

.contact-item:not(:last-child) {
margin-right: 50px;
}

.icon-mail {

    width: 16px;
    height: 12px;
    margin-right: 10px;
    fill: currentColor;

}

.icon-phone {
width: 10px;
height: 16px;
margin-right: 10px;
fill: currentColor;
}

/_ --------------Footer-------------- _/

.site-footer {
background-color: var(--footer-background-color);
}

.footer-container {
display: flex;
align-items: baseline;

    width: 1200px;

    margin-left: auto;
    margin-right: auto;
    padding: 60px 15px;

}

/_ .site-footer .container {
padding: 60px 15px;
} _/

.logo-footer {
display: block;
margin-bottom: 20px;

    color: var(--primary-background-color);

    font-family: 'Raleway', sans-serif;

    font-weight: 700;
    font-size: 26px;
    line-height: 1.2;
    letter-spacing: 0.03em;

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.logo-footer.link span {
color: var(--focus-color);
}

.logo-footer:hover,
.logo-footer:focus {
color: var(--focus-color);
}

.address{
font-style: normal;
}

.address-link {
text-decoration: none;
color: var(--primary-background-color);
}

.address-item{
font-size: 14px;
line-height: 1.7;
letter-spacing: 0.03em;
color: rgba(255, 255, 255, 0.6);
}

.address-item:not(:last-child) {
margin-bottom: 9px;
}

.address-item .link:hover,
.address-item .link:focus {
color: var(--focus-color);
}

.Logo-footer-container {
width: 231px;
margin-right: 70px;
}

.social-div {
margin-right: 93px;
}

b {
display: block;
margin-bottom: 20px;

    color: var(--primary-background-color);

    font-weight: 700;
    font-size: 14px;
    line-height: 1.4;
    letter-spacing: 0.03em;
    text-transform: uppercase;

}

.svg-container.footer {
color: var(--primary-background-color);
background-color: rgba(255, 255, 255, 0.1);
border-radius: 50px;
}

.footer-form-group {
display: flex;
align-items: center;
}

.footer-input {

    padding-left: 16px;

    width: 358px;
    height: 50px;

    border: 1px solid rgba(255, 255, 255, 0.3);
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
    border-radius: 4px;

    outline: none;

    background-color: var(--footer-background-color);
    color: var(--primary-background-color);

    transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.footer-input:hover,
.footer-input:focus {

    border-color:  var(--focus-color);

}

.footer-input::placeholder {
font-size: 16px;
line-height: 1.25;

    color: rgba(255, 255, 255, 0.6);

}

.footer-submit-button {

    display: flex;
    align-items: center;

    margin-left: 12px;
    padding: 10px 28px 10px 29px;

    height: 50px;

    border-width: 0px;

    font-weight: 700;
    font-size: 16px;
    line-height: 1.87;
    text-align: center;
    letter-spacing: 0.06em;

    outline: none;

    background-color: var(--focus-color);
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
    border-radius: 4px;
    color: var(--primary-background-color);

}

.footer-icon-send {
margin-left: 10px;
}

/_ -----------Form footer----------- _/

/_ ----------Maine content---------- _/

/_ -----Hero content----- _/

.hero {
margin-left: auto;
margin-right: auto;
padding-top: 200px;
padding-bottom: 200px;
max-width: 1600px;
height: 600px;
background-repeat: no-repeat;
background-size: cover;

    background-image: linear-gradient( to right, rgba(47, 48, 58, 0.4),  rgba(47, 48, 58, 0.4)), url(../img/preview.jpg);
    background-color: var(--footer-background-color);

}

.hero-title {
color: var(--primary-background-color);

    font-weight: 900;
    font-size: 44px;
    line-height: 1.36;
    text-align: center;
    letter-spacing: 0.06em;
    text-transform: uppercase;

}

.hero-button {
margin-top: 30px;
margin-left: auto;
margin-right: auto;
padding: 10px 32px;
min-width: 200px;

    color: var(--primary-background-color);
    background-color: var(--focus-color);


    font-weight: 700;
    font-size: 16px;
    line-height: 1.9;
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: 0.06em;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
    border-radius: 4px;
    border-width: 0px;

}

/_ ----------------Modal content----------------_/

.backdrop {
position: fixed;
z-index: 1;
top: 0;
left: 0;
width: 100%;
height: 100%;

    background: rgba(0, 0, 0, 0.2);

    opacity: 1;
    transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.backdrop.is-hidden {
opacity: 0;
pointer-events: none;
}

.backdrop.is-hidden .modal {
transform: translate(-50%, -50%) scale(0.9);
}

.modal {
position: absolute;

    top:50%;
    left:50%;
    transform: translate(-50%, -50%);

    min-height: 528px;
    min-width: 581px;

    background-color: var(--primary-background-color);

    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2);
    border-radius: 4px;

    transform: translate(-50%, -50%) scale(1);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.close-button {
display: flex;
justify-content: center;
align-items: center;
margin-left: auto;
margin-top: 8px;
margin-right: 8px;
width: 30px;
height: 30px;
border-radius: 50px;

    cursor: pointer;

    background-color: var(--primary-background-color);
    border: 1px solid rgba(0, 0, 0, 0.1);

    transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.close-button:hover,
.close-button:focus {
fill: var(--focus-color);
}

/_ Form-content _/

.form-title {
font-weight: 700;
font-size: 20px;
line-height: 1.15;
text-align: center;
letter-spacing: 0.03em;

    color: var(--secondary-font-color);

}

.form-container {
display: flex;
flex-direction: column;

    margin-top: 12px;
    padding-left: 41px;
    padding-right: 39px;
    padding-bottom: 40px;

}

.modal-label:not(:first-child) {
margin-top: 10px;
}

.modal-label {
font-size: 12px;
line-height: 1.15;
letter-spacing: 0.01em;

    color: #757575;

}

.modal-input {
width: 100%;
height: 40px;

    padding-left: 42px;

    cursor: pointer;
    outline: none;

    border: 1px solid rgba(33, 33, 33, 0.2);
    box-sizing: border-box;
    border-radius: 4px;

    transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.modal-textarea {
display: block;

    height: 120px;
    padding: 12px 16px;

    outline: none;

    border: 1px solid rgba(33, 33, 33, 0.2);
    box-sizing: border-box;
    border-radius: 4px;

    transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1)

}

.modal-textarea {
width: 100%;
resize: none;

    margin-top: 4px;

}

.modal-textarea::placeholder {
font-size: 12px;
line-height: 1.16;
letter-spacing: 0.01em;

color: rgba(117, 117, 117, 0.5);
}

.modal-textarea:hover,
.modal-textarea:focus {

    border-color: var(--focus-color);

}

.group-container-svg {

    position: relative;

    margin-top: 4px;

}

.form-svg {
position: absolute;

    cursor: pointer;

    top: 50%;
    left: 12px;
    transform: translateY(-50%);

    transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.modal-input:hover,
.modal-input:focus {
border-color: var(--focus-color);
}

.modal-input:hover + .form-svg,
.modal-input:focus + .form-svg {
fill: var(--focus-color);
}

.policy {

    margin-top: 30px;
    margin-bottom: 30px;

}

.label-policy {

    display: flex;
    align-items: center;

    font-size: 14px;
    line-height: 1.71;
    letter-spacing: 0.03em;

    color: var(--primary-font-color);

}

.label-policy::before {
content: " ";

    height: 15px;
    width: 16px;

    border: 2px solid var(--secondary-font-color);
    border-radius: 2px;
    margin-right: 7px;

}

.policy-checkbox:checked + .label-policy::before {
background-image: url(../img/icon-check.svg);
border: none;
}

.policy-checkbox {
position: absolute;
appearance: none;
}

.policy-link {

    margin-left: 2px;

    font-size: 14px;
    line-height: 1.71;

    color: var(--focus-color);

}

.form-button {
margin-right: auto;
margin-left: auto;

    padding: 10px 55px 10px 56px;

    border-width: 0px;

    font-weight: 700;
    font-size: 16px;
    line-height: 1.87;
    text-align: center;
    letter-spacing: 0.06em;

    color: var(--primary-background-color);
    background: var(--focus-color);
    border-color: var(--focus-color);

    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
    border-radius: 4px;

}

/_ --------------Soft-skills-------------- _/

.soft-skills-list {
display: flex;
}

.icon-div-soft {
width: 100%;
height: 120px;
border-radius: 4px;
background-color: var(--secondary-background-color);
display: flex;
align-items: center;
justify-content: center;
margin-bottom: 30px;
}

.list-title {
margin-bottom: 10px;
color: var(--secondary-font-color);

    font-weight: 700;
    font-size: 14px;
    line-height: 1.4px;
    letter-spacing: 0.03em;
    text-transform: uppercase;

}

.soft-item {
width: 270px;
height: 251px;
}

/_ -------------------Business section------------------- _/

.business {
padding-top: 0px;
}

.business-thumb {
position: relative;
z-index: -1;
}

.description-thumb {
position: absolute;
width: 100%;
height: 70px;
bottom: 0;
right: 0;

    display: flex;
    justify-content: center;

    padding: 27px;

    background: rgba(47, 48, 58, 0.8);

}

.business-description {

    color: var(--primary-background-color);

    font-weight: 700;
    font-size: 14px;
    line-height: 1.4;
    text-align: center;
    letter-spacing: 0.03em;
    text-transform: uppercase;

}
/_ ----------------------Team---------------------- _/

.team {
background-color: var(--secondary-background-color);
}

.name-title {
margin-bottom: 10px;

    color: var(--secondary-font-color);

    font-weight: 500;
    font-size: 16px;
    line-height: 1.2;
    text-align: center;
    letter-spacing: 0.03em;

}

.position {
margin-bottom: 16px;
color: var(--primary-font-color);

    font-size: 16px;
    line-height: 1.2;
    text-align: center;
    letter-spacing: 0.03em;

}

.team-group-div {
margin-top: 30px;
padding-right: 30px;
padding-left: 30px;
padding-bottom: 30px;
}

.team-item {
background-color: var(--primary-background-color);
box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2);
border-radius: 0px 0px 4px 4px;
}

.social-list.list {
display: flex;
align-content: center;
}

.social-item:not(:last-child) {
margin-right: 10px;
}

.svg-container {
display: flex;
align-content: center;

    width: 44px;
    height: 44px;
    border-radius: 50px;
    justify-content: center;
    align-items: center;
    color: var(--icon-color);
    cursor: pointer;

    transition: background 250ms cubic-bezier(0.4, 0, 0.2, 1), color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.social-icon{
fill: currentColor;
}

.svg-container:hover,
.svg-container:focus{
border-radius: 50px;
color: var(--primary-background-color);
background-color: var(--focus-color);
}

/_ -----------Company section----------- _/

/_ -----Company----- _/

.company-list{
display: flex;
align-content: center;
}

.company-item:not(:last-child){
margin-right: 30px;
}

.company-link {
display: flex;
align-items: center;
justify-content: center;

    width: 170px;
    height: 92px;

    border: 1px solid var(--icon-color);
    border-radius: 4px;
    color: var(--icon-color);

    background-color: var(--primary-background-color);

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1), border 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.company-icon{
display: block;
fill: currentColor;
}

.company-link:hover,
.company-link:focus {
color: var(--focus-color);
border: 1px solid var(--focus-color)
}

/_ ---------------------Portfolio page--------------------- _/

/_ ---------Filter buttons--------- _/
.portfolio-container {
display: block;
}

.filter-list {
display: flex;
justify-content: center;
margin-bottom: 50px;
}

.filter-button {
padding: 6px 22px;
height: 38px;
color: var(--footer-background-color);
background-color: var(--secondary-background-color);

    font-family: inherit;
    font-weight: 500;
    font-size: 16px;
    line-height: 1.62;
    text-align: center;
    letter-spacing: 0.03em;
    border: none;
    border-radius: 4px;

    transition: background 250ms cubic-bezier(0.4, 0, 0.2, 1),
    color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.button-li:not(:last-child) {
margin-right: 8px;
}

.filter-button:hover,
.filter-button:focus {
color: var(--primary-background-color);
background-color: var(--focus-color);
box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 1px 2px rgba(0, 0, 0, 0.08), 0px 2px 2px rgba(0, 0, 0, 0.12);
border-radius: 4px;
}

/_ -------------portfolio-list------------- _/

.product-naming {
margin-bottom: 4px;

    color: var(--secondary-font-color);

    font-weight: 700;
    font-size: 18px;
    line-height: 2;
    letter-spacing: 0.06em;

}

.product-type {
color: var(--primary-font-color);

    font-size: 16px;
    line-height: 1.87;
    letter-spacing: 0.03em;

}

.group-div {
padding: 20px 24px;

    border-right: 1px solid #EEEEEE;
    border-bottom: 1px solid #EEEEEE;
    border-left: 1px solid #EEEEEE;

}

.portfolio-list {
display: flex;
flex-wrap: wrap;
}

.portfolio-items {
margin-bottom: 30px;
margin-left: 30px;
}

.portfolio-items:nth-child(3n + 1) {
margin-left: 0px;
}

.portfolio-items:nth-last-child(-n + 3) {
margin-bottom: 0px;
}

.portfolio-items .link {
display: block;

    transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.portfolio-items .link:hover,
.portfolio-items .link:focus {
box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06), 1px 4px 6px rgba(0, 0, 0, 0.16);
}

.portfolio-items .link:hover .portfolio-text,
.portfolio-items .link:focus .portfolio-text {
transform: translateY(0);
}
.portfolio-items .link:hover .portfolio-thumb::before,
.portfolio-items .link:focus .portfolio-thumb::before{
transform: translateY(0);
}

.portfolio-thumb {
display: flex;
position: relative;

    overflow: hidden;

}

.portfolio-text {
position: absolute;
width: 100%;
height: 100%;
bottom: 0;

    padding: 63px 24px;

    font-size: 18px;
    line-height: 1.5;

    color: var(--primary-background-color);

    transform: translateY(100%);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.portfolio-thumb::before {
content: '';
display: inline-block;
position: absolute;
width: 100%;
height: 100%;

    background-color: rgba(33, 150, 243, 0.9);

    transform: translateY(100%);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
