
[comment]: <> ( Colour Key )

<div class="colour_key">
  <p style="text-align: center"><strong>KEY</strong></p>
  <p><span style="background-color: #f5c44b">&nbsp;</span> Accessibility</p>
  <p><span style="background-color: #3ee9d1">&nbsp;</span> Other</p>
  <p><span style="background-color: #ce43eb">&nbsp;</span> Lab research</p>
  <p><span style="background-color: #4d92eb">&nbsp;</span> Online research</p>
  <p><span style="background-color: #935300">&nbsp;</span> Partners collaboration - co-design</p>
</div>


<ul>
  {% for post in site.posts %}

      <div class="timeline_card {{post.type}}">
        <div class="timeline_head">
          <h2><span class="small">{{ post.display_date }}</span>Online Research</h2>
        </div>
        <div class="timeline_body">
          Content of the actual card
        </div>
      </div>


  {% endfor %}
</ul>
