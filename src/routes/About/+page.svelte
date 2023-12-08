<script>
	import VariPull from '$lib/assets/mushIngr.jpg';
	import SidePull from '$lib/assets/steamyComboPull.jpg';
	import TopPull from '$lib/assets/Aboutim.jpg';
</script>

<banner>
	<img src={TopPull} alt="background" />
</banner>

<div class="text_Block">
	<p class="text_Box">
		Fairgrounds Pizza unfolds a remarkable five-decade tale, woven with passion, tradition, and a
		commitment to serving the community. In 1973, our founders, Maria and Tony, embarked on a
		culinary journey, transforming a modest corner into what would become the heart of the
		neighborhood. From the very beginning, their dedication to crafting exceptional pizzas and
		fostering a welcoming atmosphere laid the foundation for Fairgrounds Pizza's enduring legacy.
	</p>

	<p class="text_Box glass_Back">
		As the years unfolded, Fairgrounds Pizza became a cherished gathering place for families,
		friends, and pizza enthusiasts alike. The aroma of our freshly baked pies became synonymous with
		the warmth and camaraderie that filled the air. Through the ups and downs of the decades, the
		pizzeria evolved, adapting to changing tastes while staying true to its roots.
	</p>

	<p class="text_Box">
		In the midst of the Great Robot War of 1993, Fairgrounds Pizza stood resilient, a beacon of
		normalcy in tumultuous times. Despite the challenges posed by the robotic uprising, our
		dedicated team continued to roll out dough, spread sauce, and sprinkle toppings, offering a
		haven where the community could find solace and comfort. The pizzeria became a symbol of
		perseverance, turning each pizza into a testament of resilience and a slice of hope during those
		challenging days.
	</p>

	<div class="img_Gap">
		<img src={VariPull} alt="background" />
	</div>

	<p class="text_Box glass_Back">
		Throughout the fifty-year journey, Fairgrounds Pizza has been more than a place to enjoy
		delicious food; it's a living testament to the power of community and the enduring appeal of a
		slice of the past. From the original recipes passed down through generations to the smiling
		faces that have walked through our doors, each element contributes to the rich tapestry that is
		the story of Fairgrounds Pizza. As we celebrate this half-century milestone, we look back with
		gratitude for the memories shared, the challenges overcome, and the joy found in every
		pizza-loving moment.
	</p>

	<p class="text_Box">
		Today, as we continue our tradition of serving mouthwatering pizzas, Fairgrounds Pizza remains a
		cornerstone of the neighborhood, a place where families create new memories and friends come
		together over a shared love for exceptional pizza. Here's to the next fifty years of
		deliciousness, community, and the timeless joy of Fairgrounds Pizza.
	</p>

	<div class="img_Gap">
		<img src={SidePull} alt="background" />
	</div>
</div>

<!-- svelte-ignore css-unused-selector -->
<style lang="scss">
	.img_Gap {
		img {
			width: 60%;
			margin: 0 20%;
		}
	}

	@media only screen and (min-width: 980px) {
		destination {
			display: none;
		}
	}
</style>
