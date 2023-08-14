---
layout: page
title: Lab collaborations
section_id: about
---

<div class='full'>
  <div class='row'>
    {% for member in site.data.collaborations %}
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
