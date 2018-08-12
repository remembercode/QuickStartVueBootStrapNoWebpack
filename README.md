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
		  