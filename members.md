---
layout: page
title: Lab members
section_id: about
---

<h3>Current members</h3>
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

<h3>Alumni</h3>
<div class='full'>
  <div class='row'>
    {% for member in site.data.alumni %}
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
