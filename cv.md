<h1>My resume</h1>
<p class="name">Anzhela Abitova</p>
        <p>My Email anzhela.abitova@mail.ru, telephone number <tel>+79608138825</tel>, my profiles on 
        <a href="https://vk.com/id230631255">VK</a>, <a class="social_media_links" 
        href="https://www.facebook.com/abitovaanzela" 
        target="_blank">Facebook</a>.</p>
        <p>My main goal is to become a successful web-developer. Now I engage in web-design. But I 
        find coding much more fascinating and reliable. I have to admit my lack of actual experience. 
        All projects I did contribute were training. But I do learn fast, especially when I'm 
        inspired. And I'm inspired to learn coding.</p>
        <p>I know HTML, CSS and currently trying to learn JavaScript and PHP.</p>
        <p>Education that I've had so far are course Web-design at Samara University, courses at HTML 
        Academy and various online-seminars (mostly Skillbox), a lot of books and articles. </p>
        <p>I have learned English at school, then had three courses at university. For the most part 
        all practice I had with English is reading a lot and watching courses.</p>
        <p>As I said previously I've had contributed to some training projects, links provided above, and had 
        badges at HTML Academy.</p>
        <p><a href="https://htmlacademy.ru/assets/courses/309/project-state-final.zip" target="_blank">Page 
        from HTML Academy</a></p>
        <p>Examples of my code:</p>
        </div>

        <div class="code_example">
            <code>
              <pre>
const $getElById = (id) => document.getElementById(id);
const random = (num) => Math.ceil(Math.random() * num);

function tapCounting(btn, tapLimit){
    let count = 0;
    return function(){
        count++;
        btn.querySelector('span').innerText = tapLimit - count;
        if (count >= tapLimit) {
            btn.disabled = true;
        }
        return count;
    }
}




function minmaxDamage(item) {
    let damageArr = [item.maxDamage, item.minDamage];
    return damageArr[random(1)];
}
let selectorsM = {
    selectors(name) {
        this.elHP = document.getElementById(`health-${name}`);
        this.elProgressbar = document.getElementById(`progressbar-${name}`);
        this.namePlayer = document.getElementById(`name-${name}`);
        this.imgPlayer = document.getElementById(`img-${name}`);
    }
}

export {$getElById, random, tapCounting, minmaxDamage, selectorsM };

        </pre>
          </code>
          <code>
            <pre>
            * {
	margin:0;
	padding:0;
	box-sizing:border-box;
}

body {
	font-family:"Roboto", "Arial", sans-serif;
	max-width: 99vw;
	height: 100%;
	overflow-x: hidden;
	position:relative;
	line-height:1.5;
}

h1 {
	color:#131313;
	font-size:2.5rem;
	margin: 1rem auto;
	text-align:center;
}

h2 {
	color:#131313;
	margin: 1rem auto;
	text-align:center;
}

header {
	position:sticky;
}

header nav,
footer nav {
	background-color:#008B8B;
	color:#fff;
}

nav ul {
	margin:0 auto;
	max-width:75%;
	display:flex;
	flex-wrap:nowrap;
	justify-content:space-between;
}

nav ul li {
	list-style:none;
	padding: 0.8rem 0;
}

nav li a {
	color:#fff;
	text-transform:uppercase;
	font-size:0.9rem;
}

.container {
	max-width:80%;
	margin:0 auto;
}

.basic_typo {
	margin: 2rem 0;
}

.container div {
	margin:2rem 0;
}

.sky {
	width:100vw;
	height:100vh;
	position:fixed;
	z-index:-1;
	background-image: url(../img/lukasz-lada-LtWFFVi1RXQ-unsplash.jpg);
	background-position: top center;
	background-size: cover;
	background-repeat: no-repeat;
	background: url(../img/lukasz-lada-LtWFFVi1RXQ-unsplash.jpg) no-repeat center center fixed;
	background-size: cover;
}

a {
	text-decoration: none;
}

.test_button {
	outline:none;
	appearance:none;
	border:none;
	background-color:;
}

ul, ol {
	margin-top:2rem;
	list-style-position: inside;
}

ul ol, ol ul {
	margin-left:1.5rem;
	margin-top:0;
}

table {
	border: 2px dashed #131313;
	border-radius: 5px;
	margin: 2rem auto;
}

td {
	border: none;
	text-align:center;
	padding:0.5rem;
}

tr:nth-child(even) {
	background-color:#AFEEEE;
}

tr:nth-child(odd) {
	background-color:#E0FFFF;
}

.table_head {
	background-color:#191970;
	color:#fff;
}

.red {
	color: #FF0000;
	font-weight: lighter;
	font-size:2rem;
	margin-left:60px;
	background-color:#FFE4E1;
	margin-bottom:2rem;
}

body.layout {
	font-family: 'Arial', 'Roboto', sans-serif;
}

.layout h1 {
	color:#fff;
	font-size:4.5rem;
	font-weight:normal;
	margin:0;
	text-align:left;
}

