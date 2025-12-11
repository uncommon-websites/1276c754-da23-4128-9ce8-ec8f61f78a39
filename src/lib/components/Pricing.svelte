<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5" id="pricing">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-4">Pricing</h2>
		<p class="text-gray-400 text-lg mb-16">Start free, scale as you grow</p>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Growth -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Growth</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Contact us
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN STARTER +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced workflow automation</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom integrations</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Priority support & onboarding</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Analytics & reporting dashboard</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated account manager</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>API access</span>
					</li>
				</ul>
			</div>

			<!-- Starter -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Starter</h3>
				<p class="text-primary-400 text-sm mb-6">$49 / month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Start free trial
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">PERFECT FOR EARLY STAGE</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 10 team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited workflow captures</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Automated documentation</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic integrations (Slack, GitHub, Notion)</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Real-time collaboration</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Founder community access</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Email support</span>
					</li>
				</ul>
			</div>

			<!-- Free -->
			<div>
				<h3 class="text-xl font-bold mb-2">Free</h3>
				<p class="text-gray-400 text-sm mb-6">$0 forever</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Get started
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EXPLORE THE PLATFORM</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 3 team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>5 workflow captures per month</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic documentation generation</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>1 integration (Slack or GitHub)</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Community support</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Access to founder community</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-gray-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Help center resources</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
