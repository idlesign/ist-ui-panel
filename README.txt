

NOTE: This Panel plugin version is somewhat outdated, if not to say unsupported.
      You might be interesting in a new version of this plugin.
      It can be found at https://github.com/idlesign/jquery-ui repository.
      To be more precise at https://github.com/idlesign/jquery-ui/blob/master/ui/jquery.ui.panel.js



==========

'Panel / Content Grouping' Draft for jQuery UI
(ist-ui-panel)

Grab documentation & latest source at 
http://github.com/idlesign/ist-ui-panel/

See demo.htm for usage examples.

Report bugs to
http://github.com/idlesign/ist-ui-panel/issues/

Source code is also available at jQuery UI Labs
http://code.google.com/p/jquery-ui/source/browse/#svn/branches/labs/panel

Read more about Panel widget concept at jQuery UI public wiki
http://jqueryui.pbworks.com/ContentGrouping

==========
Changelog:

0.6
	* changed: refactored to jQuery UI 1.8 (also removed 'disable' method now implemented in jquery.ui.widget.js)
	* fixed: issue #1 on github: panel state not restored from cookie data
	* fixed: issue #2 on github: unnecessary styling of destroyed panels
	* fixed: issue #3 on github: error on stackable panel destroy

0.5
	* changed: refactored to jQuery 1.4
	* changed: 'trueVerticalText' parameter now defaults to 'true'

0.4
	* new: 'width' option - if set panel's width will be adjusted according to given value
	* new: 'stackable' option - if true, special stack area (navigation window emulation) is automatically created for 'slide-left' & 'slide-right' collapseType panels only
	* new: advanced demo page 'demo.htm', old demo renamed into 'demo_simple.htm'
	* changed: improved destroy method
	* changed: improved title text positioning in vertical panels with 'trueVerticalText'
	* changed: source code reformatted (tabs converted to spaces)

0.3.6
	* fixed: issue #4 (true vertical text is not rendered in Opera - svg generation failed when font-family css property contained quotes)

0.3.5
	* fixed: 'pointer' cursor over panel title on non-collapsible panels (changed to 'default')

0.3.4.1
	* fixed: issue #3 (Panel state is not stored in a cookie)

0.3.4
	* new: 'disable' method (& 'disabled' option)

0.3.3
	* changed: 'collapsed' ident moved from tag attribute to .data

0.3.2
	* new: 'draggable' option (depends on jQuery UI Draggable)
	* fixed: vertical svg text now themeroller compliant
	* fixed: panel content top border removed

0.3.1
	* fixed: unfold by header click for 'trueVerticalText' sliding left/right panels (Firefox, Opera)
	* fixed: panel content wider than the header when unfolded( noticed with jQuery UI Dialog)

0.3
	* new: 'content' method
	* new: vertical text rendering implementation (experimental svg/filter) - 'trueVerticalText' option

0.2.3.1
	* fixed: issue #2 (no collapse button on 'slide-right' panel when controls element is undefined)

0.2.3
	* new: save panel state with cookie (depends on jQuery Cookie plugin)
	* new: accordion behavior
	* new: toggle method exposed

0.2.2
	* new: 'fold' and 'unfold' callback functions
	* new: on destroy: unbind actions that are bound to the panel
	* changed: _toggle() method modified

0.2.1
	* new: rounded corners added
	* changed: _toggle method rewritten (now supports initially collapsed mode for slide panel types)
	* changed: collapse button borders removed
	* fixed: css collapse controls style fix

0.2
	* new: destroy() method
	* fixed: some nested spans

0.1b 
	* Start here
