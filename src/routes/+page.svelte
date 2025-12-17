<script lang="ts">
	import { onMount } from 'svelte';

	let scrollY = 0;
</script>

<svelte:head>
	<title>Alrdy - Transform Your B2B SaaS Website in 5 Days</title>
	<meta name="description" content="Strategic design frameworks and rapid implementation for pre-Series B SaaS startups. Professional websites delivered in 5 days. No agency bloat, no endless timelines." />
	<meta property="og:title" content="Alrdy - Transform Your B2B SaaS Website in 5 Days" />
	<meta property="og:description" content="Strategic design frameworks and rapid implementation for pre-Series B SaaS startups. Professional websites delivered in 5 days." />
	<meta property="og:type" content="website" />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content="Alrdy - Transform Your B2B SaaS Website in 5 Days" />
	<meta name="twitter:description" content="Strategic design frameworks and rapid implementation for pre-Series B SaaS startups." />
</svelte:head>

<svelte:window bind:scrollY />

<div class="font-sans text-gray-900 antialiased selection:bg-primary-200 selection:text-primary-900">

	<!-- Hero Section -->
	<section class="relative min-h-screen w-full bg-gradient-to-b from-gray-950 via-gray-900 to-white text-white px-6 md:px-12 lg:px-24 pt-32 pb-24 flex flex-col justify-between">
		<div class="max-w-5xl">
			<div class="mb-8">
				<svg class="w-16 h-16 md:w-20 md:h-20 text-primary-400" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M5.0473 17.8386L5.69453 18.9586V18.9601H18.3003L18.9314 17.84H6.34063L6.82626 16.9993H19.4308L20.078 15.8807H7.47237L7.95715 15.0414H16.0358L16.0366 15.0429L16.0375 15.0414H20.5603L20.5612 15.0429L21.2084 13.9228L21.208 13.922L21.2084 13.9213H21.2075L14.9084 3.00677L14.9106 3.00296L14.9062 3.00296L13.6177 3.00296L5.0473 17.8386ZM14.261 4.12767L13.7751 4.96887L18.9438 13.9213H19.9139L14.261 4.12767ZM13.1286 6.08808L12.6467 6.9225L16.6749 13.9006L16.6634 13.9213H17.6511L13.1286 6.08808ZM11.9999 8.04225L8.60411 13.9213H15.3899L11.9999 8.04225ZM6.99833 3.30006C7.33866 3.10343 7.7248 2.99993 8.11786 3L2.30033 13.0776C2.10357 12.7371 2 12.3508 2 11.9575C2 11.5643 2.10357 11.178 2.30033 10.8375L6.17916 4.12006C6.37543 3.77951 6.65798 3.49669 6.99833 3.30006ZM9.08869 3H10.3816L3.43223 15.0384L2.785 13.9184L9.08869 3ZM11.3509 3H12.6424L4.56262 16.9963L3.91691 15.8777L11.3509 3ZM21.7064 13.0598C21.8988 12.7254 22 12.3463 22 11.9605C22 11.5746 21.8988 11.1956 21.7064 10.8611L17.8039 4.10233C17.6108 3.7681 17.3331 3.49057 16.9987 3.2976C16.6644 3.10463 16.2852 3.00302 15.8992 3.00296H15.8741L21.6931 13.082L21.7064 13.0598ZM17.7995 19.7994H6.17916C6.37472 20.1412 6.65692 20.4253 6.99728 20.6232C7.33763 20.8212 7.72414 20.9258 8.11786 20.9269H15.8829C16.2737 20.9261 16.6572 20.8212 16.994 20.6231C17.3309 20.4249 17.6089 20.1406 17.7995 19.7994Z"
						fill="currentColor"
					/>
				</svg>
			</div>
			<h1 class="font-serif text-5xl md:text-7xl lg:text-8xl leading-[1.1] md:leading-[1.1] tracking-tight">
				Transform your B2B SaaS website into a conversion engine. <span class="text-primary-400">In just 5 days.</span>
			</h1>
			<p class="text-xl md:text-2xl text-gray-300 mt-8 max-w-3xl">
				Strategic design frameworks and rapid implementation for pre-Series B startups. No agency bloat, no endless timelines.
			</p>
		</div>

		<div class="mt-24">
			<a href="#work" class="inline-flex items-center justify-center px-6 py-3 bg-primary-500 hover:bg-primary-600 text-white rounded-full text-sm font-medium transition-colors duration-300">
				See our work
			</a>
		</div>
	</section>

	<!-- Trusted Clients -->
	<section class="bg-white px-6 md:px-12 lg:px-24 py-16 md:py-24">
		<p class="text-lg md:text-xl text-gray-600 mb-12">Trusted by ambitious B2B SaaS startups</p>
		
		<div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-8 gap-4 md:gap-8">
			<!-- Client logos -->
			{#each ['Compa', 'Banxware', 'Openhealth', 'Oaks', 'Re:ports', 'Real PACE', 'Zepta', 'Kaiko'] as client}
				<div class="h-20 bg-white border border-gray-200 rounded-lg flex items-center justify-center grayscale opacity-70 hover:opacity-100 hover:grayscale-0 transition-all duration-300">
					<span class="font-semibold text-gray-800 text-sm">{client}</span>
				</div>
			{/each}
		</div>
	</section>

    <!-- Work Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24" id="work">
        <div class="flex flex-col md:flex-row justify-between items-end mb-16 md:mb-24">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900">Recent projects</h2>
        </div>

        <div class="space-y-24 md:space-y-32">
            <!-- Project 1: Compa -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Compa</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        A compensation data platform helping companies make fair pay decisions. We transformed their website to clearly communicate value to enterprise buyers.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Homepage</span>
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">5-Day Delivery</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-professional-website-design-mockup-on-la-1765978200633-1.webp" alt="Compa website" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 2: Banxware -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Banxware</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        A fintech platform providing flexible financing for SMEs. We created a conversion-focused website that builds trust with financial decision-makers.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Homepage</span>
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Brand Foundation</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-clean-modern-b2b-fintech-website-interfa-1765978205569-2.webp" alt="Banxware website" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 3: Openhealth -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Openhealth Technologies</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Healthcare technology platform streamlining medical data. We designed a professional website that communicates complex solutions with clarity.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Homepage</span>
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Copywriting</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-healthcare-technology-dashboard-on-compu-1765978211084-3.webp" alt="Openhealth website" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 4: Oaks -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Oaks</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Enterprise software for modern teams. We built a sleek, conversion-optimized website that positions them as industry leaders.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Homepage</span>
                        <span class="px-3 py-1 bg-primary-50 border border-primary-200 rounded-full text-xs font-medium text-primary-700">Brand Foundation</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-sleek-b2b-software-platform-website-on-l-1765978215173-4.webp" alt="Oaks website" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="bg-white px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900 mb-4 max-w-3xl">How we work</h2>
        <p class="text-xl text-gray-600 mb-16 max-w-2xl">12+ years of startup experience, condensed into a perfected 5-day delivery system.</p>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Strategy -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"></path>
                    </svg>
                </div>
                <h3 class="text-2xl font-semibold mb-4">Strategy First</h3>
                <p class="text-gray-600 leading-relaxed mb-auto">
                    We start with your ICP and positioning. No design without strategy. Our SaaS-specific frameworks ensure your message resonates with B2B buyers.
                </p>
            </div>

            <!-- Design -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01"></path>
                    </svg>
                </div>
                <h3 class="text-2xl font-semibold mb-4">Rapid Design</h3>
                <p class="text-gray-600 leading-relaxed mb-auto">
                    Figma designs delivered in days, not weeks. Our proven workflow eliminates back-and-forth while maintaining quality. One revision cycle keeps momentum.
                </p>
            </div>

            <!-- Deliver -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                    </svg>
                </div>
                <h3 class="text-2xl font-semibold mb-4">Ship Fast</h3>
                <p class="text-gray-600 leading-relaxed mb-auto">
                    Built in Webflow with client-first framework. SEO-optimized, GDPR-compliant, easy to edit. You own everything—no strings attached.
                </p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <div class="flex flex-col md:flex-row justify-between items-end mb-12">
            <h2 class="font-serif text-3xl md:text-4xl text-gray-900">What founders say</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Testimonial 1 -->
            <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                <div class="flex items-center mb-6">
                    <img src="/generated/image-professional-headshot-of-confident-femal-1765978219163-5.webp" alt="Matthäus Kerres" class="w-16 h-16 rounded-full object-cover mr-4" />
                    <div>
                        <h4 class="font-semibold text-gray-900">Matthäus Kerres</h4>
                        <p class="text-sm text-gray-600">Founder, Compa</p>
                    </div>
                </div>
                <p class="text-gray-700 leading-relaxed italic">
                    "Alrdy is a game changer for early-stage companies. The speed and quality are unmatched. They understood our positioning immediately."
                </p>
            </div>

            <!-- Testimonial 2 -->
            <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                <div class="flex items-center mb-6">
                    <img src="/generated/image-professional-headshot-of-marketing-execu-1765978223036-6.webp" alt="Ulrike Grandi" class="w-16 h-16 rounded-full object-cover mr-4" />
                    <div>
                        <h4 class="font-semibold text-gray-900">Ulrike Grandi</h4>
                        <p class="text-sm text-gray-600">Head of Marketing, Banxware</p>
                    </div>
                </div>
                <p class="text-gray-700 leading-relaxed italic">
                    "Working with Marina and Ben was effortless. Their can-do attitude and strategic guidance made the whole process smooth and fast."
                </p>
            </div>

            <!-- Testimonial 3 -->
            <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                <div class="flex items-center mb-6">
                    <img src="/generated/image-professional-headshot-of-male-product-ma-1765978226239-7.webp" alt="Pedro Benites" class="w-16 h-16 rounded-full object-cover mr-4" />
                    <div>
                        <h4 class="font-semibold text-gray-900">Pedro Benites</h4>
                        <p class="text-sm text-gray-600">Product Manager, Openhealth</p>
                    </div>
                </div>
                <p class="text-gray-700 leading-relaxed italic">
                    "They translated our complex product into clear messaging. The website now actually converts. Minimal effort required from our side."
                </p>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="px-6 md:px-12 lg:px-24 py-12">
        <div class="bg-gradient-to-br from-gray-900 via-gray-800 to-primary-950 rounded-2xl p-8 md:p-16 lg:p-20 text-white">
            <h3 class="font-serif text-3xl md:text-4xl lg:text-5xl mb-4">Are you rdy?</h3>
            <p class="text-xl text-gray-300 mb-8 max-w-2xl">
                Transform your B2B SaaS website in 5 days. Fixed pricing, no surprises. Let's turn your outdated website into a conversion engine.
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4">
                <a href="mailto:hello@alrdy.de" class="inline-flex items-center justify-center bg-primary-500 hover:bg-primary-600 text-white px-8 py-4 rounded-lg text-base font-medium transition-colors">
                    Book a call with Marina
                </a>
                <a href="#work" class="inline-flex items-center justify-center bg-transparent border border-white/30 hover:bg-white hover:text-gray-900 text-white px-8 py-4 rounded-lg text-base font-medium transition-colors">
                    See our work
                </a>
            </div>
            
            <div class="mt-12 pt-8 border-t border-white/10">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-sm">
                    <div>
                        <p class="text-primary-300 font-medium mb-1">Brand Foundation</p>
                        <p class="text-2xl font-bold">€8,000</p>
                        <p class="text-gray-400 mt-1">2 days delivery</p>
                    </div>
                    <div>
                        <p class="text-primary-300 font-medium mb-1">Homepage</p>
                        <p class="text-2xl font-bold">€16,000</p>
                        <p class="text-gray-400 mt-1">5 days delivery</p>
                    </div>
                    <div>
                        <p class="text-primary-300 font-medium mb-1">Response Time</p>
                        <p class="text-2xl font-bold">24 hours</p>
                        <p class="text-gray-400 mt-1">Email guarantee</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="relative bg-white pt-24 pb-32 px-6 md:px-12 lg:px-24">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="font-serif text-3xl md:text-5xl text-gray-900 leading-tight mb-8">
                Built by founders, for founders
            </h2>
            <p class="text-xl text-gray-600 leading-relaxed mb-8">
                Marina and Ben Brühl bring 12+ years of startup experience. They've lived the pain points of early-stage companies firsthand—and built Alrdy to solve them.
            </p>
            <p class="text-lg text-gray-600 leading-relaxed">
                No long-term commitments. No hidden costs. No agency bloat. Just fast, professional websites that help B2B SaaS startups appear credible and convert visitors into customers.
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-950 text-gray-300 px-6 md:px-12 lg:px-24 pt-24 pb-12 relative overflow-hidden">
        <div class="relative z-10">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-16">
                <div class="col-span-1 md:col-span-2">
                    <svg class="w-12 h-12 text-primary-400 mb-6" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            fill-rule="evenodd"
                            clip-rule="evenodd"
                            d="M5.0473 17.8386L5.69453 18.9586V18.9601H18.3003L18.9314 17.84H6.34063L6.82626 16.9993H19.4308L20.078 15.8807H7.47237L7.95715 15.0414H16.0358L16.0366 15.0429L16.0375 15.0414H20.5603L20.5612 15.0429L21.2084 13.9228L21.208 13.922L21.2084 13.9213H21.2075L14.9084 3.00677L14.9106 3.00296L14.9062 3.00296L13.6177 3.00296L5.0473 17.8386ZM14.261 4.12767L13.7751 4.96887L18.9438 13.9213H19.9139L14.261 4.12767ZM13.1286 6.08808L12.6467 6.9225L16.6749 13.9006L16.6634 13.9213H17.6511L13.1286 6.08808ZM11.9999 8.04225L8.60411 13.9213H15.3899L11.9999 8.04225ZM6.99833 3.30006C7.33866 3.10343 7.7248 2.99993 8.11786 3L2.30033 13.0776C2.10357 12.7371 2 12.3508 2 11.9575C2 11.5643 2.10357 11.178 2.30033 10.8375L6.17916 4.12006C6.37543 3.77951 6.65798 3.49669 6.99833 3.30006ZM9.08869 3H10.3816L3.43223 15.0384L2.785 13.9184L9.08869 3ZM11.3509 3H12.6424L4.56262 16.9963L3.91691 15.8777L11.3509 3ZM21.7064 13.0598C21.8988 12.7254 22 12.3463 22 11.9605C22 11.5746 21.8988 11.1956 21.7064 10.8611L17.8039 4.10233C17.6108 3.7681 17.3331 3.49057 16.9987 3.2976C16.6644 3.10463 16.2852 3.00302 15.8992 3.00296H15.8741L21.6931 13.082L21.7064 13.0598ZM17.7995 19.7994H6.17916C6.37472 20.1412 6.65692 20.4253 6.99728 20.6232C7.33763 20.8212 7.72414 20.9258 8.11786 20.9269H15.8829C16.2737 20.9261 16.6572 20.8212 16.994 20.6231C17.3309 20.4249 17.6089 20.1406 17.7995 19.7994Z"
                            fill="currentColor"
                        />
                    </svg>
                    <h3 class="text-2xl font-semibold text-white mb-4">Let's build your website</h3>
                    <p class="text-gray-400 mb-6 max-w-md">
                        Ready to transform your B2B SaaS website? Book a call with Marina to discuss your project.
                    </p>
                    <a href="mailto:hello@alrdy.de" class="inline-flex items-center text-primary-400 hover:text-primary-300 transition-colors font-medium">
                        hello@alrdy.de <span class="ml-2">→</span>
                    </a>
                </div>
                
                <div class="space-y-4">
                    <h4 class="font-medium text-white">Germany</h4>
                    <div class="pt-4 text-sm space-y-1">
                        <p>Marina & Ben Brühl</p>
                        <p>Founders</p>
                        <p class="mt-4 text-gray-500">24-hour email response guarantee</p>
                    </div>
                </div>
            </div>

            <div class="flex flex-col md:flex-row justify-between items-center border-t border-gray-800 pt-8">
                <div class="mb-4 md:mb-0">
                    <p class="text-sm text-gray-500">© 2025 Alrdy. All rights reserved.</p>
                </div>
                
                <div class="flex gap-6 text-sm">
                    <a href="#" class="hover:text-white transition-colors">LinkedIn</a>
                    <a href="#" class="hover:text-white transition-colors">Privacy</a>
                    <a href="#" class="hover:text-white transition-colors">Terms</a>
                </div>
            </div>
        </div>
    </footer>
</div>

<style>
    /* Custom utility for vertical writing mode */
    .writing-vertical-rl {
        writing-mode: vertical-rl;
    }
</style>

