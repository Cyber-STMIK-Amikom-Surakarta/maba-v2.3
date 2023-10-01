<script lang="ts">
	import { Presentation, Slide, Layout, Vertical, Code } from '@components'

	import LogoCyber from './assets/logo.webp'
	import LogoDiscord from './assets/discord.webp'
	import LogoGithub from './assets/github.webp'
</script>

<Presentation>
	<Vertical>
		<Slide animate>
			<Layout>
				<img src={LogoCyber} alt="Logo Cyber" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={LogoCyber} alt="Logo Cyber" class="w-72" />
				<h1 class="text-[6rem] font-bold tracking-wide">
					Cyber Amikom Surakarta
				</h1>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide>
			<Layout>
				<h2 class="text-[10rem] font-bold tracking-widest">Perkenalan</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<img src={LogoDiscord} alt="Discord" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={LogoDiscord} alt="Discord" class="w-72" />
				<h2 class="text-[5rem] font-bold tracking-wide">Discord</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-[10rem] font-bold tracking-widest">Games</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-[10rem] font-bold tracking-widest leading-relaxed">
					Open Recruitment
				</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<h2 class="text-[5rem] font-bold leading-relaxed tracking-wide">
				Presentasi ini dibuat menggunakan kodingan
			</h2>
		</Slide>

		<Slide animate>
			<Code lang="svelte">
				{`
<Vertical>
	<Slide animate>
		<Layout>
			<img src={LogoCyber} alt="Logo Cyber" />
		</Layout>
	</Slide>

	<Slide animate>
		<Layout>
			<img src={LogoCyber} alt="Logo Cyber" class="w-72" />
			<h1 class="text-[6rem] font-bold tracking-wide">
				Cyber Amikom Surakarta
			</h1>
		</Layout>
	</Slide>
</Vertical>
				`}
			</Code>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={LogoGithub} alt="Github" class="w-72" />
				<h2 class="text-[5rem] font-bold leading-relaxed tracking-wide">
					Kodingan ada di github
				</h2>
				<a href="https://bit.ly/github-cyber" class="text-blue-500 underline"
					>https://bit.ly/github-cyber</a
				>
			</Layout>
		</Slide>
	</Vertical>
</Presentation>
