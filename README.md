# gyanExchange

// writing jquery extensions and prowiding and defaults 

If you are writing extenstion and want to use some defaults use the $.extend
eg. 
$jqGallery = function(options){
	var defaults = {
		delay : 10
	}
	var opts = $.extend({},defaults,options);
	console.log(opts.delay)
}

//now if we init using $.jqGallery()
	the delay will be of 10
//if we init using $.jqGallery({ delay: 20 })
	the delay will be 20
	
