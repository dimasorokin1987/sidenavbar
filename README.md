usage:
```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dimasorokin1987/sidenavbar@v0.1.0/sidenavbar.css">
...
<input id="expand-collapse-menu-button" type="checkbox" />
<input id="show-hide-menu-button" type="checkbox" />
<header>
<label id="show-hide" class="menu-btn" for="show-hide-menu-button">
    <i class="fa fa-bars" aria-hidden="true"></i>
    <i class="fa fa-times" aria-hidden="true"></i>
</label>
<label id="expand-collapse" class="menu-btn" for="expand-collapse-menu-button">
    <i class="fa fa-arrow-right" aria-hidden="true"></i>
</label>
</header>
<nav>
<ul>
    <li><a href="#intro"><i class="fa fa-sticky-note-o"></i><span>intro</span></a></li>
    <li><a href="#projects"><i class="fa fa-tasks"></i><span>projects</span></a></li>
    <li><a href="#contacts"><i class="fa fa-address-book"></i><span>contacts</span></a></li>
    <li><a href="#about"><i class="fa fa-align-center"></i><span>about</span></a></li>
</ul>
</nav>
<main class="tablet-menu-shown">
<section id="intro">
    <h2>intro</h2>
</section>
<section id="projects">
    <h2>projects</h2>
</section>
<section id="contacts">
    <h2>contacts</h2>
</section>
<section id="about">
    <h2>about</h2>
</section>
</main>
```
