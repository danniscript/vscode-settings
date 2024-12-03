## vscode settings

```json
{
	"window.title": "${rootName}",
	"window.commandCenter": false,

	"workbench.colorTheme": "Night Howl",
	"workbench.iconTheme": "r-sveltekit-icons",
	"workbench.tree.enableStickyScroll": false,
	"workbench.tree.indent": 16,

	"explorer.sortOrder": "filesFirst",
	"explorer.compactFolders": false,

	"breadcrumbs.enabled": false,

	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.colorDecorators": false,
	"editor.formatOnSave": true,
	"editor.stickyScroll.enabled": false,

	"files.exclude": {
		// ".svelte-kit/": true,
		// ".vscode/": true,
		// "node_modules/": true,
		// ".gitignore": true,
		// ".prettierrc": true,
		// "bun.lockb": true,
		// "eslint.config.js": true,
		// "package.json": true,
		// "postcss.config.js": true,
		// "README.md": true,
		// "svelte.config.js": true,
		// "tailwind.config.ts": true,
		// "tsconfig.json": true,
		// "vite.config.ts": true,
		// "vite.config.ts.timestamp-*": true,
		// "vite.config.js.timestamp-*": true,
	},

	"svelte.enable-ts-plugin": true,
	"svelte.plugin.svelte.runesLegacyModeCodeLens.enable": false,

	"cSpell.words": ["tailwindcss"]
}
```

## prettier

```json
{
	"semi": false,
	"useTabs": true,
	"quoteProps": "consistent",
	"singleQuote": true
}
```

## eslint

```json
{
	"rules": {
		"@typescript-eslint/no-unused-vars": "warn"
	}
}
```
