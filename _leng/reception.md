---
layout: wedding
lang: eng
order: 30
showfoodmenu: true
---

<div class="eng reception">
    <h1 class="head recp"> Reception </h1>
    <h3 class="head recp-time">7PM, 14th February, 2025, Friday</h3>
    <h3 class="head recp-loc">Trinayani Hotel & Banquet</h3>
    <h3 class="head recp-loc">StateHighway 6, Kalipur, Suri, Birbhum</h3>

    <div class="map-container">
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m17!1m11!1m3!1d542.9825471720449!2d87.51447853693026!3d23.90579518000148!2m2!1f0!2f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f75846cfaab1c5%3A0x7e44407e58d00763!2sTRINAYANI%20HOTEL%20%26%20BANQUET!5e1!3m2!1sen!2sin!4v1738954702104!5m2!1sen!2sin"
            allowfullscreen
            loading="lazy">
        </iframe>
    </div>
    <h3><a href="https://maps.app.goo.gl/Sme2MVXKQ4Hjevv3A">Open in map</a></h3>
    {% if page.showfoodmenu %}
    <br />
    <br />
    <!-- <h1> Menu </h1> -->
    <div class="foodmenu-image" id="foodmenu">
        <img src="{{ site.baseurl }}/assets/img/menu/Menu-1-eng/Slide1.jpeg" /> <br/>
        <img src="{{ site.baseurl }}/assets/img/menu/Menu-1-eng/Slide2.jpeg" /> <br/>
        <h3><a href="{{ site.baseurl }}/assets/img/menu/Menu-1-eng.pdf">Download PDF</a></h3>
    </div>
    {% endif %}
</div>