# Template:Background
```html
{{Doc}}
<onlyinclude><includeonly><div style="width: calc(100% + 48px); height: calc(100% + 88px); background-color: {{{bgcolor|transparent}}}; opacity:{{{opacity|0.05}}}; overflow:hidden; pointer-events:none; user-select:none; position:absolute; z-index:-1; left:-24px; top:-64px"><!--
	--><div style="background: linear-gradient(180deg, rgb(38,38,38) 0%, rgba(38,38,38,0) 100%); width:100%; height:{{{gradient-height|150px}}}; position:absolute; z-index:1"></div><!--
	--><div style="width:100%; display:flex; justify-content:center; position:absolute; z-index:0"><!--
		-->{{{1|}}}<!--
-->		<div style="background:linear-gradient(0deg, rgb({{{gradient-color|38,38,38}}}) 0%, rgba({{{gradient-color|38,38,38}}},0) 100%); width:100%; height:{{{gradient-height|150px}}}; position:absolute; z-index:1; bottom:0.5em"></div><!--
	--></div>
</div></includeonly></onlyinclude>
```