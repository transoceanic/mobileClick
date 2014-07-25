mobileClick - jQuery plugin
===========

Remove click delay on you mobile and browser page

For use you need bind ***mobileclick*** event to jQuery element (standard)

	$('you-element-selector').bind('mobileclick', function() {
		alert('test me');
	})
	// or
	$(document).on('mobileclick', 'you-element-selector', function() {
		alert('test me');
	})

If you bind ***mobileclick*** to button html element this event triggered if between start touching and finish you don't leave button bound rectangle.

In case of other html element this event triggered if between start touching and finish you don't leave button bound rectangle and move finger no more than 20px on each side.

All open source code is licenced under the FreeBSD License
