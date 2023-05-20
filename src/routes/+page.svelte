<script>
	import Tesimonial from '../lib/components/Tesimonial.svelte';
	import Hof1 from '$lib/images/hof/hof1.webp';
	import Hof2 from '$lib/images/hof/hof2.webp';
	import Hof3 from '$lib/images/hof/hof3.jpg';
	import Hof4 from '$lib/images/hof/hof4.jpg';
	import Hof5 from '$lib/images/hof/hof5.webp';
	import Hof6 from '$lib/images/hof/hof6.jpg';
	import Hof7 from '$lib/images/hof/hof7.webp';
	import Hof8 from '$lib/images/hof/hof8.webp';
	import Dailymail from '$lib/images/dailymail.gif';
	import Testim from '$lib/images/testim.gif';
</script>

<div class="pt-8">
	<div class="sect-1 grid gap-y-8">
		<p class="text-2xl text-center font-semibold">
			For 6, 7 & 8-figure businesses who want to grow their online influence
		</p>
		<h1 class="text-center">
			Want to dominate <b class="font-extrabold">page #1 of Google</b> with <br />
			<b class="font-extrabold">high-quality press</b> about you <br />
			and your business in 6 weeks?
		</h1>
		<p class="text-2xl text-center">
			We're part of the 1% of PR agencies that can guarantee results or you don't pay.
		</p>
	</div>

	<div class="grid gap-y-8">
		<div class="sect-2 flex items-center justify-center mt-12">
			<video class="bg-gray-600" width="auto" controls>
				poster="https://upload.wikimedia.org/wikipedia/commons/e/e8/Elephants_Dream_s5_both.jpg">
				<source src="https://archive.org/download/ElephantsDream/ed_hd.ogv" type="video/ogg" />
				<source src="https://archive.org/download/ElephantsDream/ed_hd.avi" type="video/avi" />
				<source
					src="https://archive.org/download/ElephantsDream/ed_1024_512kb.mp4"
					type="video/mp4"
				/>
				<track kind="captions" src="" srclang="en" label="English" />
				Your browser does not support the video tag.
			</video>
		</div>
		<a href="/" class="book-call">BOOK 7MIN INTRO CALL</a>
	</div>

	<h1 class="py-10 text-center">Some of our <b>past clients...</b></h1>

	<Tesimonial />

	<div class="offer grid gap-y-8 mx-auto">
		<h1 class="text-center pt-14">This offer is <b>not for you if...</b></h1>
		<ul class="list-disc mx-auto w-[70%]">
			<li>You don't run your own business</li>
			<li>You're making less than 6-figures a year ‍</li>
			<li>You're happy being a ghost on the internet</li>
		</ul>

		<h1 class="text-center">Who is this <b>offer for?</b></h1>

		<ul class="list-disc mx-auto w-[70%] grid gap-y-4">
			<li>
				If you want influence, authority, and make more money in your industry, this offer is for
				you.
			</li>
			<li>I'm not going to write some fancy copy on this landing page.</li>
			<li>
				If you're reading this, it's because you've seen my social media, someone referred you to me
				or maybe you saw an AD.
			</li>
			<li>
				Truth is, I'm one of the fastest growing PR figures on the internet. And I don't say that to
				brag, I'll just show you the results I get.
			</li>
		</ul>
	</div>

	<div class="sect-3 grid sm:grid-cols-2 items-center gap-x-10 gap-y-20 mt-20">
		<img src={Hof1} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof2} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof3} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof4} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof5} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof6} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof7} alt="Blog 1" class="w-[70%] h-full mx-auto" />
		<img src={Hof8} alt="Blog 1" class="w-[70%] h-full mx-auto" />
	</div>

	<div class="sect-4 py-14 grid gap-y-10">
		<h1 class="text-center">Guaranteed or <b>you don't pay...</b></h1>
		<div class="grid gap-y-6">
			<p>
				Truth is, the main reason why I have a full-money back guarantee on this offer is because <span
					class="underline">I am selfish.</span
				>
			</p>
			<p>Let me explain...</p>
			<p>
				My goal is to become the #1 PR agency in the entire globe for business owners that relay on
				the internet to make money.
			</p>
			<p>
				Which means I can't deliver average results or offer cheap $97 articles anyone can find on
				fivver.
			</p>
			<p>It's not how I operate or run my business.</p>
			<p>100% of my business is based on results, and results only.</p>
		</div>
		<img src={Dailymail} alt="Daily mail" class="w-[80%] sm:w-[60%] h-full mx-auto" />
	</div>

	<div class="sect-5 grid gap-y-10">
		<h1 class="text-center">What are some of <b>the benefits?</b></h1>
		<ul class="list-disc mx-auto w-[70%] grid gap-y-4">
			<li>
				<b>Gain instant trust & credibility:</b> Turn 10s of thousands of cold leads into hot ones by
				leveraging the established trust of other major media companies.
			</li>
			<li>
				<b>Convert more sales:</b> Getting featured on the press gives you status. Those with status
				don't "hard" sell. It’s the difference between attraction and force. Status is power.
			</li>
			<li>
				<b>Build brand awareness:</b> Stay top-of-mind with customers, increase trust and loyalty, and
				ultimately drive more sales
			</li>
			<li>
				<b>Get into bigger opportunities:</b> We get you the social proof and leverage that catches the
				attention of other high-profile companies or individuals.
			</li>
		</ul>
	</div>

	<div class="sect-6 grid gap-y-8">
		<img src={Testim} alt="Daily mail" class="w-[60%] h-full mx-auto" />
		<a href="/" class="book-call">BOOK 7MIN INTRO CALL</a>
	</div>
</div>

<style lang="postcss">
	h1 {
		font-weight: 400;
		line-height: 115%;
		font-size: 32px;
		color: #005598;
	}

	p {
		line-height: 120%;
		letter-spacing: -0.05rem;
		color: rgba(0, 0, 0, 0.75);
	}

	.sect-2 {
		background-image: url($lib/images/hero-bg.webp);
		background-position: top;
		min-height: 450px;
		width: 100%;
	}

	video {
		max-width: 600px;
		width: 100%;
		height: auto;
	}

	.book-call {
		margin: 0 auto;
		border-radius: 14px;
		border-style: none;
		padding: 30px 80px;
		box-shadow: 0px 0px 10px 1px rgb(103, 103, 103);
		background: rgb(0, 154, 255);
		color: white;
		border-color: rgb(106, 89, 89);
		border-width: 0.5px;
		display: inline-flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		width: fit-content;
		font-weight: 600;
		transition: background 0.2s ease;
		font-size: 26px;
		letter-spacing: 0;
		line-height: 80%;
		font-family: 'Inter', sans-serif;
		font-weight: 700;
	}

	ul > li {
		font-size: 26px;
		color: rgba(0, 0, 0, 0.75);
		font-family: 'Inter', sans-serif;
		font-weight: 500;
		letter-spacing: -0.05rem;
		line-height: 150%;
	}

	li > b {
		color: rgb(0, 154, 255);
	}

	.sect-3 > img {
		box-shadow: 0px 0px 10px 1px rgb(103, 103, 103);
	}

	.sect-4 {
		margin: 0 auto;
		width: 70%;
	}

	.sect-4 > div > p {
		font-size: 24px;
	}

	@media screen and (max-width: 640px) {
		.sect-2 {
			min-height: 300px;
			background-position: center;
			/* background-size: cover; */
		}
		video {
			max-width: 400px;
		}

		.book-call {
			font-size: 18px;
			text-align: center;
			line-height: 120%;
			padding: 20px 60px;
		}
	}
</style>
