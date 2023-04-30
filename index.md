---
layout: info
title: Home
---

<h1 class="name-rotate">
<div style="">Cadmium</div>
<div style="display:none" name="qu">Kadmiyu</div>
<div style="display:none" name="ar">كَادْمِيُوم</div>
<div style="display:none" name="cy">Cadmiwm</div>
<div style="display:none" name="ru">Кадмий</div>
<div style="display:none" name="sa">कैडमियम</div>
<div style="display:none" name="my">ကတ်မီယမ်</div>
<div style="display:none" name="et">Kaadmium</div>
<div style="display:none" name="es">Cadmio</div>
<div style="display:none" name="gu">કેડમિયમ</div>
<div style="display:none" name="ml">കാഡ്മിയം</div>
<div style="display:none" name="el">Κάδμιο</div>
<div style="display:none" name="is">Kadmín</div>
<div style="display:none" name="pl">Kadm</div>
<div style="display:none" name="ka">კადმიუმი</div>
<div style="display:none" name="lt">Kadmis</div>
<div style="display:none" name="vi">Cađimi</div>
<div style="display:none" name="zh">鎘</div>
<div style="display:none" name="ga">Caidmiam</div>
<div style="display:none" name="sq">Kadmiumi</div>
<div style="display:none" name="ja">カドミウム</div>
<div style="display:none" name="bo">ཁེ་ཌི་ནིམ།</div>
<div style="display:none" name="he">קדמיום</div>
<div style="display:none" name="de">Kadmium</div>
<div style="display:none" name="hy">Կադմիում</div>
<div style="display:none" name="ta">காட்மியம்</div>
<div style="display:none" name="ko">카드뮴</div>
<div style="display:none" name="uk">Кадмій</div>
</h1>

<aside>
	<h2>Cd</h2>
	
	<dl>
		<dt>Atomic Number</dt>
		<dd>48</dd>
		<dt>Atomic Weight</dt>
		<dd>112.411</dd>
		<dt>Atomic Radius</dt>
		<dd>151 pm</dd>
		<dt>Melting Point</dt>
		<dd>594.22 K</dd>
		<dt>Boiling Point</dt>
		<dd>1040 K</dd>
		<dt>Orbitals</dt>
		<dd>[Kr] 4d<sup>10</sup> 5s<sup>2</sup></dd>
		<dt>Oxidation State</dt>
		<dd>+2</dd>
	</dl>
</aside>

<div>
<p>Dieses Element ist ein silbriges Metall mit einer Dichte von 8,65 g/cm<sup>3</sup>. Es ist weich, schneidbar, verformbar, und duktil. Es ist beständig gegen Korrosion und unlöslich in Wasser. Als ein Kristall, es erstarrt in der hexagonal dichteste Kugelpackung.</p>

<p>Chemisch gleicht es dem Zink. Im Sauerstoff bildet es eine Verdunklung der Oberfläche. Im Kohlenstoffdioxid bildet es einen grauweißen Überzug. Es ist äußerst toxisch.</p>

<p>Acht Isotopen kommen in der Natur vor. Drei Isotopen sind stabil, <sup class="at-weight">110</sup>Cd, <sup class="at-weight">111</sup>Cd, und <sup class="at-weight">112</sup>Cd. Zwei sind radioaktiv, <sup class="at-weight">113</sup>Cd und <sup class="at-weight">116</sup>Cd. Drei können radioaktiv sein, <sup class="at-weight">106</sup>Cd, <sup class="at-weight">108</sup>Cd, und <sup class="at-weight">114</sup>Cd, aber die Halbwertszeiten wurden nicht bestimmt. Es sind acht Kernisomere bekannt; das stabilste ist <sup class="at-weight">113m</sup>Cd mit einer Halbwertszeit von 14,1 Jahren.</p>
</div>

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
