---
title: 'gear.ts'
description: 'Explore my hardware and software setup. From a powerful computer with an i5-10400F, 16GB of RAM, RTX 3060, and more, to a Macbook Air M2 for work on the go. My favorite tools include NeoVIM, Tmux, iTerm, and Oh my zsh. I hosts my website and projects on Vercel. Discover my tech world!'
---

```ts
const hardware = {
	computers: [
		{
			name: 'Asus VivoBook 15',
			desc: 'My trusty workhorse. Handles ML model training, code, and the occasional binge-watch session like a champ.',
			tags: ['Laptop']
		}
	],
	monitors: [
		{
			name: 'Samsung 24" FHD Monitor',
			desc: 'Nothing fancy, but solid for dual-screen coding and debugging YOLO models without squinting.',
			tags: ['Monitor']
		}
	],
	audio: [
		{
			name: 'Boat Rockerz 255 Pro+',
			desc: 'My everyday wireless earphones – cheap, comfy, and good enough to keep me in the zone while coding.',
			tags: ['Earphones']
		}
	],
	extras: [
		{
			name: 'Logitech M235 Wireless Mouse',
			desc: 'Simple, reliable, and way better than the VivoBook’s trackpad. No regrets.',
			tags: ['Mouse']
		},
		{
			name: 'Seagate 1TB External HDD',
			desc: 'My backup lifesaver. Holds old projects, datasets, and random downloads I’ll probably never open again.',
			tags: ['Storage']
		}
	]
};

const software = [
	{
		name: 'VS Code',
		desc: 'My main coding hub. With all the right extensions, it feels like cheating (but in a good way).',
		tags: ['Editor']
	},
	{
		name: 'Jupyter Notebook',
		desc: 'My go-to for ML experiments – messy, but that’s how breakthroughs happen.',
		tags: ['ML']
	},
	{
		name: 'Obsidian',
		desc: 'Where I dump ideas, project notes, and random thoughts. My second brain.',
		tags: ['Notes']
	},
	{
		name: 'Oh My Zsh',
		desc: 'Makes my terminal look and feel cooler than it has any right to be.',
		tags: ['Terminal']
	}
];

const hosting = [
	{
		name: 'Vercel',
		desc: "The fastest way I deploy stuff. Push to GitHub, grab a coffee, and it’s live.",
		tags: ['Hosting']
	},
	{
		name: 'Render',
		desc: "Sometimes I need a cheap backend. Render gets the job done without crying for my wallet.",
		tags: ['Hosting']
	}
];
```
