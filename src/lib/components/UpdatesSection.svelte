<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4">Get started</p>
					<h2 class="text-2xl font-medium mb-4">Power your platform with sub-second streaming</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						nanocosmos delivers ultra-low latency live streaming at global scale, trusted by leading iGaming operators and streaming platforms worldwide.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							START FREE TRIAL
							<svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M1 11L11 1M11 1H3M11 1V9" stroke="currentColor" stroke-width="1.5"/>
							</svg>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							CONTACT SALES
							<svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M1 11L11 1M11 1H3M11 1V9" stroke="currentColor" stroke-width="1.5"/>
							</svg>
						</button>
					</div>
				</div>
				
				<!-- Network Visual -->
				<div class="mt-auto w-full h-48 bg-gradient-to-br from-primary-950 to-black relative overflow-hidden flex items-center justify-center">
					{#each Array(100) as _, i}
						<div 
							class="h-full bg-primary-500/20 absolute" 
							style="
								left: {i}%; 
								width: {Math.random() * 2}%; 
								opacity: {Math.random() * 0.5};
							"
						></div>
					{/each}
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-black/80 text-white font-mono text-[10px] px-3 py-1.5 z-10 border border-primary-500/30 rounded">
							nanocosmos.de
						</div>
					</div>
					<!-- Streaming indicators -->
					<div class="absolute top-4 left-4 flex items-center gap-2">
						<span class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></span>
						<span class="text-white/60 text-[8px] font-mono">1000+ SERVERS</span>
					</div>
					<div class="absolute bottom-4 right-4 flex items-center gap-2">
						<span class="text-primary-300 text-[8px] font-mono">&lt;1s LATENCY</span>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8">Latest updates</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">October 2025</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">nanoStream Live Captions v1 Released</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Introducing AI-powered real-time captioning for live streams. nanoStream Live Captions v1 provides automatic speech recognition and transcription with sub-second latency, enabling accessibility and enhanced viewer engagement across all streaming platforms. Supports multiple languages and seamless integration with existing nanoStream workflows.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Product Release</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">July 2023</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Wegner Live Partnership Announced</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								nanocosmos wins Swiss provider Wegner Live as client for live auction streaming services. The partnership brings ultra-low-latency streaming technology to the live auction industry, enabling real-time bidding experiences with sub-second delivery across Europe.
							</p>
							<div class="flex gap-2">
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Partnership</span>
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Client Win</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">February 2025</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">nanoStreamReady Partner Program Launch</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								nanocosmos introduces the nanoStreamReady Partner Program to build a network for reliable streaming solutions. The program enables technology partners, system integrators, and service providers to deliver certified ultra-low-latency streaming solutions to their customers worldwide.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Partner Program</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">2023</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">nanocosmos Celebrates 25 Years of Innovation</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Marking over two decades of innovation in video technology, nanocosmos celebrates its 25th anniversary. From pioneering video codec development to becoming a leader in interactive live streaming with proprietary MoQ technology, the company continues to push the boundaries of real-time video delivery.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Milestone</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
