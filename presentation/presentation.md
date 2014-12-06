title: Hacking Presentations : the Ruby way
author: Haris Dimitriou (xarisd)
description: An introduction to building simple presentations with Markdown
date: <%= Date.today %>
% available themes: Default - Sky - Beige - Simple - Serif - Night - Moon - Solarized
theme: simple
% available transitions: // default/cube/page/concave/zoom/linear/fade/none
transition: linear
custom_css: presentation
% code-engine: coderay


!SLIDE
## Hacking Presentations
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">Building presentations with simple markup</p>

!SLIDE
## Who am I?
<p>&nbsp;</p>
<h3 class="fragment">
  Haris Dimitriou (<strong>xarisd</strong>)
</h3>
<p>&nbsp;</p>
<p class="fragment">
  Ruby developer<span class="fragment">...among other things</span>
</p>
<p>&nbsp;</p>
<p class="fragment">
  CTO and co-founder @<a href="http://www.polyptychon.gr">Polyptychon</a> (<a href="http://polyptychon.gr">polyptychon.gr</a>)
</p>
<p>&nbsp;</p>
<p class="fragment">
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
  <li class="fragment">"Sales like" presentations</li>
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
<p class="fragment">OK, maybe a little :-) </p>



!SLIDE
#### (Tools as a Service)

## What are they good for?
<p>&nbsp;</p>
<p class="fragment">...for the same reasons</p>
<p>&nbsp;</p>
<ul>
  <li class="fragment">"Sales like" presentations</li>
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
##### (HTML5 Presentation Engines)

## Most Common

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
<p class="fragment">There are MANY more, coming up every day...</p>
<p class="fragment">Give them a try and pick the one you prefer!</p>



!SLIDE
##### (HTML5 Presentation Engines)

### Why and WHEN are they BETTER?

<p>&nbsp;</p>
<p class="fragment">They are <strong>excellent</strong> for what WE do</p>
<p>&nbsp;</p>
<p class="fragment"><strong>MEETUP PRESENTATIONS!</strong></p>
<p>&nbsp;</p>
<p class="fragment">And "educational" presentations in general</p>


!SLIDE
##### (HTML5 Presentation Engines)

### Why and WHEN are they BETTER? (2)
<p>&nbsp;</p>
<h3 class="fragment">When you don't need</h3>
<p>&nbsp;</p>
<ul>
  <li class="fragment">A "Sales like" presentation</li>
  <li class="fragment">Charts</li>
  <li class="fragment">Plenty of (unnecessary) animation</li>
</ul>


!SLIDE
##### (HTML5 Presentation Engines)

### Why and WHEN are they BETTER? (3)
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">When the following features are important</p>
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
##### (HTML5 Presentation Engines)

### Why and WHEN are they BETTER? (4)
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
##### (HTML5 Presentation Engines)

## What's the catch?

<p>&nbsp;</p>
<p class="fragment">well...</p>
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
  <img src="images/AudiA9render.jpg" alt="Audi S9" height="400px"/>
  <p>Is it...an Audi?</p>
</div>

!SLIDE
## S9

<div>
  <img src="images/Ruby_logo.png" height="400px"/>
  <%#= image 'images/Ruby_logo.png' %>
  <p>No...it's a Ruby gem</p>
</div>



!SLIDE
## What does it do?
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">It takes Markdown (or Textile) and turns it to a Slide Show</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">Enter the Ruby way :-)</p>



!SLIDE
## How to install it
<p>&nbsp;</p>
<p>&nbsp;</p>
<p class="fragment">1. You will need Ruby (preferably >= 2.0)</p>
<p>&nbsp;</p>
<p class="fragment">2. Install the slideshow (S9) gem</p>

<pre class="fragment">
  <code class="bash">
    <%= include 'code/01_gem_install_slideshow.sh' %>
  </code>
</pre>

!SLIDE
## How to use it

!SLIDE
<p>&nbsp;</p>
<p>1. Create a file in <code>Markdown</code> or <code>Textile</code> , <br/><br/>for example <code>presentation.md</code></p>
<pre class="fragment"><code class="markdown">
<%= include 'code/presentation.md' %>
</code></pre>

!SLIDE
<p>&nbsp;</p>
<p>2. Build the presentation with <code>slideshow</code> cli</p>
<pre class="fragment"><code class="bash">
<%= include 'code/03_slideshow_build.sh' %>
</code></pre>
<p>&nbsp;</p>
<p class="fragment">3. Open the generated <code>presentation.html</code> in your browser</p>

!SLIDE
## Demo time!


!SLIDE
### OK that's nice...but it is UGLY!


