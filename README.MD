Venuekick
=========


<em>Use Venuekick to search for concert venues and music listings by city.</em>

Venuekick is a web application project created with Ruby on Rails, which utilizes the <a href-"http://www.songkick.com/developer">Songkick API</a> through the <a href="https://github.com/jrmehle/songkickr">Songkickr Gem</a> to search for concert venues by city. 

Venuekick pulls langitude and longitude coordinates of all the city's concert venues and plots them on a Google Map. Upcoming concert listings (for artists/bands/performers) are listed beside each individual venue. Search form uses the ruby wrapper for <a href="https://github.com/phuphighter/google_places_autocomplete">Google Places Autocomplete<a>. 

The homepage pulls Instagram images using the <a href="https://github.com/Instagram/instagram-ruby-gem">Instagram gem</a> by searching results for "concertjunkie" and "concertphotography." Pages for each individual concert venue (Ex: Troubadour, Los Angeles, CA) searches Instagram images by venue name.

Copyright 2014 Greg Rock
