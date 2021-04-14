---
layout: default
title: Home
---

Cadmium
: {: .at-number} 48
: {: .at-weight} 112.411
: {: .symbol} Cd
: {: .ground-state} <span><sup>1</sup>S<sub>0</sub></span>
: {: .density} 8.65 g/cm<sup>3</sup>
: {: .ionization} 8.9938
: {: .melting-point} 594.22 K
: {: .boiling-point} 1040 K
: {: .at-radius} 151 pm
: {: .crystal} hcp
: {: .configuration} <span>\[Kr\] 4d<sup>10</sup> 5s<sup>2</sup></span>
: {: .oxidation} +2
{: .element}

Cadmium
: Cadmiu
: Kadmiyu
: كادميوم
: Кадми
: Kadmio
: Кадмий
: कैडमियम
: ကတ်မီယမ်
: کادمیم
: Kaadmium
: Cadmio
: કેડમિયમ
: കാഡ്മിയം
: Κάδμιο
: Kadmín
: Cadmiwm
: Kadm
: Càdmiu
: კადმიუმი
: Kadmijum
: Kadmijs
: केडमियम्
: Cadimi
: 鎘
: Caidmiam
: Kadmiumi
: Kadɩmɩyɔm
: カドミウム
: ཁེ་ཌི་ནིམ།
: Cadmi
: Kadmij
: Kadmium
: קדמיום
: Կադմիում
: Кадмій
: Cádmio
: Kadmii
: Kadmis
: 카드뮴
: Кадм
: காட்மியம்
{: .name-rotate}

<script>(function($){
    $.fn.extend({ 
        rotaterator: function(options) {
 
            var defaults = {
                fadeSpeed: 1000,
                pauseSpeed: 0,
				child:null
            };
             
            var options = $.extend(defaults, options);
         
            return this.each(function() {
                  var o = options;
                  var obj = $(this);                
                  var items = $(obj.children(), obj);
				  items.each(function() {$(this).hide();})
				  if(!o.child){var next = $(obj).children(':first');
				  }else{var next = o.child;
				  }
				  $(next).fadeIn(o.fadeSpeed, function() {
						$(next).delay(o.pauseSpeed).fadeOut(o.fadeSpeed, function() {
							var next = $(this).next();
							if (next.length == 0){
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