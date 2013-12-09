<!DOCTYPE html>
<html>

  <head>
    <meta charset='utf-8' />
    <meta http-equiv="X-UA-Compatible" content="chrome=1" />
    <meta name="description" content="Linda's blog about coding and probably more likely cats : The simplicity of this blog illustrates the laziness of software developers" />

    <link rel="stylesheet" type="text/css" media="screen" href="stylesheets/stylesheet.css">

    <title>Linda's blog about coding and probably more likely cats</title>
  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="https://github.com/lynnaloo">View on GitHub</a>

          <h1 id="project_title">Linda's blog about coding and probably more likely cats</h1>
          <h2 id="project_tagline">The simplicity of this blog illustrates the laziness of software developers</h2>

        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        <h3>
<a name="welcome" class="anchor" href="#welcome"><span class="octicon octicon-link"></span></a>Welcome.</h3>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <!-- <p>{{ post.excerpt }}</p> -->
    </li>
  {% endfor %}
</ul>

<h3>
<a name="how-to-find-me" class="anchor" href="#how-to-find-me"><span class="octicon octicon-link"></span></a>How to find me.</h3>

<p>Twitter: <a href="https://github.com/lynnaloo" class="user-mention">@lynnaloo</a></p>
      </section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        <p></p>
      </footer>
    </div>



  </body>
</html>