.h1_container {
	width:45%;
	margin-bottom:5rem;
}

.layout .header_container,
.layout .about_product_container,
.layout .dignity_product_container,
.layout .screenshots_container,
.layout .reviews_container,
.layout .tarifs_container,
.layout .contacts_container,
.layout .footer_container {
	width:85%;
	margin:0 auto;
	display: flex;
	justify-content:space-between;
}

.layout section {
	padding: 2rem 0;
}

.layout .header_container,
.layout .about_product_container,
.layout .screenshots_container,
.layout .reviews_container {
	flex-wrap:wrap;
}

.layout .tarifs_container {
	align-items: flex-end;
}

.layout header {
	background-color: #445161;
	color:#fff;
}

.layout header li {
	list-style: none;
}

.layout header li::before {
	content: url(../img/check-icon.png);
	margin-right: 5px;
}

.layout .header_img {
	margin-top:4rem;
	background-color: #fff;
	width: min(90%, 470px);
	height:215px;
}

.about_product_container_text {
	display: flex;
	flex-direction: column;
	justify-content:space-around;
	align-content: flex-start;
	width: 60%;
}

.about_product_container_text h2 {
	margin: 0;
	text-align: left;
}

.layout .about_product_container {
}

.layout .about_product_container p {
	font-size:1rem;
	line-height:1.5;
}

.layout .about_product_container p:nth-child(1) {
	margin-bottom:1rem;
}

.layout .about_product_img {
	background-color: #445161;
	width: min(90%, 430px);
	height:245px;
}

.dignity_product,
.reviews {
	background-color:#f5f5f5;
}

.layout .dignity_product_container ul {
	width:45%;
	margin: 0;
}

.layout .dignity_product_container li {
	list-style: none;
	position: relative;
	margin-left: 41px;
	margin-bottom: 1rem;
}

.layout .dignity_product_container li::before {
	content: url(../img/plus-icon.png);
	margin-right: 5px;
	display: block;
	position: absolute;
	top: 0;
	left: -41px;
	width: 32px;
	height: 32px;
}

.layout .screenshots_container_img {
	display:flex;
	justify-content:space-around;
	flex-wrap:wrap;
	width:50%;
	margin-bottom:1.5rem;
} 

.layout .screenshots_container_img_text {
	width: 60%;
	font-size: 1rem;
}

.layout .screenshots_container_img_text h3 {
	font-size: 1.5rem;
	font-weight: normal;
	color: #445161;
}

.layout .screenshots_img {
	background-color: #445161;
	width: min(90%, 200px);
	height:151px;
}

.reviews_container_img {
	display:flex;
	justify-content:space-between;
	flex-wrap:wrap;
	width:45%;
	margin-bottom:1rem;
	position: relative;
}

.layout .reviews_container_img_text::before {
	content: "";
	top: 25px;
	left: -12px;
	width: 0; 
	height: 0;
	position: absolute;
	border-top: 8px solid transparent;
	border-right: 12px solid #ebebeb;
	border-bottom: 8px solid transparent;
}

.layout .reviews_container_img_text {
	position: relative;
	width: 80%;
	background-color: #ebebeb;
	border-radius: 7px;
	font-style: italic;
	padding: 10px;
}

.layout .reviews_container_img_text i {
	color: #989898;
	font-size: 0.875rem;
}

.layout .reviews_img {
	background-color: #445161;
	width: min(90%, 75px);
	height: 75px;
	border-radius:50%;
}

.layout .tarifs_container_elem {
	background-color: #445161;
	color:#fff;
	width: min(30%, 300px);
	padding: 15px 22px;
	border-radius:10px;
}

.layout .tarifs_container_elem ol {
	margin: 1rem 0;
}

.layout .tarifs_name {
	text-align:center;
	font-size:1.5rem;
}

.layout .tarifs_price {
	text-align:center;
	font-size:2.5rem;
	background-color: #fff;
	color:#445161;
	width: calc(100% + 42px);
	align-self: center;
	margin-left: -21px;
}

.layout .tarifs_container_elem button {
	appearance:none;
	outline:none;
	border:none;
	display:block;
	background-color: #fff;
	color:#445161;
	text-transform:uppercase;
	width:100%;
	height:41px;
	border-radius:5px;
	transition: all 0.3s ease-in-out 0s;
}

.layout .tarifs_container_elem button:hover {
	background-color: #ebebeb;
	cursor: pointer;
}

.layout .contacts_container {
	justify-content: center;
}

.layout form {
	display:flex;
	justify-content:center;
	align-content: space-around;
	flex-wrap: wrap;
	width:45%;
}

.layout form #name,
.layout form #email {
	width: clamp(10vw, 501px, 500px);
	height:41px;
	border-radius:7px;
	padding:15px;
	border:none;
	margin-bottom:1rem;
}

.layout .contacts {
	background-color: #445161;
	color:#fff;
	padding:2.6rem 0;
}

.layout .contacts h2,
.layout .contacts a {
	color: #fff;
}

