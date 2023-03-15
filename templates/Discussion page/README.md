# Template:Discussion page
```html
{{Doc}}
<includeonly><onlyinclude>{{#ifeq:{{FULLPAGENAME}}|Template:Discussion page||{{DISPLAYTITLE:<span style=display:none>{{{title|{{#ifeq:{{NAMESPACE}}|User talk|{{autolang|User talk:|zh=用户谈话:}}{{{user|{{PAGENAME}}}}}|{{FULLPAGENAME}}}}}}}</span>|noerror}}}}<!--
--><div style="display:flex; flex-direction:column; gap:12px; width:100%; background-color:{{{bg|#262626}}}; position:relative; z-index:80; margin-top:{{#ifeq:{{FULLPAGENAME}}|Template:Discussion page|0|calc(-27px - {{{up|{{#ifeq:{{ROOTPAGENAME}}|{{SUBPAGENAME}}|0|20}}}}}px)}}; margin-bottom:{{#ifeq:{{FULLPAGENAME}}|Template:Discussion page|0|26px}}">
	<div style="display:flex; {{Dir|rtl=flex-direction:row-reverse;}} align-items:center; gap:14px;">
		<div style="display:flex; align-items:center; justify-content:center; user-select:none; pointer-events:none; min-width:68px; min-height:68px; border-radius:16px; background-color:rgba(255,255,255,.15)">[[File:Icon-message-48px.png|link=]]</div>
		<div {{Dir|rtl=align="right"}}>
			<div style="line-height:1.2em; color:#FFF; font-size:30px">'''{{autolang|Welcome to {{FULLPAGENAME}}!|zh=欢迎来到 {{FULLPAGENAME}}！|ru=Добро пожаловать на страницу {{FULLPAGENAME}}!}}'''</div>
			<div style="font-size:14px">{{{description|{{autolang|This is the start of the {{PAGENAME}} discussion page.|zh=这是 {{PAGENAME}} 讨论页的开始。|ru=Это начало страницы обсуждения {{PAGENAME}}.}}}}}</div>
		</div>
	</div>
	<div style="display:flex; font-size:14px; gap:8px; {{Dir|rtl=flex-direction:row-reverse;}}"><!--
		-->[[Help:Discussion|<font style="display:flex; align-items:center; user-select:none; padding:6px 8px; border-radius:4px; background:rgba(255,255,255,.04); color:lightgrey">{{autolang|Documentation|zh=文档|ru=Справочник}}</font>]] <!--
		--><span class="plainlinks">[{{fullurl:{{FULLPAGENAME}}|action=edit&section=new}} <font style="display:flex; align-items:center; user-select:none; padding:6px 8px; border-radius:4px; background:rgba(255,255,255,.04); color:lightgrey">{{autolang|Add Topic|zh=添加新话题|ru=Добавить тему}}</font>]</span>
	</div>
</div></onlyinclude></includeonly>
```