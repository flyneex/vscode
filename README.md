# vscode
// {
//     "editor.fontSize": 16,
//     "editor.wordWrap": "on",
//     "editor.fontLigatures": true,
//     "editor.fontVariations": true,
//     "editor.fontWeight": "normal",
//     "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
//     "diffEditor.ignoreTrimWhitespace": false,
//     "editor.minimap.enabled": false,
//     "editor.renderWhitespace": "none",
//     "workbench.activityBar.visible": false,
//     "workbench.iconTheme": "icons",
//     "workbench.colorTheme": "One Dark Pro Darker"

// }

{
	//Main editor settings
	"window.openFilesInNewWindow": "off",
	"editor.tabSize": 2,
	"editor.wordWrap": "bounded",
	"editor.wrappingIndent": "same",
	"editor.wordWrapColumn": 150,
	"editor.folding": false,
	"editor.insertSpaces": false,
	"editor.smoothScrolling": true,
	"editor.minimap.enabled": false,
	"editor.detectIndentation": true,
	"editor.suggestSelection": "first",
	//Определяет, будет ли редактор прокручиваться за пределы последней строки.
	"editor.scrollBeyondLastLine": true,
	"editor.multiCursorModifier": "ctrlCmd",
	//Определяет, должен ли редактор отображать управляющие символы.
	"editor.renderControlCharacters": false,
	//Управляет выделением символов, которые можно спутать с основными символами ASCII, кроме тех, которые являются общими для текущего пользовательского языкового стандарта.
	"editor.unicodeHighlight.ambiguousCharacters": false,
	"editor.quickSuggestionsDelay": 0,

	//Appearance
	"editor.cursorBlinking": "expand",
	"editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": false,
	"editor.scrollbar.horizontal": "hidden",
	"editor.scrollbar.vertical": "hidden",
	"workbench.colorCustomizations": {
		"editorOverviewRuler.errorForeground": "#0000",
		"editorOverviewRuler.warningForeground": "#0000",
		"editorOverviewRuler.infoForeground": "#0000"
	},
	"workbench.colorTheme": "Bearded Theme Black & Diamond",
	"workbench.iconTheme": "bearded-icons",
	"workbench.productIconTheme": "fluent-icons",
	"workbench.layoutControl.enabled": false,
	"editor.fontSize": 16,
	"editor.fontWeight": 400,
	"editor.lineHeight": 25,
	"editor.fontLigatures": true,
	// "editor.fontFamily": "Iosevka",
	// "editor.fontFamily": "IBM Plex Mono",
	// "editor.fontFamily": "Fira Code",
	// "editor.fontFamily": "Roboto Mono",
	// "editor.fontFamily": "Dank Mono",
	"editor.fontFamily": "MonoLisa Nerd Font Mono",
	// "editor.fontFamily": "JetBrains Mono, monospace",
	// "editor.fontFamily": "Maple Mono",
	"editor.inlayHints.fontFamily": "Pragmata Pro",
	"notebook.outputFontFamily": "Pragmata Pro",

	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
				"scope": [
					//following will be in italic (=FlottFlott)
					"comment",
					"entity.name.type.class", //class names
					"keyword", //import, export, return…
					"constant", //String, Number, Boolean…, this, super
					"storage.modifier", //static keyword
					"storage.type.class.js" //class keyword
				],
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"scope": [
					//following will be excluded from italics (VSCode has some defaults for italics)
					"invalid",
					"keyword.operator",
					"constant.numeric.css",
					"keyword.other.unit.px.css",
					"constant.numeric.decimal.js",
					"constant.numeric.json"
				],
				"settings": {
					"fontStyle": ""
				}
			}
		]
	},

	//Terminal
	"terminal.integrated.fontFamily": "monospace",
	"terminal.integrated.fontSize": 15,
	"terminal.integrated.tabs.enabled": false,

	//Explorer
	"explorer.confirmDelete": false,
	"explorer.compactFolders": false,
	"explorer.confirmDragAndDrop": false,

	//Emmet
	"emmet.triggerExpansionOnTab": true,
	"emmet.showExpandedAbbreviation": "never",
	//Разрешить уменьшение размера вкладок, когда доступного места недостаточно для отображения всех вкладок одновременно.
	"workbench.editor.tabSizing": "shrink",
	"workbench.startupEditor": "newUntitledFile",

	//Debug
	"debug.toolBarLocation": "hidden",
	"debug.focusWindowOnBreak": false,
	"debug.showInlineBreakpointCandidates": false,
	"debug.showBreakpointsInOverviewRuler": false,

	//Format
	"prettier.semi": false,
	"prettier.useTabs": true,
	"editor.formatOnSave": true,
	"prettier.singleQuote": true,
	"prettier.jsxSingleQuote": true,
	"editor.codeActionsOnSave": {
		"source.addMissingImports": "explicit",
		"source.organizeImports": "explicit"
	},
	//Включите круглые скобки вокруг единственного параметра функции стрелки
	"prettier.arrowParens": "avoid",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"eslint.packageManager": "yarn",
	"files.associations": { "*.scss": "postcss", "*.module.scss": "postcss" },
	"editor.inlineSuggest.enabled": true,
	"[html]": {
		"editor.defaultFormatter": "vscode.html-language-features"
	},

	//Laravel
	"emmet.includeLanguages": {
		"blade": "html"
	},
	"blade.format.enable": true,
	"files.defaultLanguage": "plaintext",
	"diffEditor.ignoreTrimWhitespace": false,
	"liveServer.settings.donotShowInfoMsg": true,
	"security.workspace.trust.untrustedFiles": "open",
	"html.completion.attributeDefaultValue": "singlequotes",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"[prisma]": {
		"editor.defaultFormatter": "Prisma.prisma"
	},

	//Breadcrumbs
	"breadcrumbs.icons": false,
	"breadcrumbs.showKeys": false,
	"breadcrumbs.showFiles": false,
	"breadcrumbs.symbolPath": "off",
	"breadcrumbs.showArrays": false,
	"breadcrumbs.showEvents": false,
	"breadcrumbs.showFields": false,
	"breadcrumbs.showClasses": false,
	"breadcrumbs.showMethods": false,
	"breadcrumbs.showBooleans": false,
	"breadcrumbs.showFunctions": false,
	"breadcrumbs.showConstants": false,
	"breadcrumbs.showEnumMembers": false,
	"breadcrumbs.showConstructors": false,

	//JS & TS
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"typescript.preferences.quoteStyle": "single",
	"javascript.preferences.quoteStyle": "single",
	"javascript.format.semicolons": "remove",
	"typescript.format.semicolons": "remove",
	"typescript.suggest.paths": false,
	"javascript.suggest.paths": false,

	//Spell checker
	"cSpell.language": "en,ru",
	"cSpell.userWords": [],
	"cSpell.enabled": true,
	"cSpell.enableFiletypes": [
		"blade",
		"jsx",
		"tsx",
		"ts",
		"js",
		"scss",
		"sass",
		"vue"
	],

	"editor.unicodeHighlight.allowedCharacters": {
		"а": true,
		"с": true,
		"Т": true,
		"б": true,
		"е": true
	},
	"editor.hideCursorInOverviewRuler": true,
	"git.enableSmartCommit": true,

	"files.exclude": {
		"**/.expo": true,
		"**/.expo-shared": true,
		"**/.idea": true,
		"**/.vscode": true,
		"**/.next": true
	},
	"[blade]": {
		"editor.defaultFormatter": "onecentlin.laravel-blade"
	},
	"[php]": {
		"editor.defaultFormatter": "kokororin.vscode-phpfmt"
	},
	"github.copilot.enable": {
		"*": true,
		"yaml": false,
		"plaintext": true,
		"markdown": false
	},
	"mock-server.settings.port": 4000,
	"workbench.activityBar.location": "top",
	"liveServer.settings.CustomBrowser": "chrome",
	"workbench.settings.applyToAllProfiles": [
		
	]
}
