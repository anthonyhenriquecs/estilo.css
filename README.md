body {
	background-color: #282828;
	color: #fff;
}

.cabecalho {
	height: 80px;
	background-color: #0b0b0b;
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 0 80px;
	border-bottom: 1px solid #282828;
}

.cabecalho .logo {
	display: flex;
	gap: 15px;
}

.cabecalho .menu {
	display: flex;
	gap: 30px;
}

.cabecalho .menu li a {
	padding: 30px;
	color: #e8e8e8;
	font-weight: bolder;
	font-size: 15px;
	font-family: "Chalet";
}

.cabecalho .menu li a:hover {
	border-bottom: 2px solid #fff;
}

.home {
	display: flex;
	position: relative;
	min-height: calc(100vh - 80px);
}

.home::after {
	content: "";
	position: absolute;
	height: 100%;
	width: 100%;
	background: linear-gradient(90deg, rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.7) 35%, transparent 65%);
}

.home .imagem-fundo {
	width: 100%;
	object-fit: cover;
}

.home .informacoes {
	position: absolute;
	z-index: 1;
	min-height: calc(100vh - 80px);
	display: flex;
	flex-direction: column;
	justify-content: center;
	gap: 32px;
	padding: 80px 80px 80px 170px;
	max-width: 780px;
}

.home .informacoes img {
	max-width: 150px;
}

.home .informacoes .lista-de-jogos {
	display: flex;
	gap: 32px;
}

.home .informacoes .titulo {
	font-family: "ChaletComprime";
	font-size: 55px;
}

.home .informacoes .texto {
	font-family: "Chalet";
	font-size: 18px;
	line-height: 1.6;
}

.btn-comprar,
.btn-plataforma {
	background-color: rgba(255, 255, 255, 0.1);
	border: 0.5px solid #fff;
	border-radius: 4px;
	font-family: "ChaletComprime";
	font-size: 28px;
	text-align: center;
	padding: 20px 40px;
	text-transform: uppercase;
	width: 50%;
	transition: all 0.3s ease-in;
}

.btn-plataforma {
	color: #fff;
	width: 100%;
	cursor: pointer;
}

.btn-comprar:hover {
	background-color: #fff;
	color: #000;
}

.compre-ja .capa-do-jogo {
	width: 270px;
}

.compre-ja {
	display: flex;
	flex-direction: column;
	text-align: center;
	padding: 50px;
	align-items: center;
}

.compre-ja .titulo {
	font-family: "ChaletComprime";
	font-size: 50px;
	font-weight: 700;
	margin-bottom: 50px;
}

.compre-ja .cartao {
	display: flex;
	flex-direction: column;
	align-items: center;
	background-color: #000;
	width: 50%;
	border-radius: 10px;
	padding: 80px;
	gap: 40px;
}

.compre-ja .informacoes {
	display: flex;
	flex-direction: column;
	gap: 30px;
}

.compre-ja .informacoes h3 {
	font-family: "ChaletComprime";
	font-size: 52px;
	font-weight: 700;
}

.compre-ja .informacoes p {
	color: #e8e8e8;
	font-family: "Chalet";
	font-size: 16px;
	line-height: 1.6;
}

.compre-ja .informacoes .plataformas {
	display: flex;
	flex-wrap: wrap;
	gap: 32px;
	justify-content: center;
}

.compre-ja .btn-plataforma .plataformas {
	margin-top: 10px;
	display: flex;
	flex-direction: column;
	gap: 20px;
	transition: all 0.3s ease-in;
	display: none;
	opacity: 0;
}

.compre-ja .btn-plataforma .plataformas.ativo {
	display: flex;
	opacity: 1;
}

.compre-ja .btn-plataforma .plataformas li {
	padding: 20px;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(1) {
	border: 1px solid #00439c;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(1):hover {
	background-color: #00439c;
}
.compre-ja .btn-plataforma .plataformas li:nth-child(2) {
	border: 1px solid #387a26;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(2):hover {
	background-color: #387a26;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(3) {
	border: 1px solid #00439c;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(3):hover {
	background-color: #00439c;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(4) {
	border: 1px solid #387a26;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(4):hover {
	background-color: #387a26;
}
.compre-ja .btn-plataforma .plataformas li:nth-child(5) {
	border: 1px solid #fcaf17;
}

.compre-ja .btn-plataforma .plataformas li:nth-child(5):hover {
	background-color: #fcaf17;
}
