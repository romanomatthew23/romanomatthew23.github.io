---
layout: default
---
# About Me
In September 2022 I will be starting a new position as Robotics Autonomy Engineer at SkySpecs! 

I recently graduated (August 2022) from the University of Michigan with a PhD in Robotics. Throughout my PhD I have enjoyed researching novel aerospace technologies that can revolutionize industries. My focus has been on autonomy for teams of unmanned aircraft systems (UAS) and in particular planning and control for diverse missions including: deformable formation control, cooperative multilift slung load transportation with haptic guidance, and multi-UAS wildfire mapping. I am an electronics enthusiast, care about embedded systems, and value real-time, efficient algorithms. The majority of my research has been experimentally validated on actual systems with real-world considerations in mind.

I want to do epic things, pursue my passions, and help those around me.


# Education    
**PhD** Robotics, University of Michigan (Aug 2022) <br>
**MS** Robotics, University of Michigan (May 2019) <br>
**BS** Electrical Engineering (Computer Science Minor), University of Illinois Urbana-Champaign (Dec 2016)

# Research Highlights
<div style="width: 100%;">
    <div style="width: 46%; float: left; height: 280px;background: AliceBlue; padding: 10px;
                "> 
    <a href="{{site.baseurl}}/posts/2020/07/17/deformable-formation-control.html">
        <img src="{{site.baseurl}}/images/acc2019_teaser_figure.png">
    </a><br><br><br>
    <h2 style="text-align:center;">
        <a href="{{site.baseurl}}/posts/2020/07/17/deformable-formation-control.html">Deformable Formation Control
        </a>
    </h2>
    </div><div style="margin-left: 46%; width: 8%;               "> 
    </div>
    <div style="margin-left: 54%; width: 46%; height: 280px;background: AliceBlue;    padding: 10px;           "> 
      <a href="{{site.baseurl}}/posts/2022/03/28/cooperative-payload-haptic-guidance.html">
        <img src="{{site.baseurl}}/images/haptic_guidance_1st_person_cropped.jpg">
    </a>
    <h2 style="text-align:center;">
        <a href="{{site.baseurl}}/posts/2022/03/28/cooperative-payload-haptic-guidance.html">Multilift Slung Load Transport with Haptic Guidance
        </a>
    </h2> 
    </div>
</div>

<br>

<div style="width: 100%;">
    <div style="width: 46%; float: left; background: AliceBlue; padding: 10px; height: 250px;
                "> 
    <br><br>
    <a href="{{site.baseurl}}/posts/2022/03/28/wildfire-mapping.html">
        <img src="{{site.baseurl}}/images/wildfire_mapping.png">
    </a>
    <br><br><br>
    <h2 style="text-align:center;">
        <a href="{{site.baseurl}}/posts/2022/03/28/wildfire-mapping.html">Multi-UAS Wildfire Mapping
        </a>
    </h2>
    </div><div style="margin-left: 46%; width: 8%;               "> 
    </div>
    <div style="margin-left: 54%; width: 46%; background: AliceBlue;    padding: 10px; height: 250px;          "> 

  <a href="{{site.baseurl}}/posts/2022/03/28/deformable-formation-planning.html">
     <img src="{{site.baseurl}}/images/iros2022.png">
</a><br><br>
<h2 style="text-align:center;">
    <a href="{{site.baseurl}}/posts/2022/03/28/deformable-formation-planning.html">Deformable Formation Planning
    </a>
</h2>
    </div>
</div>

<br>

# Additional Projects

<div style="width: 100%;">
    <div style="width: 46%; float: left; background: AliceBlue; padding: 10px;height: 240px;
                "> 
        <a href="{{site.baseurl}}/posts/2022/03/28/nailgun-drone.html">
            <img src="{{site.baseurl}}/images/autonomous_roofing_board_view.png">
        </a>
        <h2 style="text-align:center;">
            <a href="{{site.baseurl}}/posts/2022/03/28/nailgun-drone.html">Autonomous Roofing
            </a>
        </h2>
    </div>
    <div style="margin-left: 46%; width: 8%;               "> 
    </div>
    <div style="margin-left: 54%; width: 46%; background: AliceBlue;    padding: 10px;height: 240px;           ">
        <br>
        <a href="{{site.baseurl}}/posts/2022/03/28/nailgun-drone.html">
            <img src="{{site.baseurl}}/images/rob103.jpg">
        </a>
        <br><br><br>
        <h2 style="text-align:center;">
            <a href="{{site.baseurl}}/posts/2021/05/28/rob-103.html">ROB 103
            </a>
        </h2> 
    </div>
</div>

<br>

<div style="width: 100%;">
    <div style="width: 46%; float: left; background: AliceBlue; padding: 10px;height: 240px;
                "> 
        <a href="{{site.baseurl}}/posts/2022/03/28/nsin-hackathon.html">
            <img src="{{site.baseurl}}/images/SCRIBE_Mockup.png">
        </a>
        <h2 style="text-align:center;">
            <a href="{{site.baseurl}}/posts/2022/03/28/nsin-hackathon.html">Into the Dataverse Hackathon
            </a>
        </h2>
    </div>    
    <div style="margin-left: 46%; width: 8%;               "> 
    </div>
    <div style="margin-left: 54%; width: 46%; background: AliceBlue;    padding: 10px;height: 240px;           ">
        <a href="{{site.baseurl}}/posts/2022/03/28/m330quadrotor-rc-pilot.html">
            <img src="{{site.baseurl}}/images/m330_quadrotor.png" width= "80%" style="margin-left: 10%;" class="center">
        </a>
        <h2 style="text-align:center;">
            <a href="{{site.baseurl}}/posts/2022/03/28/m330quadrotor-rc-pilot.html">M330-Quadrotor & rc_pilot_a2sys Flight Controller
            </a>
        </h2> 
    </div>
</div>

<br>

 <h1>Undergrad & Fun Projects</h1>
  {% for post in site.categories.undergrad %}
  <article>
  <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    
  </article>
{% endfor %}