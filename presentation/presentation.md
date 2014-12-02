title: Hacking Presentations : the Ruby way
author: Haris Dimitriou (xarisd)
description: An introduction to building simple presentations with Markdown
date: <%= Date.today %>
% available themes: Default - Sky - Beige - Simple - Serif - Night - Moon - Solarized
theme: serif
% available transitions: // default/cube/page/concave/zoom/linear/fade/none
transition: linear
custom_css: presentation
% code-engine: coderay


!SLIDE
## Hacking Presentations
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">Building a simple presentation with Markdown</p>

!SLIDE
## Who am I?

<p>&nbsp;</p>
<p>&nbsp;</p>
<h3 class="fragment">
  Haris Dimitriou (<strong>xarisd</strong>)
</h3>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">
  CTO and co-founder @  <a href="http://www.polyptychon.gr">Polyptychon</a> (<a href="http://polyptychon.gr">polyptychon.gr</a>)
</p>
<p>&nbsp;</p>
<p class="fragment">
  <br>
  ...just a developer
  <br>
  <br>
  <a href="http://github.com/xarisd">github.com/xarisd</a>
  <br>
  <a href="http://twitter.com/xarisd">twitter.com/xarisd</a>
  <br>
  <a href="http://xarisd.io">xarisd.io</a>
</p>


!SLIDE
## Agenda

<p>&nbsp;</p>

* Traditional Tools
* Tools as a Service
* Open Source Tools - HTML5 Presentation Engines
* S9



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
!SLIDE down-open
!SLIDE
## Traditional Tools


!SLIDE
#### (Traditional Tools)

## Most Common

<p>&nbsp;</p>
<ul>
  <li class="fragment"><a href="http://office.microsoft.com/en-au/powerpoint/">PowerPoint</a></li>
  <li class="fragment"><a href="https://www.apple.com/mac/keynote/">Keynote</a></li>
  <li class="fragment"><a href="http://www.smartdraw.com/software/presentation.asp">SmartDraw</a></li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">There are more, but...not interested :-)</p>

!SLIDE
#### (Traditional Tools)

## What are they good for?

<p>&nbsp;</p>
<ul>
  <li class="fragment">Sales</li>
  <li class="fragment">Pitching</li>
  <li class="fragment">Lots of interactivity and animations</li>
  <li class="fragment">Charts</li>
  <li class="fragment">...</li>
</ul>


!SLIDE
#### (Traditional Tools)

## Why and WHEN are they BAD?

<p>&nbsp;</p>
<ul>
  <li class="fragment">Speed of presentation development</li>
  <li class="fragment">Embedding <code>code</code> examples</li>
  <li class="fragment">You need dedicated software to make them</li>
  <li class="fragment">You need dedicated software to PLAY them</li>
  <li class="fragment">Not good for plenty of content (i.e. for educational purposes)</li>
  <li class="fragment"><strong>NOT FUN TO USE!</strong></li>
  <li class="fragment"><strong>NOT FUN TO USE!!</strong></li>
  <li class="fragment"><strong>NOT FUN TO USE!!!</strong></li>
</ul>


!SLIDE down-close
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
!SLIDE down-open
!SLIDE
## Tools as a Service
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">New kids on the block</p>

!SLIDE
#### (Tools as a Service)

## Most Common

<p>&nbsp;</p>
<ul>
  <li class="fragment"><a href="https://prezi.com/">Prezi</a></li>
  <li class="fragment"><a href="http://slides.com/">Slides (slides.com)</a></li>
  <li class="fragment"><a href="https://www.haikudeck.com/">Haiku Deck (in slideshare)</a></li>
  <li class="fragment"><a href="https://docs.google.com/presentation">Google Slides</a></li>
  <li class="fragment"><a href="http://www.powtoon.com/">PowToon</a></li>
  <li class="fragment"><a href="http://www.emaze.com/">emaze</a></li>
  <li class="fragment">...</li>
</ul>
<p>&nbsp;</p>
<p class="fragment">There are MANY more, but again...<span class="fragment">not interested</span></p>
<p>&nbsp;</p>
<p class="fragment">OK, maybe a little :-) </p>



!SLIDE
#### (Tools as a Service)

## What are they good for?
<p>&nbsp;</p>
<p class="fragment">...for the same reasons</p>
<ul>
  <li class="fragment">Sales</li>
  <li class="fragment">Pitching</li>
  <li class="fragment">Lots of interactivity and animations</li>
  <li class="fragment">Charts</li>
  <li class="fragment">...</li>
</ul>

!SLIDE
#### (Tools as a Service)

## Why are they BETTER than traditional tools?
<p>&nbsp;</p>
<p>&nbsp;</p>
<ul>
  <li class="fragment">You need ONLY a browser to make them</li>
  <li class="fragment">You need ONLY a browser to PLAY them</li>
  <li class="fragment">REALLY easy to SHARE a presentation</li>
</ul>
<p>&nbsp;</p>
<p class="fragment">but...</p>
<p>&nbsp;</p>
<p class="fragment">They are not as fully featured as the traditional tools</p>




!SLIDE
#### (Tools as a Service)

## Why and WHEN are they BAD?

<p>&nbsp;</p>
<p class="fragment">...pretty much for the same reasons</p>
<p>&nbsp;</p>
<ul>
  <li class="fragment">Speed of presentation development</li>
  <li class="fragment">Embedding <code>code</code> examples (a little better)</li>
  <li class="fragment">Not good for plenty of content (i.e. for educational purposes)</li>
  <li class="fragment"><strong>NOT FUN TO USE!</strong></li>
  <li class="fragment"><strong>NOT FUN TO USE!!</strong></li>
  <li class="fragment"><strong>NOT FUN TO USE!!!</strong></li>
