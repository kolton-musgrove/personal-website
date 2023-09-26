<script lang="ts">
	import { JumpLink, SocialMediaButtons } from '$lib/components';
</script>

<main class="mx-auto min-h-screen max-w-screen-xl px-6 py-12 font-sans md:px-12 md:py-20 lg:px-24 lg:py-0">
	<a
		href="#content"
		class="absolute left-0 top-0 block -translate-x-full rounded bg-gradient-to-br from-teal-400 via-blue-500 to-purple-600 px-4 py-3 text-sm font-bold uppercase tracking-widest text-white focus-visible:translate-x-0"
		>Skip to Content</a
	>
	<div class=" lg:flex lg:justify-between">
		<header class="lg:sticky lg:top-0 lg:flex lg:max-h-screen lg:w-1/2 lg:flex-col lg:justify-between lg:py-24">
			<div>
				<h1 class="text-4xl font-bold tracking-tight text-slate-200 sm:text-5xl">
					<a href="/">Kolton Musgrove</a>
				</h1>
				<h2 class="mt-3 text-lg font-medium tracking-tight text-slate-200 sm:text-xl">
					Site Reliability Engineer @ Polaris
				</h2>
				<p class="mt-4 max-w-xs leading-normal">I build reliable, scalable products and digital experiences for the web.</p>
				<nav class="nav hidden lg:block" aria-label="In-page jump links">
					<ul class="mt-16 w-max">
						<JumpLink href="#projects" description="Projects" />
						<JumpLink href="#about" description="About" />
						<JumpLink href="#experience" description="Experience" />
					</ul>
				</nav>
				<SocialMediaButtons />
			</div>
		</header>
	</div>
</main>
