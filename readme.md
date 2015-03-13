#bxsliderでループスライダー

http://bxslider.com/examples/ticker
を使って拡張。

幅固定を

    $(document).ready(function(){
    	$('.bxslider').bxSlider({
    	  minSlides: 4,
    	  maxSlides: 4,
    	  slideWidth: "auto",
    	  slideMargin: 10,
    	  ticker: true,
    	  speed: 6000
    	});
    });

とすることで、幅サイズを自動化 