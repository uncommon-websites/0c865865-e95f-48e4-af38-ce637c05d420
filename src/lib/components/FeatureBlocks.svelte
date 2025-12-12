<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: nanoStream Cloud Platform -->
<FeatureBlock 
	title="nanoStream Cloud Platform" 
	description="Complete live streaming solution with ultra-low latency, global CDN, and professional APIs for rapid deployment."
	buttons={[
		{ text: "START FREE TRIAL", icon: true },
		{ text: "VIEW DOCUMENTATION" }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 font-mono text-xs">
		<div class="flex items-center gap-2 border-b border-border pb-2 mb-4">
			<span class="text-accent">●</span>
			<span class="text-muted">nanoStream Cloud</span>
			<span class="ml-auto text-green-500 text-[10px]">LIVE</span>
		</div>
		<div class="space-y-3">
			<div class="flex items-center gap-2">
				<div class="w-2 h-2 bg-primary-500 rounded-full"></div>
				<div class="h-2 bg-gray-100 w-3/4 rounded"></div>
			</div>
			<div class="flex items-center gap-2">
				<div class="w-2 h-2 bg-primary-500 rounded-full"></div>
				<div class="h-2 bg-gray-100 w-1/2 rounded"></div>
			</div>
			<div class="flex items-center gap-2">
				<div class="w-2 h-2 bg-primary-500 rounded-full"></div>
				<div class="h-2 bg-gray-100 w-5/6 rounded"></div>
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Ultra-Low Latency Streaming -->
<FeatureBlock 
	title="Ultra-Low Latency Streaming" 
	description="Proprietary MoQ technology delivers sub-second latency at scale, perfect for interactive applications and live betting."
	buttons={[
		{ text: "TEST LATENCY", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full max-w-md bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center gap-2 text-xs font-mono text-muted">
			<div class="w-4 h-4 border border-primary-500 rounded-sm flex items-center justify-center">
				<div class="w-2 h-2 bg-primary-500 rounded-[1px] animate-pulse"></div>
			</div>
			Streaming live...
		</div>
		<div class="w-full bg-gray-100 h-1.5 rounded-full overflow-hidden">
			<div class="bg-primary-600 h-full w-full"></div>
		</div>
		<div class="flex gap-1">
			{#each Array(20) as _, i}
				<div class="w-1 h-3 {i % 2 === 0 ? 'bg-primary-400' : 'bg-primary-300'}"></div>
			{/each}
		</div>
		<div class="mt-2 flex items-center gap-2 text-[10px] text-primary-600 font-mono uppercase">
			<span class="w-3 h-3 border border-current rounded-full flex items-center justify-center text-[8px]">⚡</span>
			LATENCY: &lt;1 SECOND
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Global CDN Infrastructure -->
<FeatureBlock 
	title="Global CDN Infrastructure" 
	description="1,000+ servers worldwide with 24/7 monitoring ensure consistent performance across all continents for your viewers."
	buttons={[
		{ text: "VIEW NETWORK MAP", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-4 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>REGION</div>
			<div>SERVERS</div>
			<div>STATUS</div>
			<div>LATENCY</div>
		</div>
		{#each [
			{ region: 'North America', servers: '250+', status: 'Operational', latency: '< 1s' },
			{ region: 'Europe', servers: '300+', status: 'Operational', latency: '< 1s' },
			{ region: 'Asia Pacific', servers: '280+', status: 'Operational', latency: '< 1s' },
			{ region: 'South America', servers: '80+', status: 'Operational', latency: '< 1s' },
			{ region: 'Middle East', servers: '60+', status: 'Operational', latency: '< 1s' },
			{ region: 'Africa', servers: '30+', status: 'Operational', latency: '< 1s' }
		] as row}
			<div class="grid grid-cols-4 gap-2 p-2 border-b border-border/50 items-center">
				<div class="text-foreground">{row.region}</div>
				<div class="text-muted">{row.servers}</div>
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 rounded-full bg-green-500"></div>
					<span class="text-green-600">{row.status}</span>
				</div>
				<div class="text-primary-600">{row.latency}</div>
			</div>
		{/each}
	</div>
</FeatureBlock>

<!-- Block 4: Analytics & Monitoring -->
<FeatureBlock 
	title="Analytics & Monitoring" 
	description="Complete visibility into your streaming performance with real-time metrics, custom alerts, and comprehensive analytics dashboard."
	buttons={[
		{ text: "VIEW ANALYTICS", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-4 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>METRIC</div>
			<div>CURRENT</div>
			<div>AVG</div>
			<div>STATUS</div>
		</div>
		{#each [
			{ metric: 'Viewers', current: '45.2K', avg: '38.1K', status: 'up' },
			{ metric: 'Latency', current: '0.8s', avg: '0.9s', status: 'up' },
			{ metric: 'Bitrate', current: '4.2 Mbps', avg: '4.0 Mbps', status: 'stable' },
			{ metric: 'Buffer Rate', current: '0.2%', avg: '0.3%', status: 'up' },
			{ metric: 'Uptime', current: '99.98%', avg: '99.95%', status: 'up' },
			{ metric: 'CDN Load', current: '67%', avg: '72%', status: 'stable' }
		] as row}
			<div class="grid grid-cols-4 gap-2 p-2 border-b border-border/50 items-center">
				<div class="text-foreground">{row.metric}</div>
				<div class="text-primary-600 font-semibold">{row.current}</div>
				<div class="text-muted">{row.avg}</div>
				<div class="flex items-center gap-1">
					{#if row.status === 'up'}
						<span class="text-green-600">↑</span>
					{:else}
						<span class="text-gray-400">→</span>
					{/if}
				</div>
			</div>
		{/each}
	</div>
</FeatureBlock>

<!-- Block 5: AI-Powered Live Captions -->
<FeatureBlock 
	title="AI-Powered Live Captions" 
	description="Real-time captioning with AI technology for accessibility and enhanced viewer engagement across all your live streams."
	buttons={[
		{ text: "ENABLE CAPTIONS", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-2">
			<div class="text-[10px] font-mono text-muted flex items-center gap-2">
				<span class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></span>
				Live Captions Active
			</div>
			<div class="text-[10px] text-muted">EN</div>
		</div>
		
		<!-- Caption waveform visualization -->
		<div class="grid grid-cols-12 gap-1">
			{#each Array(48) as _, i}
				<div class="aspect-square rounded-[1px] {i > 36 && i < 44 ? 'bg-primary-500' : (i > 30 && i < 48 ? 'bg-primary-200' : 'bg-gray-50')}"></div>
			{/each}
		</div>

		<div class="mt-auto space-y-2">
			<div class="flex items-center gap-2 text-[10px] text-muted font-mono">
				<span class="w-3 h-3 border border-primary-500 rounded-full flex items-center justify-center text-[8px]">CC</span>
				Real-time transcription
			</div>
			<div class="bg-gray-50 p-2 rounded border border-border">
				<div class="space-y-1">
					<div class="h-1.5 w-full bg-gray-200 rounded"></div>
					<div class="h-1.5 w-3/4 bg-gray-200 rounded"></div>
					<div class="h-1.5 w-5/6 bg-primary-200 rounded animate-pulse"></div>
				</div>
			</div>
		</div>
	</div>
</FeatureBlock>
