# Bootstrap-navbar-fixed-on-scroll-sticky-top-
Make bootstrap navbar fixed on scroll (sticky top)
There are multiple ways to fix navbar or header on top of page to stay always visible. In this example we illustrate how to add fixed-top class when page scolled. To see the difference between normal and fixed top navigation menu, just scroll. Keep in mind, This will work only for desktop screens. But still you can customize our code example.

# Steps to make bootstrap nav fixed top after scroll
1. Create navbar on top of page
2. Check window screen size with javascript: if ($(window).width() > 992) { ... }
3. Now let's check if window scrolled $(window).scroll(function(){ ... }
4. Check if scrolled more than x amount of px if ($(this).scrollTop() > 40) { ... }
5. Add fixed-top class on navbar
6. When you make navbar's position fixed or absolute during scroll, other elements will shake. because they will take space of navbar.

There is more simple way also to do that, just add class name sticky-top to your navbar. But keep in mind, your navbar element must be direct child of body. If you wrap your navbar with some other div it will not work.
