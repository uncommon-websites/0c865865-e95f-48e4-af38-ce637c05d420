<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2">Industry-leading latency performance</h2>
				<p class="text-xl text-muted font-light">Sub-second streaming at global scale</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1">About this comparison</strong>
				This comparison shows end-to-end latency performance for live video streaming at scale. Measurements represent typical latency experienced by viewers across global CDN infrastructure. nanocosmos achieves sub-second latency through proprietary MoQ (Media over QUIC) technology, enabling real-time interactive applications like live betting. Learn more in our <a href="#" class="underline">technical documentation</a>.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/30 p-8 font-mono text-xs">
			<!-- Chart Grid -->
			<div class="absolute inset-0 p-8 grid grid-rows-6 grid-cols-1">
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
			</div>
			
			<!-- Y Axis Label -->
			<div class="absolute left-2 top-1/2 -translate-y-1/2 -rotate-90 text-muted origin-center whitespace-nowrap">
				VIEWER ENGAGEMENT (%)
			</div>

			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted">
				LATENCY (SECONDS)
			</div>

			<!-- Top Left Legend -->
			<div class="absolute top-4 left-4 flex gap-4 text-[10px] text-muted">
				<span class="bg-gray-200 px-1 rounded text-foreground">iGaming Benchmark</span>
				<span>Interactive Streaming</span>
				<span>Global Scale</span>
			</div>

			<!-- Data Points -->
			
			<!-- nanocosmos (The Winner) -->
			<div class="absolute top-[12%] left-[15%] flex flex-col items-center group cursor-pointer z-10">
				<div class="flex items-center gap-2 mb-1">
					<span class="text-accent font-bold">NANOCOSMOS</span>
				</div>
				<div class="w-3 h-3 bg-accent rounded-full shadow-[0_0_0_4px_rgba(139,92,246,0.2)]"></div>
				<div class="mt-1 text-[10px] text-accent">95% / &lt;1s</div>
			</div>

			<!-- Wowza -->
			<div class="absolute top-[45%] left-[35%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">WOWZA</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">72% / 3-5s</div>
			</div>

			<!-- Agora -->
			<div class="absolute top-[35%] left-[25%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">AGORA</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">80% / 1-2s</div>
			</div>

			<!-- Traditional CDN -->
			<div class="absolute top-[65%] left-[55%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">TRADITIONAL CDN</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">55% / 8-12s</div>
			</div>

			<!-- HLS Standard -->
			<div class="absolute top-[75%] left-[70%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">HLS STANDARD</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">45% / 15-30s</div>
			</div>

			<!-- Bottom Right Legend -->
			<div class="absolute bottom-4 right-4 flex items-center gap-4 text-[10px]">
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-accent rounded-full"></div>
					<span class="text-accent font-bold">NANOCOSMOS</span>
				</div>
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-black rounded-full"></div>
					<span class="text-muted">COMPETITORS</span>
				</div>
			</div>
		</div>
	</div>
</section>
