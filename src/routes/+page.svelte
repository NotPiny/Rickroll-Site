<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />

	<meta property="og:title" content="Home" />
</svelte:head>

<section>
	<p>Please wait for website to load</p>
	<h1>
		<span class="welcome">
			<img src="https://thisimagewillnotload.com/495/2048" alt="Gayming news logo" />
		</span>

		Welcome to Gayming news, Your source for the gayest gaming news, reviews, and more!
	</h1>
</section>

<!-- svelte-ignore a11y-media-has-caption -->
<video style="display: none;" autoplay>
	<source src="https://shattereddisk.github.io/rickroll/rickroll.mp4" type="video/mp4" />
	Your browser does not support the video tag.
</video>
<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;

		font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
