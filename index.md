---
layout: default
title: Home
---

<h1>
<div style="">Cadmium</div>
<div style="display:none">Cadmiu</div>
<div style="display:none">Kadmiyu</div>
<div style="display:none">كادميوم</div>
<div style="display:none">Кадми</div>
<div style="display:none">Cadmiwm</div>
<div style="display:none">Кадмий</div>
<div style="display:none">कैडमियम</div>
<div style="display:none">ကတ်မီယမ်</div>
<div style="display:none">کادمیم</div>
<div style="display:none">Kaadmium</div>
<div style="display:none">Cadmio</div>
<div style="display:none">કેડમિયમ</div>
<div style="display:none">കാഡ്മിയം</div>
<div style="display:none">Κάδμιο</div>
<div style="display:none">Kadmín</div>
<div style="display:none">Kadm</div>
<div style="display:none">კადმიუმი</div>
<div style="display:none">Kadmij</div>
<div style="display:none">Kadmijs</div>
<div style="display:none">Cađimi</div>
<div style="display:none">鎘</div>
<div style="display:none">Caidmiam</div>
<div style="display:none">Kadmiumi</div>
<div style="display:none">カドミウム</div>
<div style="display:none">ཁེ་ཌི་ནིམ།</div>
<div style="display:none">Kadmij</div>
<div style="display:none">קדמיום</div>
<div style="display:none">Kadmium</div>
<div style="display:none">Կադմիում</div>
<div style="display:none">Кадмій</div>
<div style="display:none">காட்மியம்</div>
<div style="display:none">Kadmii</div>
<div style="display:none">Kadmis</div>
<div style="display:none">카드뮴</div>

</h1>
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

Dieses Element ist ein silbriges Metall mit einer Dichte von 8,65 g/cm<sup>3</sup>. Es ist weich, schneidbar, verformbar, und duktil. Es ist beständig gegen Korrosion und unlöslich in Wasser. Als ein Kristall, es erstarrt in der hexagonal dichteste Kugelpackung.

Chemisch gleicht es dem Zink. Im Sauerstoff bildet es eine Verdunklung der Oberfläche. Im Kohlenstoffdioxid bildet es einen grauweißen Überzug. Es ist äußerst toxisch.

Acht Isotopen kommen in der Natur vor. Drei Isotopen sind stabil, <sup class="at-weight">110</sup>Cd, <sup class="at-weight">111</sup>Cd, und <sup class="at-weight">112</sup>Cd. Zwei sind radioaktiv, <sup class="at-weight">113</sup>Cd und <sup class="at-weight">116</sup>Cd. Drei können radioaktiv sein, <sup class="at-weight">106</sup>Cd, <sup class="at-weight">108</sup>Cd, und <sup class="at-weight">114</sup>Cd, aber die Halbwertszeiten wurden nicht bestimmt. Es sind acht Kernisomere bekannt; das stabilste ist <sup class="at-weight">113m</sup>Cd mit einer Halbwertszeit von 14,1 Jahren.

<script>
	(function($) {
		$.fn.extend({
			rotaterator: function(options) {
				var defaults = {
					fadeSpeed: 500,
					pauseSpeed: 100,
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
		$('.name-rotate').rotaterator({fadeSpeed:500, pauseSpeed:1000});
		$('.name-rotate').removeClass('hidden');
	});
</script>