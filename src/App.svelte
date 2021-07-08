<script>
	
</script>

<main>
	<div class="page">
		<header>
			<div class="nav-container">
				<div class="logo">						
				</div>
				<ul class="nav-items">
					<li>    
						<a href={'#'}>About</a>					
					</li>
					<li>
						<a href={'#'}>Services</a>					
					</li>
					<li>
						<a href={'#'}>Projects</a>					
					</li>
					<button class="contact-button">Contact</button>	
				</ul>			
			</div>
			<div class="title">
				<p>We are creatives</p> 
			</div>
			<div class="arrow">
				<img class="images" src="/images/icon-arrow-down.svg" alt="arrow down">
			</div>			
		</header>
	
		
		<div class="main">
			<div class="row1">
				<div class="row">
					<div class="rowtext">
						<p class="text-title">Transform your brand</p>
						<p class="text-standart">We are a full-service creative agency specializing in helping brands grow fast. Engage your clients through compelling visuals that do most of the marketing for you.</p>
						<div class="text-link">    
							<a class="link-text" href={'#'}>Learn More</a>
							<div class="link-box"></div>					
						</div>						
					</div>					
				</div>
				<div class=row1-2>
					<img class="images" src="/images/image-transform.jpg" alt="egg">
				</div>

			</div>
			<div class="row2">
				<div class="row2-1" >
					<img class="images" src="/images/image-stand-out.jpg" alt="glass">
				</div>
				<div class="row">
					<div class="rowtext">
						<p class="text-title">Stand out to the right audience</p>
						<p class="text-standart">Using a collaborative formula of designers, researchers, photographers, videographers, and copywriters, we’ll build and extend your brand in digital places. </p>
						<div class="text-link">    
							<a class="link-text" href={'#'}>Learn More</a>
							<div class="link-box"></div>					
						</div>
					</div>									
				</div>
			</div>
			<div class="row3">
				<div class="row3-1">
					<div class="row3text">
						<p class="titlesmall">Graphic Design</p>
						<p class="titlesmall3">Great design makes you memorable. We deliver artwork that underscores your brand message and captures potential clients’ attention.</p>			
					</div>	
				</div>
				<div class="row3-2">
					<div class="row3text">
						<p class="titlesmall">Photography</p>
						<p class="titlesmall3">Increase your credibility by getting the most stunning, high-quality photos that improve your business image.</p>
					</div>
				</div>
			</div>			
		</div>
		<div class="testimonials">
			<p class="titlesmall2">CLIENT TESTIMONIALS</p>
			<div class="people">
				<div class="person">
					<img class="person-image" src="/images/image-emily.jpg" alt="Emily" >
					<p class="person-text">We put our trust in Sunnyside and they delivered, making sure our needs were met and deadlines were always hit.</p>
					<p class="person-name">Emily R.</p>
					<p class="jobtext">Marketing Director</p>
				</div>
				<div class="person">
					<img class="person-image" src="/images/image-thomas.jpg" alt="Thomas" >
					<p class="person-text">Sunnyside’s enthusiasm coupled with their keen interest in our brand’s success made it a satisfying and enjoyable experience.</p>
					<p class="person-name">Thomas S.</p>
					<p class="jobtext">Chief Operating Officer</p>
				</div>
				<div class="person">
					<img class="person-image" src="/images/image-jennie.jpg" alt="Jennie" >
					<p class="person-text">Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly recommended!</p>
					<p class="person-name">Jennie F.</p>
					<p class="jobtext">Business Owner</p>
				</div>
			</div>
		</div>
		<div class=bottomvisuals>
			<div class="visuals"><img src="/images/image-gallery-milkbottles.jpg" alt="Milk Bottles"></div>
			<div class="visuals"><img src="/images/image-gallery-orange.jpg" alt="Orange"></div>
			<div class="visuals"><img src="/images/image-gallery-cone.jpg" alt="Cone"></div>
			<div class="visuals"><img src="/images/image-gallery-sugarcubes.jpg" alt="Sugar Cubes"></div>						
		</div>
		<div class="footer">
			<div class="logo-footer">
				<img class="logo-footer1" src="/images/logo.svg" alt="logo">
			</div>
			<div class="bottom-links">
				<div class="bottom-nav-items text-standart">					
						<a class="footer-text" href={'#'}>About</a>						
						<a class="footer-text" href={'#'}>Services</a>
						<a class="footer-text" href={'#'}>Projects</a>						
				</div>				
			</div>
			<div class="social-media">
				<a href={'#'}><img class="social-media-items" src="/images/icon-facebook.svg" alt="facebook"></a>
				<a href={'#'}><img class="social-media-items" src="/images/icon-instagram.svg" alt="instagram"></a>
				<a href={'#'}><img class="social-media-items" src="/images/icon-twitter.svg" alt="twitter"></a>
				<a href={'#'}><img class="social-media-items" src="/images/icon-pinterest.svg" alt="pinterest"></a>
			</div>
		</div>		
	</div>	
