---
layout: page
title: About the NumberWorks lab
section_id: about
---

<!-- About us -->
{% include section-header.html title="About us" %}

Our lab is at [Eötvös Loránd University](http://www.elte.hu/en). 

Find our Hungarian webpage [here](https://sites.google.com/site/matematikaimegismeres/).


<!-- Members -->
{% include section-header.html title="Lab members" %}

<div class='full'>
  <div class='row'>
    {% for member in site.data.members %}
      <div class='small-4 medium-3 large-3 columns'>
        <div class='mod modTeamMember'>
          <div class='member'>
            <img class="avatar" alt="" src="{{ member.avatar }}" />
            <div class='overlay'>
              <div class='intro'>
                <h3>{{member.name}}</h3>
                <p>{{member.position}}</p>
                <ul class='socials'>
                  {% for social in member.socials %}
                    <li>
                      <a href='{{social.link}}'>
                        <i class='fa fa-{{social.icon}}'></i>
                      </a>
                    </li>
                  {% endfor %}
                </ul>
              </div>
            </div>
          </div>
          <p class='centered-text'>{{member.desc}}</p>
          <div class='two spacing'></div>
        </div>
      </div>
    {% endfor %}
  </div>
</div>


<!-- Events -->
{% include section-header.html title="Events" %}

Find some of the events where you can meet us.

<iframe src="https://calendar.google.com/calendar/embed?showPrint=0&amp;showCalendars=0&amp;mode=AGENDA&amp;height=400&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=1drtia47l13oloprn5fo4o9974%40group.calendar.google.com&amp;color=%23ccb7a7&amp;ctz=Europe%2FBudapest" style="border-width:0" width="800" height="400" frameborder="0" scrolling="no"></iframe>

<div class='two spacing'></div>

<!-- Contact us -->
{% include section-header.html title="Contact us" %}

<div class='full'>
  <div class='row'>
    <div class='medium-6 columns'>
        <div class='fadein mod modIconText' data-delay='{{ 300 | times:forloop.index0 }}'>
          <div class='icon-text-simple'>
            <i class='fa fa-map-marker'></i>
            <h3>Address</h3>
            <p>Budapest<br>Izabella utca 46.<br>1064, Hungary</p>
          </div>
          <div class='two spacing'></div>
        </div>
    </div>
    <div class='medium-6 columns'>
        <div class='fadein mod modIconText' data-delay='{{ 300 | times:forloop.index0 }}'>
          <div class='icon-text-simple'>
            <i class='fa fa-envelope'></i>
            <h3>Email</h3>
            <p><a href="mailto:krajcsi@gmail.com">Attila Krajcsi</a></p>
          </div>
          <div class='two spacing'></div>
        </div>
    </div>
  </div>
</div>

<iframe width="600" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://www.openstreetmap.org/export/embed.html?bbox=19.03664588928223%2C47.494182604162184%2C19.10080432891846%2C47.51867884501743&amp;layer=mapnik&amp;marker=47.506432153588%2C19.068725109100342" style="border: 1px solid black"></iframe><small><a href="https://www.openstreetmap.org/?mlat=47.5064&amp;mlon=19.0687#map=15/47.5064/19.0687">Larger map</a></small>

