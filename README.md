# Browser Homepage

Custom browser homepage inspired by https://github.com/GreatDanton/browser-homepage

It should work on modern browsers similar to the original, just set `index.html` as your homepage and customize to your own liking.

# Features

* Search
* Clock
* Calendar
* Countdown/Timer
* Todo List Built In
* Organizing links the way you want

The above listed features are included from the original hompeage created by GreatDanton

The features listed below are created by BaakaFate for his customization

* Brand new Theme
* Easier theme customization
* Theme Selector

# Adding links
Links should be added directly into `<div class="slides-container"` in index.html page. See below:

```html
<div class="slide" name="Reddit">
    <div class="part">
        <h1> Reddit </h1>

        <div class="links">
            <a href='https://www.reddit.com/r/unixporn/'> r/Unixporn </a>
            <a href='https://www.reddit.com/r/nosleep/'> r/Nosleep </a>
            <a href='https://www.reddit.com/r/homelab/'> r/HomeLab </a>
            <a href='https://www.reddit.com/r/sysadmin/'> r/SysAdmin </a>
            <a href='https://www.reddit.com/r/webdev/'> r/WebDev </a>
            <a href='https://www.reddit.com/r/devops/'> r/DevOps </a>
        </div>
    </div>
</div>
```