</main>

<style>
	.page{
		display: flex;
		flex-direction: column;
		width:1440px;		
	}
	
	header{
		height: 800px;
		background-image:url(/images/image-header.jpg);
		background-size: cover;		
	}
	.nav-container{
		display: flex;
		justify-content: space-between;
		height:56px;
	}
	.logo{
		margin-left: 40px;
		margin-top: 46px;
		width: 170px;
		height: 33px;
		background-image:url(/images/logo.svg);
		background-size: cover;
	}
	.nav-items{
		display: flex;		
		list-style: none;
		margin-right: 50px;
		
	}
	.nav-items li{
		margin-top: 50px;
		margin-right: 50px;
		font-family: Barlow;
		font-size: 18px;
		font-style: normal;
		font-weight: 600;
		line-height: 25px;
		letter-spacing: -0.12857143580913544px;		
	}
	.nav-items li a {
			color: #FFFFFF;
			text-decoration: none;
		}
	.contact-button{
		width: 140px;
		height: 56px;
		margin-top: 34px;
		margin-right: 48px;
		font-family: Fraunces;
		font-size: 15px;
		font-style: normal;
		font-weight: 700;
		line-height: 25px;
		letter-spacing: -0.1071428582072258px;
		color:#24303E;
		text-transform: uppercase;
		background: rgba(#FFFFFF, 1);
		border-radius: 28px;
		text-align: center;
	}
	.contact-button:hover{
		background: rgba(255, 255, 255, 0.25);		
		color:white;
		border: none;	
	}
	.title{
		margin-top: 139px;
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 56px;
		line-height: 69px;
		color: #FFFFFF;
		text-align: center;
		letter-spacing: 8.75px;
		text-transform: uppercase;
	}
	.arrow{
		margin-top: 96px;
		text-align: center;
	}
	
	.main{
		display: flex;
		flex-direction: column;				
	}	
	.row1{
		display: flex;		
	}
	.row{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;		
		width: 50%;
	}
	.rowtext {
		width:445px;
		height: 285px;
	}
	.text-title {
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 40px;
		line-height: 49px;
		letter-spacing: -0.285714px;
	}
	.text-standart{
		font-family: Barlow;
		font-style: normal;
		font-weight: 600;
		font-size: 18px;
		line-height: 30px;
		letter-spacing: -0.128571px;
		color: #808397;
	}
	.titlesmall {
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 28px;
		line-height: 35px;
		text-align: center;
		letter-spacing: -0.2px;
		color: #24554A;			
	}
	.titlesmall2 {
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 20px;
		line-height: 25px;
		text-align: center;
		letter-spacing: 5px;
		color: #A7AAAD;		
	}
	.titlesmall3{
		font-family: Barlow;
		font-style: normal;
		font-weight: 600;
		font-size: 16px;
		line-height: 27px;		
		text-align: center;
		letter-spacing: -0.114286px;
		color: #24554A;
	}
	.jobtext{
		font-family: Barlow;
		font-style: normal;
		font-weight: 600;
		font-size: 14px;
		line-height: 25px;
		text-align: center;
		letter-spacing: -0.1px;
		color: #A7AAAD;
		margin-top: -20px;
	}
	.link-text{
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 15px;
		line-height: 25px;
		letter-spacing: 1px;
		text-transform: uppercase;
		color: #24303E;		
		text-decoration-line: none;	
	}
	.link-box{
		width: 137px;
		height: 10px;
		background: #FAD400;
		opacity: 0.25;
		mix-blend-mode: normal;
		
		border-radius: 5px;
		margin-top: -10px;
		z-index: -1;
		
	}
	.text-link{
		display:flex;
		flex-direction: column;				
		align-items: center;
		width:137px;
	}
    .text-link:hover .link-box {
    	opacity: 1;  
    }
	.row2{
		display: flex;	
	}
	.row2-1{
		display: flex;
		width: 50%;
		flex-shrink: 1;
	}
	.row3{
		display: flex;
		flex-shrink: 1;
		height: 600px;
	}
	.row3-1{
		background-image:url(/images/image-graphic-design.jpg);
		background-size: cover;
		display: flex;
		flex-direction: column;
		width: 50%;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.row3-2{
		background-image:url(/images/image-photography.jpg);
		background-size: cover;
		display: flex;
		flex-direction: column;
		width:50%;
		display: flex;
		justify-content: center;
		align-items: center;		
	}
	.row3text{
		margin-top: 300px;
		width:339px;
		
	}
	.testimonials{		
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		margin-top: 100px;
		height:457px;
		margin-top: 150px;
		margin-bottom: 150px;
	}
	.people{
		display: flex;
		flex-direction: row;
	}
	.person {
		display:flex;
		flex-direction: column;
		align-items: center;
		text-align: center;
		justify-content: center;
		margin: 50px 30px;
	}
	.person-image {
		width: 72px;
		height: 72px;
		border-radius: 50%;
	}
	.person-text {
		margin-top:50px;
		width:350px;
		height:96px;
		font-family: Barlow;
		font-style: normal;
		font-weight: 600;
		font-size: 18px;
		line-height: 32px;
		text-align: center;
		letter-spacing: -0.128571px;
		color: #5B636D;
	}
	.person-name {
		font-family: Fraunces;
		font-style: normal;
		font-weight: 900;
		font-size: 18px;
		line-height: 22px;
		text-align: center;
		letter-spacing: -0.128571px;
		color: #24303E;
		margin-top:40px;
		
	}
	.bottomvisuals{
		display:flex;		
		height: 447px;		
	}
	.visuals{
		display: flex;
		width: 25%;
	}
	.footer{
		background: #90D4C6;
		display: flex;
		flex-direction: column;
		align-items: center;	
		height: 350px;	
	}
	.footer-text{
		color: #458D7E;
	}
	.logo-footer1 {
		width: 170px;
		height: 33px;
		filter: invert(42%) sepia(93%) saturate(1352%) hue-rotate(130deg) brightness(55%) contrast(119%);	
	}
	.logo-footer{
		margin-top:72px;
		margin-bottom: 40px;
	}
	.bottom-links {
		display:flex;					
	}
	.bottom-nav-items {		
		display: flex;
		justify-content: space-between;	
		list-style: none;
		width: 300px;	
		margin-bottom:88px;		
	}
	.bottom-links .bottom-nav-items a:hover {
		text-decoration: none;
		color:white;
	}
	.social-media {
		display: flex;
		width:164px;
		justify-content: space-between;
		margin-top:8px;
	}
	.social-media a:hover{
		filter: invert(42%) sepia(93%) saturate(1%) hue-rotate(130deg) brightness(500%) contrast(119%);
	}

</style>