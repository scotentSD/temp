

<section id="timeline">
<h3>Beta Timeline</h3>
<div class="colour_key">
  <p style="text-align: left"><strong>KEY</strong></p>
  <p><span style="background-color: #f5c44b">&nbsp;&nbsp;</span> Accessibility</p>
  <p><span style="background-color: #3ee9d1">&nbsp;&nbsp;</span> Other</p>
  <p><span style="background-color: #ce43eb">&nbsp;&nbsp;</span> Lab research</p>
  <p><span style="background-color: #4d92eb">&nbsp;&nbsp;</span> Online research</p>
  <p><span style="background-color: #935300">&nbsp;&nbsp;</span> Partners collaboration - co-design</p>
</div>

<ul class="timeline_ul">
  {% for post in site.posts %}
      <div class="timeline_card">

        <div class="timeline_head {{post.type}}">
          <span class="date_{{post.type}}" > {{ post.display_date }} </span>
          <br>
          <span class="type_{{post.type}}" > </span>  
        </div>
        <div class="timeline_body">
          {{ post.excerpt }}
        </div>
      </div>
  {% endfor %}
</ul>


</section>
