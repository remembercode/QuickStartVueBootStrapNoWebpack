# QuickStartVueBootStrapNoWebpack
Quick Start VUE2 &amp; BootStrap4 Without Webpack or Babel

# init

	npm install pnpm
	pnpm install

	edit node_modules\vue-devtools\vender\manifest.json

	from

	  "permissions": [
		"http://*/*",
		"https://*/*",
		"file:///*",
		"contextMenus"
	  ],

	to
	  
	  "permissions": [
		"http://*/*",
		"https://*/*",
		"file:///*",
		"contextMenus",
		"*://*/*"
	  ],

# run with nwjs

## notepad++ 

	path\to\nw.exe "$(CURRENT_DIRECTORY)" --load-extension="$(CURRENT_DIRECTORY)\node_modules\vue-devtools\vender"

## intellij idea & WebStorm

	NW.js app : this folder
	NW.js arguments : --load-extension="node_modules\vue-devtools\vender"
	Working directory : this folder
	NW.js interpreter : path\to\nw.exe
	  