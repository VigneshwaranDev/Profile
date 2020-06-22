# Details
This single page has the sticky navigation bar and also the smooth scrolling to the section.

```javascript

$('.navbar a').on('click', function (e) {
    if (this.hash !== '') {
        e.preventDefault();

        const hash = this.hash;

        $('html, body').animate({
                scrollTop: $(hash).offset().top,
            },
            800
        );
    }
});

```

This above mentioned program helps to animate the scroll.

Happy Coding... !
