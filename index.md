<!DOCTYPE html> 
 <html lang="eng"> 
	<head> 
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta http-equiv="X-UA-Compatible" content="ie=edge">
		<title>The Tea Cozy</title>
		<meta name="description" content="" />  
		<link rel="stylesheet" type="text/css" href="css/reset.css">
		<link rel="stylesheet" type="text/css" href="css/style.css">
	</head>

	<body>

		<!-- HEADER -->
		<header class="header">
			<div class="header-wrapper">
				<div class="header__logo">
					<a href="#!" class="header__logo-link ">
						<img src="img/logo.png" alt="Tea Cozy" class="header__logo-pic">
					</a>
				</div>
				<nav class="header__nav">
					<ul class="header__list">
						<li class="header__item">
							<a href="#intro " class="header__link js-scroll">Mission</a>
						</li>
						<li class="header__item">
							<a href="#blog" class="header__link js-scroll">Featured Tea</a>
						</li>
						<li class="header__item">
							<a href="#locations" class="header__link js-scroll">Locations</a>
						</li>
					</ul>
					<div class="header__nav-close">
						<span class="header__nav-close-line"></span><span class="header__nav-close-line"></span>
					</div>
				</nav>
				<div class="header__burger burger">
					<span class="burger__line burger__line_first"></span>
					<span class="burger__line burger__line_second"></span>
					<span class="burger__line burger__line_third"></span>
				</div> 
			</div>
		</header>
		<!-- HEADER END -->

		
		<main class="main">
		<!-- INTRO -->
			<section class="intro" id="intro">
				<div class="wrapper intro-bg">
					<div class="intro__items">
						<h2 class="intro__title h2__title ">Our Mission</h2>
						<h4 class="intro__subtitle h4__subtitle">Handpicked, Artisanally Curated, Free Range, Sustainable, Small Batch, Fair Trade, Organic Tea</h4>
					</div>
				</div>
			</section>
		<!-- INTRO END-->

		<!-- BLOG -->

		<section class="blog" id="blog">
			<div class="blog-wrapper">
				<h2 class="blog__title h2__title">Tea of the Month</h2>
				<h4 class="blog__subtitle h4__subtitle">What's Steeping at The Tea Cozy?</h4>
				<div class="blog__cards">
					<figure class="blog__card">
						<img src="img/img-berryblitz.jpg" alt="Fall Berry Blitz Tea" class="blog__card-pic">
						<figcaption class="blog__card-desc h4__subtitle">Fall Berry Blitz Tea</figcaption>
					</figure>
					<figure class="blog__card">
						<img src="img/img-spiced-rum.jpg" alt="Spiced Rum Tea" class="blog__card-pic">
						<figcaption class="blog__card-desc h4__subtitle">Spiced Rum Tea</figcaption>
					</figure>
					<figure class="blog__card">
						<img src="img/img-donut.jpg" alt="Seasonal Donuts" class="blog__card-pic">
						<figcaption class="blog__card-desc h4__subtitle">Seasonal Donuts</figcaption>
					</figure>
					<figure class="blog__card">
						<img src="img/img-myrtle-ave.jpg" alt="Myrtle Ave Tea" class="blog__card-pic">
						<figcaption class="blog__card-desc h4__subtitle">Myrtle Ave Tea</figcaption>
					</figure>
					<figure class="blog__card">
						<img src="img/img-bedford-bizarre.jpg" alt="Bedford Bizarre Tea" class="blog__card-pic">
						<figcaption class="blog__card-desc h4__subtitle">Bedford Bizarre Tea</figcaption>
					</figure>
				</div>
			</div>
		</section>

		<!-- BLOG END -->
		

		<!-- LOCATIONS -->
		
		<section class="locations" id="locations">
			<div class="wrapper locations-bg">
				<h2 class="locations__title h2__title">
					Locations
				</h2>
				<div class="locations__cards">
					<div class="locations__card">
						<h3 class="locations__card-title">
							Downtown
						</h3>
						<p class="locations__card-text">
							384 West 4th St
						</p>
						<p class="locations__card-text">
							Suite 108
						</p>
						<p class="locations__card-text">
							Portland, Maine
						</p>
					</div>
					<div class="locations__card">
						<h3 class="locations__card-title">
							East Bayside
						</h3>
						<p class="locations__card-text">
							3433 Phisherman's Avenue
						</p>
						<p class="locations__card-text">
							(Northwest Corner)
						</p>
						<p class="locations__card-text">
							Portland, Maine
						</p>
					</div>
					<div class="locations__card">
						<h3 class="locations__card-title">
							Oakdale
						</h3>
						<p class="locations__card-text">
							515 Crescent Avenue
						</p>
						<p class="locations__card-text">
							Second Floor
						</p>
						<p class="locations__card-text">
							Portland, Maine
						</p>
					</div>
				</div>
			</div>
		</section>

		<!-- LOCATIONS END -->
		</main>
		
		<!-- FOOTER -->

		<footer class="footer">
			<div class="footer__contacts">
				<h2 class="footer__contacts-brand h2__title">
					The Tea Cozy
				</h2>
				<h5 class="footer__contacts-email">
					contact@theteacozy.com
				</h5>
				<p class="footer__contacts-phone">
					917-555-8904
				</p>
			</div>
			<p class="copyright">
				copyright The Tea Cozy 2017<br>made up by Daniel Sysoev
			</p>
		</footer>
		<!-- FOOTER END -->
		<script src="./js/main-es6.js"></script>
	</body>
</html>