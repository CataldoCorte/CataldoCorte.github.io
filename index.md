<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<title>Cataldo Corte & Costura</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="">
	<!--[if ie]><meta content='IE=8' http-equiv='X-UA-Compatible'/><![endif]-->
	<!-- bootstrap -->
	<link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
	<link href="bootstrap/css/bootstrap-responsive.min.css" rel="stylesheet">

	<link href="themes/css/bootstrappage.css" rel="stylesheet" />

	<!--favIcon-->
	<link rel="icon" type="image/png" sizes="32x32" href="themes/images/favicon-32x32.png">
	<link rel="apple-touch-icon" sizes="180x180" href="themes/images/apple-touch-icon.png">

	<!-- global styles -->
	<link href="themes/css/flexslider.css" rel="stylesheet" />
	<link href="themes/css/main.css" rel="stylesheet" />
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

	<!-- scripts -->
	<script src="themes/js/jquery-1.7.2.min.js"></script>
	<script src="bootstrap/js/bootstrap.min.js"></script>
	<script src="themes/js/superfish.js"></script>
	<script src="themes/js/jquery.scrolltotop.js"></script>
	<!--[if lt IE 9]>			
			<script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
			<script src="js/respond.min.js"></script>
		<![endif]-->
</head>

<body>
	<div id="wrapper" class="container">
		<section class="navbar main-menu">
			<div class="navbar-inner main-menu">
				<a href="index.html" class="logo pull-left"><img src="themes/images/logo.png" class="site_logo"
						alt=""></a>
				<nav id="menu" class="pull-right">
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="servicos.html">Serviços</a></li>
						<li><a href="sobre.html">Sobre</a></li>
						<li><a href="./contact.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</section>
		<section class="homepage-slider" id="home-slider">
			<div class="flexslider">
				<ul class="slides">
					<li>
						<img src="themes/images/carousel/banner-1.jpg" alt="" />
					</li>
					<li>
						<img src="themes/images/carousel/banner-2.png" alt="" />
						<div class="intro">
							<h1>Novidade!</h1>
							<p><span>Até 50% Off</span></p>
							<p><span>Encomendamos com diferentes cores e tamanhos</span></p>
						</div>
					</li>
				</ul>
			</div>
		</section>
		<section class="header_text">
			A mais alta moda para roupas de banho, venha conferir nossos produtos e fazer sua encomenda.
			<br />Tudo de forma personalizada, tenha hoje mesmo uma peça unicamente sua.
		</section>
		<section class="main-content">
			<div class="row">
				<div class="span12">
					<div class="row">
						<div class="span12">
							<h4 class="title">
								<span class="pull-left"><span class="text"><span class="line">Mais
											<strong>Vendidos</strong></span></span></span>
								<span class="pull-right">
									<a class="left button" href="#myCarousel" data-slide="prev"></a><a
										class="right button" href="#myCarousel" data-slide="next"></a>
								</span>
							</h4>
							<div id="myCarousel" class="myCarousel carousel slide">
								<div class="carousel-inner">
									<div class="active item">
										<ul class="thumbnails">
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<span class="sale_tag"></span>
													<p><a href="javascript:AbrirModalProduto(1)"><img
																src="../shopper/img-products/Bikini-azul2.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(1)" id="produto1" class="title">Biquini Azul Piscina</a><br />
													<a href="javascript:AbrirModalProduto(1)" class="category">Comprar</a></br>
													<a href="products.html" class="category">Carrinho</a>
													<p id="precoProduto1" class="price">R$119,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<span class="sale_tag"></span>
													<p><a href="javascript:AbrirModalProduto(2)"><img
																src="../shopper/img-products/Bikini-banana.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(2)" id="produto2" class="title">Biquini Rosa com Estampa</a><br />
													<a href="javascript:AbrirModalProduto(2)" class="category">Comprar</a></br>
													<a href="products.html" class="category">Carrinho</a>
													<p id="precoProdutor2" class="price">R$149,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(3)"><img
																src="../shopper/img-products/Bikini-rosa2.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(3)" id="produto3" class="title">Biquini Rosa</a><br />
													<a href="javascript:AbrirModalProduto(3)" class="category">Comprar</a></br>
													<a href="products.html" class="category">Carrinho</a>
													<p id="precoProdutor3" class="price">R$119,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(4)"><img
																src="../shopper/img-products/Bikini-beje.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(4)" id="produto4" class="title">Biquini Beje</a><br />
													<a href="javascript:AbrirModalProduto(4)" class="category">Comprar</a></br>
													<a href="javascript:AbrirModalProduto(4)" class="category">Carrinho</a>
													<p id="precoProdutor4" class="price">R$119,00</p>
												</div>
											</li>
										</ul>
									</div>
									<div class="item">
										<ul class="thumbnails">
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(5)"><img
																src="../shopper/img-products/Bikini-vermelho.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(5)" id="produto5" class="title">Biquini Vermelhor</a><br />
													<a href="javascript:AbrirModalProduto(5)" class="category">Comprar</a></br>
													<a href="javascript:AbrirModalProduto(5)" class="category">Carrinho</a>
													<p id="precoProdutor5"  class="price">R$139,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(6)"><img
																src="../shopper/img-products/Bikini-rosa.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(6)" id="produto6" class="title">Biquini Pessego</a><br />
													<a href="javascript:AbrirModalProduto(6)" class="category">Comprar</a></br>
													<a href="javascript:AbrirModalProduto(6)" class="category">Carrinho</a>
													<p id="precoProdutor6"  class="price">R$119,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(7)"><img
																src="../shopper/img-products/Bikini-pretobranco.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(7)" id="produto7" class="title">Biquini de Bolinhas</a><br />
													<a href="javascript:AbrirModalProduto(7)" class="category">Comprar</a></br>
													<a href="javascript:AbrirModalProduto(7)" class="category">Carrinho</a>
													<p id="precoProdutor7" class="price">R$139,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(8)"><img
																src="../shopper/img-products/Biquini-azulclaro.jpg" alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(8)" id="produto8" class="title">Biquini Azul Claro</a><br />
														<a href="javascript:AbrirModalProduto(8)" class="category">Comprar</a></br>
														<a href="javascript:AbrirModalProduto(8)" class="category">Carrinho</a>
														<p id="precoProdutor8"  class="price">R$139,00</p>
												</div>
											</li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
					<br />
					<div class="row">
						<div class="span12">
							<h4 class="title">
								<span class="pull-left"><span class="text"><span class="line">Novidades
											<strong>Quentes</strong></span></span></span>
								<span class="pull-right">
									<a class="left button" href="#myCarousel-2" data-slide="prev"></a><a
										class="right button" href="#myCarousel-2" data-slide="next"></a>
								</span>
							</h4>
							<div id="myCarousel-2" class="myCarousel carousel slide">
								<div class="carousel-inner">
									<div class="active item">
										<ul class="thumbnails">
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<span class="sale_tag"></span>
													<p><a href="javascript:AbrirModalProduto(9)"><img
																src="../shopper/img-products/Bikini-azulmarinho.jpg"
																alt="" /></a></p>
													<a href="javascript:AbrirModalProduto(9)" id="produto9" class="title">Biquini Azul Escuro</a><br />
														<a href="javascript:AbrirModalProduto(9)" class="category">Comprar</a></br>
														<a href="javascript:AbrirModalProduto(9)" class="category">Carrinho</a>
														<p id="precoProdutor9" class="price">R$139,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(10)"><img
																src="../shopper/img-products/Bikini-vermelhoouro.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(10)" id="produto10" class="title">Biquini Vermelho com Laço</a><br />
																<a href="javascript:AbrirModalProduto(10)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(10)" class="category">Carrinho</a>
																<p id="precoProdutor10" class="price">R$139,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(11)"><img
																src="../shopper/img-products/Bikini-ouro.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(11)" id="produto11" class="title">Biquini Ouro com Laço</a><br />
																<a href="javascript:AbrirModalProduto(11)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(11)" class="category">Carrinho</a>
																<p id="precoProdutor11" class="price">R$139,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(12)"><img
																src="../shopper/img-products/Bikini-varios.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(12)" id="produto12" class="title">Conjunto Biquinis Variados</a><br />
																<a href="javascript:AbrirModalProduto(12)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(12)" class="category">Carrinho</a>
																<p id="precoProdutor12" class="price">R$299,00</p>
												</div>
											</li>
										</ul>
									</div>
									<div class="item">
										<ul class="thumbnails">
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(13)"><img
																src="../shopper/img-products/Bikini-preto.jfif"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(13)" id="produto13" class="title">Biquinis Preto com duas partes de cima</a><br />
																<a href="javascript:AbrirModalProduto(13)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(13)" class="category">Carrinho</a>
																<p id="precoProdutor13" class="price">R$209,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(14)"><img
																src="../shopper/img-products/Bikini-roxo.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(14)" id="produto14" class="title">Biquinis Roxo com duas partes de cima</a><br />
																<a href="javascript:AbrirModalProduto(14)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(14)" class="category">Carrinho</a>
																<p id="precoProdutor14" class="price">R$209,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(15)"><img
																src="../shopper/img-products/maios2.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(15)" id="produto15" class="title">Conjunto de Maios</a><br />
																<a href="javascript:AbrirModalProduto(15)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(15)" class="category">Carrinho</a>
																<p id="precoProdutor15" class="price">R$259,00</p>
												</div>
											</li>
											<li class="span3">
												<div class="product-box">
													<input type="hidden" class="produtoSelecionado" value="false" />
													<p><a href="javascript:AbrirModalProduto(16)"><img
																src="../shopper/img-products/maios.jpg"
																alt="" /></a></p>
																<a href="javascript:AbrirModalProduto(16)" id="produto16" class="title">Conjunto de Maios</a><br />
																<a href="javascript:AbrirModalProduto(16)" class="category">Comprar</a></br>
																<a href="javascript:AbrirModalProduto(16)" class="category">Carrinho</a>
																<p id="precoProdutor16" class="price">R$359,00</p>
												</div>
												
											</li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="row feature_box">
						<div class="span4">
							<div class="service">
								<div class="responsive">
									<img src="themes/images/feature_img_2.png" alt="" />
									<h4>DESIGN <strong>MODERNO</strong></h4>
									<p>Modelos mais recentes para a moda praia, com alta qualidade de costura e grande aceitação pelo consumidor.</p>
								</div>
							</div>
						</div>
						<div class="span4">
							<div class="service">
								<div class="customize">
									<img src="themes/images/feature_img_1.png" alt="" />
									<h4>FRETE<strong>GRÁTIS</strong></h4>
									<p>Enviamos para todo o Brasil de forma gratuita na compra de dois ou mais produtos.</p>
								</div>
							</div>
						</div>
						<div class="span4">
							<div class="service">
								<div class="support">
									<img src="themes/images/feature_img_3.png" alt="" />
									<h4>TIRE SUAS <strong>DÚVIDAS</strong></h4>
									<p>Em caso de dúvida entre em contato com a nossa equipe pelo nosso Whatsapp.</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<!-- 
		<section class="our_client">
			<h4 class="title"><span class="text">Manufactures</span></h4>
			<div class="row">
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/14.png"></a>
				</div>
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/35.png"></a>
				</div>
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/1.png"></a>
				</div>
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/2.png"></a>
				</div>
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/3.png"></a>
				</div>
				<div class="span2">
					<a href="#"><img alt="" src="themes/images/clients/4.png"></a>
				</div>
			</div>
		</section>
		-->
		<section id="footer-bar" >
			<div class="row" >
				<div class="span12" >
					<p class="logo-novo"><img src="themes/images/logo.png" class="site_logo" alt=""></p>
					<p class="novo-p">Temos o compromisso com o nosso consumidor, usamos os melhores materiais e uma mão-de-obra qualificada. Nossos produtos têm qualidade assegurada, venha conferir agora mesmo. Caso não tenha encontrado o produto que deseja venha fazer um orçamento para a confecção de um modelo exclusivo para você. Chame no WhatsApp (13) 9 9876-5432</p>
					<br />
				</div>
			</div>
		</section>
		<section id="copyright">
			<span>Copyright 20220 Cataldo Corte & Costura.</span>
		</section>
	</div>
		<!-- Começo Modal -->
		<div class="modal fade" id="modalCompra" tabindex="-1" role="dialog" aria-labelledby="AdicionarCarrinho"
		aria-hidden="true">
		<div class="modal-dialog" role="document">
			<div class="modal-content">
				<div class="modal-header">
					<h5 class="modal-title" id="modalLabel">Produto Selecionado</h5>
				</div>
				<div class="modal-body">
					<input type="hidden" id="ultimoProdutoSelecionadoId" />
					Você selecionou o produto <span id="nomeProdutoSelecionado"></span>
					<br>
					Clique aqui para falar conosco sobre este produto, ou aqui para adicionar ao carrinho e continuar
					escolhendo.
				</div>
				<div class="modal-footer">
					<button type="button" class="btn btn-success" onclick="EnviarMensagemWhatsapp()">Pedir
						informações</button>
					<button type="button" class="btn btn-primary" onclick="ContinuarComprando()">Continuar
						selecionando</button>
				</div>
			</div>
		</div>
	</div>
	<!-- Fim modal -->


	<script src="themes/js/common.js"></script>
	<script src="themes/js/jquery.flexslider-min.js"></script>
	<script type="text/javascript">
		$(function () {
			$(document).ready(function () {
				$('.flexslider').flexslider({
					animation: "fade",
					slideshowSpeed: 4000,
					animationSpeed: 600,
					controlNav: false,
					directionNav: true,
					controlsContainer: ".flex-container" // the container that holds the flexslider
				});
			});
		});
	</script>

	<script>
		function AbrirModalProduto(idProduto) {
			if ($('#produto' + idProduto).closest('.product-box').find('.produtoSelecionado').val() === "false") {
				$('#modalCompra').modal();
				var nomeProduto = $('#produto' + idProduto);
				$('#ultimoProdutoSelecionadoId').val(idProduto);
				$('#nomeProdutoSelecionado').text($('#produto' + idProduto).text());
			}
			else {
				$('#produto' + idProduto).closest('.product-box').removeAttr("style");
				$('#produto' + idProduto).closest('.product-box').find('.produtoSelecionado').val(false);
				carrinho = carrinho.filter(produto => produto != idProduto);
			}
		}

		function EnviarMensagemWhatsapp() {
			var ultimoProdutoSelecionadoId = $('#ultimoProdutoSelecionadoId').val();
			carrinho.push(ultimoProdutoSelecionadoId);
			var mensagem = "Olá, gostaria de saber mais informações sobre o produto #produto# ! :)";

			carrinho = carrinho.filter(onlyUnique);

			if (carrinho.length <= 1) {
				$('#modalCompra').modal('toggle');
				mensagem = mensagem.replace('#produto#',$('#produto' + $('#ultimoProdutoSelecionadoId').val()).text());
				alert(mensagem); //trocar pelo whatsapp
				carrinho = [];
			}
			else {
				var produtos = "";
				$(carrinho).each(function (i, produto) {
					produtos += $('#produto' + produto).text() + ", ";
				})
				produtos = produtos.slice(0, -1);
				produtos = produtos.slice(0, -1);
				mensagem = mensagem.replace('o produto', 'os produtos');
				mensagem = mensagem.replace('#produto#', produtos);
				alert(mensagem); //trocar pelo whatsapp
				carrinho = [];
			}
		}
		var carrinho = [];
		function ContinuarComprando() {
			var ultimoProdutoSelecionadoId = $('#ultimoProdutoSelecionadoId').val();
			var produtoAtivo = $('#produto' + ultimoProdutoSelecionadoId).closest('.product-box').find('.produtoSelecionado').val();
			if (produtoAtivo === "false") {
				$('#produto' + ultimoProdutoSelecionadoId).closest('.product-box').css("background-color", '#5772a8');
				$('#produto' + ultimoProdutoSelecionadoId).closest('.product-box').find('.produtoSelecionado').val(true);
				$('#modalCompra').modal('toggle');
				carrinho.push(ultimoProdutoSelecionadoId);
			}
		}

		function onlyUnique(value, index, self) {
			return self.indexOf(value) === index;
		}
	</script>

</body>

</html>GET
