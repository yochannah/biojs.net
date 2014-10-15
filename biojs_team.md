---
layout: container
title: BioJS Team
extra_css:
 - css/people.css
team: 
 - name: Seth Carbon
   institute: Berkeley Lab
   img: https://sigil.cupcake.io/seth
 - name: Saket Choudhary
   institute: University Of Southern California
   img: https://avatars2.githubusercontent.com/u/682153?v=2&s=460
   github: saketkc
 - name: David Dao
   institute: TUM
   img: https://sigil.cupcake.io/daviddao
 - name: Alex Garcia
   institute: Uni Bonn
   img: https://sigil.cupcake.io/alexgarcia
 - name: Leyla Garcia
   institute: EMBL-EBI
   img: https://avatars1.githubusercontent.com/u/5427252?v=2&s=460
   github: ljgarcia
 - name: Tatyana Goldberg
   institute: RostLab, TUM
   img: img/team/tatyana.jpg
   personLink: http://www.rostlab.org/~goldberg
   instituteLink: http://www.rostlab.org/
   github: TatyanaGoldberg
 - name: John Gomez
   institute: EMBL-EBI
   img: https://sigil.cupcake.io/johngomez
 - name: Alex Kalderimis
   institute: Cambridge
   img: https://sigil.cupcake.io/alexkalderimis
 - name: Ian Mulvany
   institute: eLife
   img: https://sigil.cupcake.io/ianmulvany
 - name: Miguel Pignatelli
   institute: EBI
   github: emepyc
   img: https://avatars3.githubusercontent.com/u/473962?v=2&s=460
 - name: Ricardo Ramirez
   institute: TGAC
   github: homonecloco
   img: https://avatars3.githubusercontent.com/u/254050?v=2&s=460
 - name: Francis Rowland
   institute: EMBL-EBI
   img: https://sigil.cupcake.io/francisrowland
 - name: Gustavo Salazar
   institute: Cape Town Uni
   img: https://avatars3.githubusercontent.com/u/2870295?v=2&s=460
   github: 4ndr01d3
 - name: Fabian Schreiber
   institute: EMBL-EBI
   img: https://sigil.cupcake.io/fabianschreiber
 - name: Ian Silitoe
   institute: UCL
   img: https://avatars1.githubusercontent.com/u/152954?v=2&s=460
 - name: William Spooner
   institute: Eagle Genomics
   img: https://sigil.cupcake.io/williamspooner
 - name: Anil Thanki
   institute: TGAC
   img: https://sigil.cupcake.io/anilthanki
 - name: Jose Villaveces
   institute: Max Planck Institute
   img: https://sigil.cupcake.io/josevilleveces
 - name: Sebastian Wilzbach
   institute: RostLab, TUM
   github: greenify
   img: img/team/seb.jpg
 - name: Guy Yachdav
   institute: RostLab, TUM
   github: 
   img: img/team/guy.jpg
 - name: Your name
   institute: your institute
   img: https://sigil.cupcake.io/yourimg

---

<!-- 
IMPORTANT: please upload your image in img/team and read the README their (1:1 dimension, max 200px)
-->

<div id="people-container">

<div class="row">

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/manny">
<div class="people-name"> Manuel Corpas </div>
<div class="people-institution"> TGAC </div>
<div class="people-position"> Project Coordinator, PI </div>
</div>

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/hennig">
<div class="people-name"> Henning Hermjakob </div>
<div class="people-institution"> EMBL-EBI </div>
<div class="people-position"> Senior PI </div>
</div>

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/suzi">
<div class="people-name"> Suzi Lewis </div>
<div class="people-institution"> Berkeley Lab </div>
<div class="people-position"> Senior PI </div>
</div>

<div class="col-md-2 col-xs-4">
<img src="https://avatars1.githubusercontent.com/u/2062396?v=2&s=460">
<div class="people-name"> Rafael Jiménez  </div>
<div class="people-institution"> ELIXIR </div>
<div class="people-position"> Chief Technical Coordinator </div>
</div>


<div class="clearfix"> </div>

</div>

<div class="row">

{% for person in page.team %}

<div class="col-md-2 col-xs-4">
<img src="{{ person.img }}">
<div class="people-name">
{% if person.personLink != nil %}
<a href="{{ person.personLink }}">{{ person.name }}</a>
{% else %}
{{ person.name }}
{% endif %}
</div>
<div class="people-institution">
{% if person.instituteLink != nil %}
<a href="{{ person.instituteLink }}">{{ person.institute }}</a>
{% else %}
{{ person.institute }}
{% endif %}
</div>
</div>

{% cycle nil, nil, '<div class="visible-xs clearfix"> </div>', nil, nil, '<div class="clearfix"> </div>' %}

{% endfor %}

</div>


Former members
-------

<div class="row">

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/">
<div class="people-name">
First_name Last_name
</div>
<div class="people-institution">
Institution
</div>
</div>

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/">
<div class="people-name">
First_name Last_name
</div>
<div class="people-institution">
Institution
</div>
</div>

<div class="col-md-2 col-xs-4">
<img src="https://sigil.cupcake.io/">
<div class="people-name">
First_name Last_name
</div>
<div class="people-institution">
Institution
</div>
</div>



</div>