---
navgroup: 'MainNav'
navTitle: Contact
order: 4

layout: website
title: Get In Touch

heroTitle: Get in Touch
heroImage: contact-hero.jpg
---

There are a variety of ways to get in contact with Collective Logic and we'd love to hear from you:

### By post or in person (by appointment only)

<address>
Collective Logic Ltd<br>
Campus North 5 Sunco House<br>
Carliol Square<br>
Newcastle upon Tyne<br>
United Kingdom, NE1 6UF
</address>

<div id="cl-map"></div>

<script>
    function initMap() {
        var collectivelogic = { lat: 54.972864, lng: -1.608659 };
        var map = new google.maps.Map(document.getElementById('cl-map'), {
            zoom: 17,
            center: collectivelogic,
            styles: [
            {elementType: 'geometry', stylers: [{color: '#0a363c'}]},
            {elementType: 'labels.text.stroke', stylers: [{color: '#000000'}]},
            {elementType: 'labels.text.fill', stylers: [{color: '#dc7840'}]},
            {
              featureType: 'administrative.locality',
              elementType: 'labels.text.fill',
              stylers: [{color: '#d59563'}]
            },
            {
              featureType: 'poi',
              elementType: 'labels.text.fill',
              stylers: [{color: '#d59563'}]
            },
            {
              featureType: 'poi.park',
              elementType: 'geometry',
              stylers: [{color: '#263c3f'}]
            },
            {
              featureType: 'poi.park',
              elementType: 'labels.text.fill',
              stylers: [{color: '#6b9a76'}]
            },
            {
              featureType: 'road',
              elementType: 'geometry',
              stylers: [{color: '#38414e'}]
            },
            {
              featureType: 'road',
              elementType: 'geometry.stroke',
              stylers: [{color: '#212a37'}]
            },
            {
              featureType: 'road',
              elementType: 'labels.text.fill',
              stylers: [{color: '#9ca5b3'}]
            },
            {
              featureType: 'road.highway',
              elementType: 'geometry',
              stylers: [{color: '#746855'}]
            },
            {
              featureType: 'road.highway',
              elementType: 'geometry.stroke',
              stylers: [{color: '#1f2835'}]
            },
            {
              featureType: 'road.highway',
              elementType: 'labels.text.fill',
              stylers: [{color: '#f3d19c'}]
            },
            {
              featureType: 'transit',
              elementType: 'geometry',
              stylers: [{color: '#2f3948'}]
            },
            {
              featureType: 'transit.station',
              elementType: 'labels.text.fill',
              stylers: [{color: '#d59563'}]
            },
            {
              featureType: 'water',
              elementType: 'geometry',
              stylers: [{color: '#17263c'}]
            },
            {
              featureType: 'water',
              elementType: 'labels.text.fill',
              stylers: [{color: '#515c6d'}]
            },
            {
              featureType: 'water',
              elementType: 'labels.text.stroke',
              stylers: [{color: '#17263c'}]
            }
          ]
        });
        var marker = new google.maps.Marker({
            position: collectivelogic,
            map: map
        });
    }
</script>
<script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyB_i3fJEdgLjI1SdzRiA6nAKshwna_4g48&callback=initMap">
</script>

### By email
- {:.social-media}[<i class="fas fa-envelope"></i> hello@collective-logic.co.uk](mailto:hello@collective-logic.co.uk)

### Follow us
- {:.social-media}[<i class="fab fa-linkedin"></i> @collectivelgc](https://twitter.com/collectivelgc)
- {:.social-media}[<i class="fab fa-twitter-square"></i> Collective Logic](https://www.linkedin.com/company-beta/11159490/)
