just-another-slider
===================

Just Another jQuery Slider

Why do we need just another Slider ?
===================

I know, we already have to many of them out there.
But many of them are already to complicated with lots of features, not to easy to customize.
So this script is more of a starting point with basic functionality, easy to understand but capable to extend to a rich featured Slider-Plugin.

Options
===================

    $(document).ready(function(){

        // INIT Slider Plugin
        $("#simple_slider").justAnotherSlider({
            width: 520,             // Container-width
            height: 460,            // Container-height
            carousel: true,         // Optional: if true, slider will restart when reached last element
            goLeft: $('#go_left'),  // Button-Element to go left
            goRight: $('#go_right') // ... to go right
        });          
    }); 

HTML
===================

    <div id="go_left">&lAarr;</div>
    <div id="simple_slider">
    <ul>            
        <li><p>first Slide</p></li>
        <li><p>second Slide</p></li>
        <li><p>third Slide</p></li>
    </ul>
    </div>
    <div id="go_right">&rAarr;</div>