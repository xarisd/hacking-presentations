Rails Basics 01
==========================

Presentation is made with slideshow gem and reveal.js library (links at the "Tools used" section).

## How to Build/Test the presentation

1. You will need Ruby 2.1.2
2. Install Bundler
<pre><code>gem install bundler</code></pre>
3. Install dependencies

  Install the gems
  <pre><code>bundle install</code></pre>

  You will also need to install manualy the slideshow-reveal.js template in order to build the presentation <br/>(see <https://github.com/avillafiorita/slideshow-reveal.js#installation>)
4. Edit the presentation files (**presentation/presentation.md** and the ruby files inside **presentation/code** directory)
5. Build the presentation
  <pre><code>rake</code></pre>
6. Test the presentation in browser (opens automatically through rake default task)

## Tools used

* https://github.com/slideshow-s9/slideshow
* https://github.com/avillafiorita/slideshow-reveal.js
