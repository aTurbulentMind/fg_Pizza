<script>
	//images
	import TopPull from '$lib/assets/Menim.jpg';
	import pic_One from '$lib/assets/mushIngr.jpg';
	import pic_Two from '$lib/assets/olivTom.jpg';
	import pic_Three from '$lib/assets/pepOlivChePull.jpg';
	import pic_Four from '$lib/assets/simplZZZA.jpg';
	import pic_Five from '$lib/assets/squarComb.jpg';
	import pic_Six from '$lib/assets/steamyComboPull.jpg';
</script>

<banner>
	<img src={TopPull} alt="background" />
</banner>

<div class="grid">
	<div class="card glass_Back">
		<div class="card-title">Supreme</div>

		<img src={pic_One} alt="background" />
		<ul>
			<li>S: $12</li>
			<li>M: $15</li>
			<li>L: $20</li>
		</ul>

		<div class="card-body">
			Dive into our Supreme Pizza, a flavor-packed delight featuring a medley of premium toppings.
			From savory sausage to vibrant bell peppers, each bite at Fairgrounds Pizza is a symphony of
			tastes, creating a satisfying and diverse culinary experience.<br />
		</div>
	</div>

	<div class="card glass_Back">
		<div class="card-title">Pineapple & Ham</div>

		<img src={pic_Two} alt="background" />
		<ul>
			<li>S: $12</li>
			<li>M: $15</li>
			<li>L: $20</li>
		</ul>

		<div class="card-body">
			Experience a tropical twist with our Smoked Ham and Grilled Pineapple Pizza at Fairgrounds
			Pizza. The smoky richness of ham pairs perfectly with the sweet and tangy flavor of grilled
			pineapple, creating a mouthwatering combination that transports your taste buds to paradise in
			every bite.<br />
		</div>
	</div>

	<div class="card glass_Back">
		<div class="card-title">Cheese</div>

		<img src={pic_Three} alt="background" />

		<ul>
			<li>S: $12</li>
			<li>M: $15</li>
			<li>L: $20</li>
		</ul>
		<div class="card-body">
			Embrace the simplicity and perfection of our Cheese Pizza at Fairgrounds Pizza. A golden
			crust, luscious tomato sauce, and a generous layer of melted cheese come together in harmony,
			offering a timeless and satisfying classic that celebrates the essence of pure, unadulterated
			goodness.
			<br />
		</div>
	</div>

	<div class="card glass_Back">
		<div class="card-title">Pepperoni</div>

		<img src={pic_Four} alt="background" />
		<ul>
			<li>S: $12</li>
			<li>M: $15</li>
			<li>L: $20</li>
		</ul>

		<div class="card-body">
			Indulge in our pepperoni pizza, a classic masterpiece with zesty slices of pepperoni atop a
			bed of melted cheese. The perfect harmony of crispiness, rich tomato sauce, and golden crust
			delivers a bite-sized explosion of flavor at Fairgrounds Pizza.<br />
		</div>
	</div>

	<div class="card glass_Back">
		<div class="card-title">Vegetarian</div>

		<img src={pic_Five} alt="background" />
		<ul>
			<li>S: $12</li>
			<li>M: $15</li>
			<li>L: $20</li>
		</ul>

		<div class="card-body">
			Delight in our Vegetarian Pizza at Fairgrounds, a garden-fresh symphony of flavors. Crisp
			veggies, vibrant bell peppers, juicy tomatoes, and more, all atop a golden crust with our
			signature tomato sauce and melted cheese. Savor the abundance of nature in every delectable
			slice.<br />
		</div>
	</div>
</div>

<!--svelte-ignore css-unused-selector -->
<style lang="scss">
	.grid {
		.card {
			ul {
				display: flex;
				flex-direction: row;
				justify-content: center;
				align-items: center;
				gap: 1rem;
				margin: 2vh auto;
				list-style: disc;

				li {
					font-size: var(--f_sm);
					text-shadow: var(--text_Shadow);
				}
			}

			img {
				width: 100%;
				border-radius: var(--rad);
			}
		}
	}

	@media only screen and (min-width: 740px) {
		.grid {
			grid-template-columns: 1fr 1fr;
		}
	}

	@media only screen and (min-width: 980px) {
		destination {
			display: none;
		}

		.grid {
			.card {
				font-size: var(--f_lg);

				.card-title {
					font-size: var(--f_lg);
				}

				ul {
					gap: 40px;

					li {
						font-size: var(--f_lg);
					}
				}

				img {
					width: 50%;
					margin: 0 25%;
				}
			}
		}
	}
</style>