.layout form #message {
	width: clamp(10vw, 501px, 500px);
	height:171px;
	border-radius:7px;
	padding:15px;
	border:none;
	margin-bottom:1rem;
}

.layout .contacts button {
	outline:none;
	appearance:none;
	border:none;
	background-color: #fff;
	color:#445161;
	width:141px;
	height:41px;
	border-radius:7px;
	text-transform:uppercase;
	display:block;
	transition: all 0.3s ease-in-out 0s;
}

.layout .contacts button:hover {
	background-color: #ebebeb;
	cursor: pointer;
}

.contacts_soc_container {
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	height: 30vh;
	margin-left: 2rem;
}

.contacts_soc_tel_container {
	display:flex;
	flex-direction: column;
	justify-content:flex-start;
	align-content:space-around;
	flex-wrap:wrap;
}

.contacts_soc_tel_container a {
	display: block;
	position: relative;
	margin-bottom: 0.5rem;
}

.contacts_soc_tel_container a:nth-child(1)::before {
	position: absolute;
	top: 0;
	left: -35px;
	content: url(../img/skype-icon.png);
	display: block;
}

.contacts_soc_tel_container a:nth-child(2)::before {
	position: absolute;
	top: 0;
	left: -35px;
	content: url(../img/icq-icon.png);
	display: block;
}

.contacts_soc_tel_container a:nth-child(3)::before {
	position: absolute;
	top: 0;
	left: -35px;
	content: url(../img/email-icon.png);
	display: block;
}

.contacts_soc_tel_container a:nth-child(4)::before {
	position: absolute;
	top: 0;
	left: -35px;
	content: url(../img/phone-icon.png);
	display: block;
}

.footer_container p {
	font-size: 0.75rem;
	text-align: center;
	color: #445161;
	margin: 0.5rem auto;
}

@media (max-width: 640px) {
	.layout .header_container {
		width: 98vw;
	}
	.h1_container {
		width: 85vw;
		margin: 0 auto;
		margin-bottom: 1rem;
	}
	.h1_container h1 {
		font-size: clamp(2rem, calc(12px + 1vw), 32px);
	}
	.layout h2 {
		font-size: clamp(1.5rem, calc(12px + 1vw), 26px);
	}
	.layout h3,
	.layout .screenshots_container_img_text h3 {
		font-size: clamp(1.2rem, calc(12px + 1vw), 23px);
	}
	.layout .header_img,
	.layout .about_product_img {
		margin: 1.5rem auto;
	}
	.about_product_container_text {
		width: 85vw;
	}
	.layout .about_product_container p {
		margin-bottom: 0.5rem;
	}
	.dignity_product_container {
		flex-wrap: wrap;
	}
	.layout .dignity_product_container ul {
		width: 85vw;
	}
	.layout .screenshots_container_img {
		width: 85vw;
		height: 100%;
		margin-bottom: 1.3rem;
	}
	.layout .screenshots_container_img_text {
		width: 100%;
	}
	.reviews_container_img {
		width: 85vw;
	}
	.layout .tarifs_container {
		flex-wrap: wrap;
	}
	.layout .tarifs_container_elem {
		width: 85vw;
		margin-bottom: 1.5rem;
	}
	.layout .contacts_container {
		flex-wrap: wrap;
	}
	.layout form {
		width: 85vw;
		margin-bottom: 2rem;
	}
}

@media (max-width: 340px) {
	.layout .reviews_img {
		margin: 0 auto;

	}
	.layout .reviews_container_img_text {
		width: 100%;
		margin-top: 1rem;
	}
	.layout .reviews_container_img_text::before {
		content: "";
		top: -20px;
		left: 50%;
		transform: translateX(-50%);
		width: 0;
		height: 0;
		position: absolute;
		border-left: 8px solid transparent;
		border-right: 8px solid transparent;
		border-bottom: 12px solid #ebebeb;
	}
}

.test_p2 main {
	position:relative;
	display:flex;
	justify-content:center;
	align-items:center;
	flex-wrap:nowrap;
	
}

.test_p2 p {
	color: red;
	text-transform:uppercase;
}

.test_p2 nav {
	background-color: #fff;
}

.test_p2 .logo {
	width: 100px;
	height:100px;
	position:relative;
	border:1px solid #161616;
}

.test_p2 .contacts {
	position: absolute;
	width: 30%;
	top:0;
	right:0;
	height:auto;
	border:1px solid #161616;
}

.test_p2 .menu {
	position:sticky;
	border:1px solid #161616;
}

.test_p2 aside {
	width:20%;
	position:relative;
	left:0;
	height:70vh;
	border:1px solid #161616;
}

.test_p2 section {
	width: calc(100vw - 20%);
	position:relative;
	left:auto;
	right:0;
	height:70vh;
	border:1px solid #161616;
}

.test_p2 footer {
	position:relative;
	bottom:0;
	height:10vh;
	border:1px solid #161616;
}

.break-line {
	width: 100%;
	height: 4px;
	background-color: #008B8B;
}
</pre></code>
          </div>