</ul>


!SLIDE down-close
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
!SLIDE down-open
!SLIDE
## Open Source Tools
<p>&nbsp;</p>
<p>&nbsp;</p>
<h3 class="fragment">HTML5 Presentation Engines</h3>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">...now we are talking!</p>


!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## Most Common

<p>&nbsp;</p>
<ul>
  <li class="fragment"><a href="http://imakewebthings.com/deck.js/">deck.js</a></li>
  <li class="fragment"><a href="http://bartaz.github.io/impress.js/#/bored">impress.js</a></li>
  <li class="fragment"><a href="http://lab.hakim.se/reveal-js/#/">reveal.js</a></li>
  <li class="fragment"><a href="http://shwr.me/">shower</a></li>
  <li class="fragment"><a href="http://remarkjs.com/">remark</a></li>
  <li class="fragment"><a href="http://flowtime-js.marcolago.com/">flowtime.js</a></li>
  <li class="fragment"><a href="http://markdalgleish.com/projects/fathom/">Fathom.js</a></li>
  <li class="fragment">...</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">There are MANY more, coming up every day...</p>
<p>&nbsp;</p>
<p class="fragment">Give them a try and pick the one you prefer!</p>



!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## Why and WHEN are they BETTER?

<p>&nbsp;</p>
<p class="fragment">...pretty much for what WE do</p>
<p>&nbsp;</p>
<p class="fragment"><strong>MEETUP PRESENTATIONS!</strong></p>
<p>&nbsp;</p>
<p class="fragment">..."educational" presentations in general</p>


!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## Why and WHEN are they BETTER? (2)
<p>&nbsp;</p>
<h3 class="fragment">When you don't need</h3>
<p>&nbsp;</p>
<ul>
  <li class="fragment">Sales or Pitch presentation</li>
  <li class="fragment">Charts</li>
  <li class="fragment">Plenty of (unnecessary) animation</li>
</ul>


!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## Why and WHEN are they BETTER? (3)
<p>&nbsp;</p>
<h3 class="fragment">When the following features are important</h3>
<p>&nbsp;</p>
<ul>
  <li class="fragment">Speed of presentation development</li>
  <li class="fragment">Embedding <code>code</code> examples (a little better)</li>
  <li class="fragment">You need ONLY a TEXT EDITOR to make them</li>
  <li class="fragment">You need ONLY a BROWSER to PLAY them</li>
  <li class="fragment">You can make <strong>your own theme</strong></li>
  <li class="fragment">Easy sharing</li>
  </li>
</ul>

!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## Why and WHEN are they BETTER? (4)
<p>&nbsp;</p>
<h3 class="fragment">Really easy sharing</h3>
<p>&nbsp;</p>

<ul>
  <li class="fragment">It's just an HTML page</li>
  <li class="fragment">Put it in a server</li>
  <li class="fragment">Share the link!</li>
  <li class="fragment">or... upload them in
    <ul>
      <li class="fragment"><a href="https://speakerdeck.com">Speaker Desck (as pdf)</a></li>
      <li class="fragment"><a href="https://slides.com/">Slides.com (reveal.js compatible)</a></li>
      <li class="fragment">the service of your choice (as pdf)</li>
    </ul>
  </li>
</ul>


!SLIDE
#### (Open Source Tools - HTML5 Presentation Engines)

## What's the catch?

<p>&nbsp;</p>
<p class="fragment">...well</p>
<p>&nbsp;</p>
<h3 class="fragment">You make them in <code>HTML</code></h3>
<p>&nbsp;</p>
<p class="fragment">
  Not really good for plenty of content
  <br/>(i.e. for educational purposes)
</p>


!SLIDE
## So, is there a solution?


!SLIDE down-close
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
!SLIDE down-open
!SLIDE
## Meet S9

!SLIDE
## S9?

<div class="fragment">
  <%= image 'images/AudiA9render.jpg' %>
  <p>is it...an Audi?</p>
</div>

!SLIDE
## S9

<div class="fragment">
  <img src="images/Ruby_logo.png" height="400px"/>
  <%#= image 'images/Ruby_logo.png' %>
  <p>no...it's a Ruby gem</p>
</div>



!SLIDE
#### (S9)

## What does it do?
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">It takes Markdown and turns it to a Slide Show</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">Enter the Ruby way :-)</p>



!SLIDE
#### (S9)

## How to install it


!SLIDE
#### (S9)

## How to use it


!SLIDE
#### (S9)

## Demo time!


!SLIDE
#### (S9)

## More info



!SLIDE down-close
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
!SLIDE down-open
!SLIDE
## Thank you!
<p>&nbsp;</p>
<h3 class="fragment">Liked the presentation?</h3>
<p>&nbsp;</p>
<p class="fragment">
  Source: <a href="http://github.com/xarisd/hacking-presentations"> github.com/xarisd/hacking-presentations</a>
</p>
<p>&nbsp;</p>
<p>
<p class="fragment">
  View it online: <a href="http://xarisd.io/presentations/hacking-presentations.html">xarisd.io/presentations/hacking-presentations.html</a>
</p>
<p>&nbsp;</p>
<p class="fragment">
  Comments and feedback:<br/>
  Send a tweet (or a "bad" direct message :-))<br/>
  <a href="http://twitter.com/xarisd">@xarisd</a>
</p>
<p>&nbsp;</p>
<p class="fragment">Questions?</p>
