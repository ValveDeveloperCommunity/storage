# Template:Code
```html
{{Doc}}
<onlyinclude><includeonly><!--
-->{{#switch:{{{style}}}
	|#default=<code style="background: {{{bg|{{{background|rgb(0,0,0,.35)}}}}}}; border-radius: 4px; color: {{{color|currentcolor}}}; padding: 2px 3px; user-select:{{#switch:{{{select}}}|#default=text|1=all|2=none}}">{{{1|}}}</code>
	|1=<code style="background-color: rgba(0,0,0,.16); border: 1px solid rgba(255,255,255,.1); border-radius: 4px; padding: 1px 3px; user-select:{{#switch:{{{select}}}|#default=text|1=all|2=none}}">{{{1|}}}</code>
	|2=<code style="background-color: rgb(0,0,0,.16); border-radius: 4px; padding: 2px 3px; user-select:{{#switch:{{{select}}}|#default=text|1=all|2=none}}">{{{1|}}}</code>
	|3=<kbd style="color:{{{color|currentcolor}}}; user-select:{{#switch:{{{select}}}|#default=text|1=all|2=none}}">{{{1|}}}</kbd>
}}</includeonly></onlyinclude>
```