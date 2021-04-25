---
layout: default
title: Home
---

<h1><div style="">Cadmium</div><div style="display:none">Cadmiu</div><div style="display:none">Kadmiyu</div><div style="display:none">كادميوم</div><div style="display:none">Кадми</div><div style="display:none">Kadmio</div><div style="display:none">Кадмий</div><div style="display:none">कैडमियम</div><div style="display:none">ကတ်မီယမ်</div><div style="display:none">کادمیم</div><div style="display:none">Kaadmium</div><div style="display:none">Cadmio</div><div style="display:none">કેડમિયમ</div><div style="display:none">കാഡ്മിയം</div><div style="display:none">Κάδμιο</div><div style="display:none">Kadmín</div><div style="display:none">Cadmiwm</div><div style="display:none">Kadm</div><div style="display:none">Càdmiu</div><div style="display:none">კადმიუმი</div><div style="display:none">Kadmijum</div><div style="display:none">Kadmijs</div><div style="display:none">केडमियम्</div><div style="display:none">Cadimi</div><div style="display:none">鎘</div><div style="display:none">Caidmiam</div><div style="display:none">Kadmiumi</div><div style="display:none">Kadɩmɩyɔm</div><div style="display:none">カドミウム</div><div style="display:none">ཁེ་ཌི་ནིམ།</div><div style="display:none">Cadmi</div><div style="display:none">Kadmij</div><div style="display:none">Kadmium</div><div style="display:none">קדמיום</div><div style="display:none">Կադմիում</div><div style="display:none">Кадмій</div><div style="display:none">Cádmio</div><div style="display:none">Kadmii</div><div style="display:none">Kadmis</div><div style="display:none">카드뮴</div><div style="display:none">Кадм</div><div style="display:none">காட்மியம்</div></h1>
{: .name-rotate} 

{: .hide} Symbol
: {: .symbol} Cd

Atomic Number
: 48

Atomic Weight
: 112.411

Atomic Radius
: <span>151 pm</span>

Melting Point
: <span>594.22 K</span>

Boiling Point
: <span>1040 K</span>

Orbitals
: <span>\[Kr\] 4d<sup>10</sup> 5s<sup>2</sup></span>

Oxidation State
: +2
{: .card .elem}

<script>
	(function($) {
		$.fn.extend({
			rotaterator: function(options) {
				var defaults = {
					fadeSpeed: 5000,
					pauseSpeed: 5000,
					child:null
				};
				
				var options = $.extend(defaults, options);
				
				return this.each(function() {
					var o = options;
					var obj = $(this);                
					var items = $(obj.children(), obj);
					items.each(function() {
						$(this).hide();
					});
					if (!o.child) {
						var next = $(obj).children(':first');
					}
					else{
						var next = o.child;
					}
					
					$(next).fadeIn(o.fadeSpeed, function() {
						$(next).delay(o.pauseSpeed).fadeOut(o.fadeSpeed, function() {
							var next = $(this).next();
							
							if (next.length == 0) {
								next = $(obj).children(':first');
							}
							$(obj).rotaterator({child : next, fadeSpeed : o.fadeSpeed, pauseSpeed : o.pauseSpeed});
						})
					});
				});
			}
		});
	})(jQuery);
	
	$(document).ready(function() {
		$('.name-rotate').rotaterator({fadeSpeed:500, pauseSpeed:100});
		$('.name-rotate').removeClass('hidden');
	});
</script>