!SLIDE
## No problem
<p>&nbsp;</p>
<p class="fragment">You can use it with HTML5 Presentation Engines</p>
<p>&nbsp;</p>
<p class="fragment">Yeah!</p>


!SLIDE
### Which Engines are supported
<p>&nbsp;</p>
<p class="fragment">In S9 lingo they are called "Template Packs"</p>
<p>&nbsp;</p>
<ul>
  <li class="fragment"><a href="http://imakewebthings.com/deck.js/">deck.js</a></li>
  <li class="fragment"><a href="http://bartaz.github.io/impress.js/#/bored">impress.js</a></li>
  <li class="fragment"><a href="http://lab.hakim.se/reveal-js/#/">reveal.js</a> <a href="https://github.com/xarisd/slideshow-reveal.js/blob/add-submodule-commands-to-readme/README.markdown">(manual installation)</a></li>
  <li class="fragment"><a href="https://github.com/slideshow-s9/slideshow">s5blank</a></li>
  <li class="fragment"><a href="https://github.com/slideshow-s9/slideshow">s5themes</a></li>
  <li class="fragment"><a href="https://github.com/slideshow-s9/slideshow">slidy</a></li>
  <li class="fragment"><a href="https://github.com/slideshow-s9/slideshow">g5</a></li>
  <li class="fragment"><a href="https://github.com/slideshow-s9/slideshow">csss</a></li>
</ul>


!SLIDE
### How to install the "Template Packs"
<p>&nbsp;</p>
<p class="fragment">With the <code>slideshow</code> cli</p>
<pre class="fragment"><code class="bash">
<%= include 'code/04_slideshow_install_a.sh' %>
</code></pre>


!SLIDE
## How to use a "Template Pack"
<p>&nbsp;</p>
<p>With the <code>slideshow</code> cli during <code>build</code></p>
<pre class="fragment"><code class="bash">
<%= include 'code/05_slideshow_build_impress.sh' %>
</code></pre>


!SLIDE
## Demo time AGAIN!



!SLIDE
### OK that's nice...
<p>&nbsp;</p>
<h3 class="fragment">but I want to use the <code>???</code> engine.</h3>


!SLIDE
### No problem
<p>&nbsp;</p>
<p>&nbsp;</p>
<h3 class="fragment">You can built <br/><a href="http://slideshow-s9.github.io/template.html">your own Template Pack</a>!</h3>
<p>&nbsp;</p>
<p class="fragment"><a href="https://github.com/xarisd/slideshow-reveal.js">slideshow-reveal.js</a> is such an example </p>

!SLIDE
### A final piece of advice
<p>&nbsp;</p>
<p>&nbsp;</p>
<h3 class="fragment">Automate!</h3>
<h3 class="fragment">Automate!!</h3>
<h3 class="fragment">Automate!!!</h3>
<p>&nbsp;</p>
<p class="fragment">Take a look at the source of this presentation <br/><a href="https://github.com/xarisd/hacking-presentations">https://github.com/xarisd/hacking-presentations</a></p>
<p>&nbsp;</p>
<p class="fragment">I am using <code>rake</code> tasks to automate my workflow.</p>


!SLIDE
## More Info
<p>&nbsp;</p>
<ul>
  <li class="fragment">
    slideshow (S9) source: <a href="https://github.com/slideshow-s9/slideshow">https://github.com/slideshow-s9/slideshow</a>
  </li>
  <!-- <p>&nbsp;</p> -->
  <li class="fragment">
    slideshow (S9) documentation: <a href="http://slideshow-s9.github.io/">http://slideshow-s9.github.io/</a>
  </li>
  <li class="fragment">
    How to install the <a href="https://github.com/hakimel/reveal.js">reveal.js</a> template pack: <a href="https://github.com/xarisd/slideshow-reveal.js/blob/add-submodule-commands-to-readme/README.markdown">github.com/xarisd/slideshow-reveal.js</a> (fork)
  </li>
</ul>
<p>&nbsp;</p>
<p class="fragment">Oh!</p>
<p class="fragment">About automation...</p>
<p>&nbsp;</p>
<p class="fragment"><a href="https://github.com/ruby/rake">https://github.com/ruby/rake</a></p>
<p class="fragment">...awesomeness :-)</p>

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
  View it online: <a href="http://xarisd.io/presentations/hacking-presentations">xarisd.io/presentations/hacking-presentations</a>
</p>
<p>&nbsp;</p>
<p class="fragment">
  Have something to say?
</p>
<p class="fragment">
  Send me a tweet or direct message: <a href="http://twitter.com/xarisd">@xarisd</a>
</p>
<p>&nbsp;</p>
<p class="fragment">Questions?</p>
