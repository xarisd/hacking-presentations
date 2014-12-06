Hacking Presentations
==========================

This is a presentation about how to build presentations (the slides) using Markdown.

You can enjoy it online at <http://xarisd.io/presentations/hacking-presentations>


## About this repository

Here you can find the source of the slides used for the presentation along with the tooling needed to build them.

Presentation is made with [Slide Show (s9) gem](https://github.com/slideshow-s9/slideshow) and [reveal.js HTML Presentation Framework](https://github.com/hakimel/reveal.js).

## How to build/test the presentation

1. You will need **Ruby 2.1.2**

2. Install Bundler
<pre><code>gem install bundler</code></pre>

3. Install the required gems (Ruby libraries needed)
<pre><code>bundle install</code></pre>

4. Install the s9 template for reveal.js

  You need to install manualy the slideshow-reveal.js template in order to build the presentation.

  For instructions see here:  <https://github.com/xarisd/slideshow-reveal.js/blob/add-submodule-commands-to-readme/README.markdown>.

  Important! The [official](  <https://github.com/avillafiorita/slideshow-reveal.js#installation>) "Installation" section lacks the steps for the reveal.js submodule. So you get errors when "building" the presentation.

  I have made a [Pull Request](https://github.com/avillafiorita/slideshow-reveal.js/pull/3) to contribute. Until this is fixed...use my version of instructions :-)

5. Edit the presentation files (**presentation/presentation.md** and the ruby files inside **presentation/code** directory)

6. Build the presentation
  <pre><code>rake</code></pre>

7. Test the presentation: open <code>presentation/slides/presentation.html</code> in browser and enjoy.

8. Explore what else you can do (export to pdf, open in browser etc)
<pre><code>rake -T</code></pre>


## Tools used

* https://github.com/slideshow-s9/slideshow
* https://github.com/avillafiorita/slideshow-reveal.js
