# Creating-AI-Data-Products-Using-Jupyter-Notebooks

<a href="https://jupyter.org/try" style="outline: none;">Jupyter</a> is an incredibly powerful coding tool for interactively developing and presenting coding workflows.
This GitHub-repository will walk you through "How to employ Jupyter Notebooks for data science projects". We start by explaining how to set it up on your local machine [DIY].

To be more precice, Jupyter notebook is a <a href="https://en.wikipedia.org/wiki/Integrated_development_environment" target="_blank" style="outline: none;" rel="noopener">cloud-based IDE</a> [Integrated Development Environment]. Data Scientists use notebboks predominantly to create documents [.ipynb] that can be created and shared with live codes. That is, it is a web-based interactive computational environment. The Jupyter notebook can support various languages that are popular in data science such as Python, Julia, Scala, R, etc.1

The goal is to set users on the path toward using the Python language by preparing them to write their 1rst script. This tutorial is divided in the following fashion: a small introduction to Python, how to download the Anaconda software, the different content that comes with the installation, and a simple example related to implementing a Python script.

Best of all, as part of the open source <a href="https://jupyter.org/" style="outline: none;">Project Jupyter</a>, Jupyter Notebooks are completely free. You can download the software <a href="https://jupyter.org/install" target="_blank" style="outline: none;" rel="noopener">on its own</a>, or as part of the <a href="https://www.anaconda.com/products/individual" target="_blank" rel="noopener">Anaconda data science toolkit</a>.

![jupyter](https://user-images.githubusercontent.com/684692/191042084-f82c5fb2-1b46-40fe-a631-420493397049.png)


<html lang="en"><head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Use our tools without installing anything">
    <title>Project Jupyter | Try Jupyter</title>
    <meta property="og:title" content="Project Jupyter">
    <meta property="og:description" content="The Jupyter Notebook is a web-based interactive computing platform. The notebook combines live code, equations, narrative text, visualizations, interactive dashboards and other media.
">
    <meta property="og:url" content="https://jupyter.org">
    <meta property="og:image" content="https://jupyter.org/assets/share.png">
    <link rel="canonical" href="https://jupyter.org/try">
    <style class="anchorjs"></style><link rel="stylesheet" href="/assets/css/bootstrap.css">
    <link rel="stylesheet" href="/assets/css/main.css">
    <link rel="icon" type="image/x-icon" href="/favicon.ico">
    <link rel="apple-touch-icon" href="/assets/favicons/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/assets/favicons/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/assets/favicons/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/assets/favicons/apple-touch-icon-180x180.png">
    <link rel="apple-touch-icon" sizes="167x167" href="/assets/favicons/apple-touch-icon-167x167.png">
    <script>console.log('Welcome to Project Jupyter! Explore the various tools available and their corresponding documentation. If you are interested in contributing to the platform, please visit the community resources section at https://jupyter.org/community.html.')</script>
  </head>
  <body>
    <nav class="navbar">
        <div class="navbar-header">
            <a class="navbar-brand" href="/">
               <picture>
                <source media="(max-width: 767px)" srcset="/assets/logos/logomark-orangebody-greyplanets.svg">
                <source media="(min-width: 768px)" srcset="/assets/logos/rectanglelogo-greytext-orangebody-greymoons.svg">
                <img class="navbar-logo" src="/assets/logos/rectanglelogo-greytext-orangebody-greymoons.svg" alt="Jupyter Home" height="40" loading="eager">
               </picture>
            </a>
        </div>
        <button type="button" class="hamburger" data-bs-toggle="collapse" data-bs-target="#bs-navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar white-icon-bar"></span>
            <span class="icon-bar white-icon-bar"></span>
            <span class="icon-bar white-icon-bar"></span>
        </button>
        <div class="mobile-clearfix"></div>
        <div class="collapse navbar-collapse" id="bs-navbar-collapse">
            <ul class="navbar-links"><li>
                <a href="/try" class="navbar-active">
                   Try
               </a>
            </li><li>
                <a href="/install" class="">
                   Install
               </a>
            </li><li>
                <a href="/community" class="">
                   Get Involved
               </a>
            </li><li>
                <a href="https://docs.jupyter.org/" target="_blank" rel="noopener noreferrer" class="">
                   Documentation
               </a>
            </li><li>
                <a href="https://blog.jupyter.org" target="_blank" rel="noopener noreferrer" class="">
                   News
               </a>
            </li><li>
                <a href="/governance/" class="">
                   Governance
               </a>
            </li><li>
                <a href="/security" class="">
                   Security
               </a>
            </li><li>
                <a href="/about" class="">
                   About
               </a>
            </li>
            </ul>
        </div>
    </nav>
    <section>
      <header class="page-header">
  
    <h1>Try Jupyter</h1>
  
  <p>Use our tools without installing anything</p>

  <script src="https://cdn.jsdelivr.net/npm/anchor-js/anchor.min.js"></script>
  <script>
    document.addEventListener('DOMContentLoaded', function(event) {
      anchors.add();
    });
  </script>
</header>


<article>
  <div class="section-white top-section-border container">
    <div class="content content--copy">
      <p>Project Jupyter builds tools, standards, and services for many different use cases. This page
has links to interactive demos that allow you to try some our tools for free online, thanks to
<a href="https://mybinder.org">mybinder.org</a>, a free public service provided by the Jupyter community.
</p>
    </div>
    <!-- Applications section -->
    <div class="content content--copy">
      <h2 id="applications">Applications<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#applications" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
      <p>The Jupyter team builds several end-user applications that facilitate interactive computing workflows.
Click the boxes below to learn how they work and to learn more.
If you like one, you can find <a href="/install">installation instructions here</a>.

<br><br>
⚠️<strong>Experimental</strong>⚠️ several of the environments below use the
<a href="https://jupyterlite.readthedocs.io/en/latest/">JupyterLite project</a> to provide a self-contained
Jupyter environment that runs in your browser. This is experimental technology and
may have some bugs, so please be patient and report any unexpected behavior in
<a href="https://github.com/jupyterlite/jupyterlite/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc">the JupyterLite repository</a>.
</p>
    </div>
    <div class="content content--wide boxlist"><section class="box">
  <a href="https://jupyter.org/try-jupyter/lab?path=notebooks%2FIntro.ipynb" class="box-link">
    <h2 class="box-title" id="jupyterlab">JupyterLab<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#jupyterlab" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Jupyter logo - Launch JupyterLab demo Binder" src="/assets/try/jupyter.png" height="100" loading="lazy">
      <p>The latest web-based interactive development environment</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://jupyter.org/try-jupyter/retro/notebooks/?path=notebooks/Intro.ipynb" class="box-link">
    <h2 class="box-title" id="jupyter-notebook">Jupyter Notebook<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#jupyter-notebook" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Python logo - Launch Jupyter Notebook demo Binder" src="/assets/try/python.svg" height="100" loading="lazy">
      <p>The original web application for creating and sharing computational documents</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/voila-dashboards/voila/stable?urlpath=voila%2Ftree%2Fnotebooks" class="box-link">
    <h2 class="box-title" id="voilà">Voilà<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#voilà" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Voilà logo - Launch Violà demo Binder" src="/assets/try/voila.svg" height="100" loading="lazy">
      <p>Share insights by converting notebooks into interactive dashboards</p>
    </div>
  </a>
</section></div>
    <!-- Kernels section -->
    <div class="content content--copy">
      <h2 id="kernels">Kernels<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kernels" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
      <p>Jupyter kernels allow you to use Jupyter interfaces and tools with <b>any programming language</b>.
Below are interactive demos for a few languages to help demonstrate. You can also find
<a href="https://github.com/jupyter/jupyter/wiki/Jupyter-kernels">a community-curated list of Jupyter kernels here</a>.
</p>
    </div>
    <div class="content content--wide boxlist"><section class="box">
  <a href="https://mybinder.org/v2/gh/QuantStack/xeus-cling/stable?filepath=notebooks/xcpp.ipynb" class="box-link">
    <h2 class="box-title" id="c">C++<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#c" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="C++ logo - Launch C++ demo Binder" src="/assets/try/Cpp.svg" height="100" loading="lazy">
      <p>How to use Jupyter with C++</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/binder-examples/demo-julia/HEAD?filepath=demo.ipynb" class="box-link">
    <h2 class="box-title" id="julia">Julia<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#julia" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Julia logo - Launch Julia demo Binder" src="/assets/try/julia.svg" height="100" loading="lazy">
      <p>How to use Jupyter with Julia</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/Kotlin/dataframe/master?filepath=examples/jupyter-notebooks/titanic/Titanic.ipynb" class="box-link">
    <h2 class="box-title" id="kotlin">Kotlin<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kotlin" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Kotlin logo - Launch Kotlin demo Binder" src="/assets/try/kotlin.svg" height="100" loading="lazy">
      <p>How to use Jupyter with Kotlin</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/binder-examples/r/HEAD?filepath=index.ipynb" class="box-link">
    <h2 class="box-title" id="r">R<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#r" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="R logo - Launch R demo Binder" src="/assets/try/R.svg" height="100" loading="lazy">
      <p>How to use Jupyter with R</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/RubyData/binder/HEAD?filepath=ruby-data.ipynb" class="box-link">
    <h2 class="box-title" id="ruby">Ruby<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ruby" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Ruby logo - Launch Ruby demo Binder" src="/assets/try/ruby.png" height="100" loading="lazy">
      <p>How to use Jupyter with Ruby</p>
    </div>
  </a>
</section><section class="box">
  <a href="https://mybinder.org/v2/gh/Calysto/calysto_scheme/HEAD?filepath=notebooks/Reference%20Guide%20for%20Calysto%20Scheme.ipynb" class="box-link">
    <h2 class="box-title" id="scheme">Scheme<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#scheme" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
    <div class="box-body">
      <img class="box-logo" alt="Scheme logo - Launch Scheme demo Binder" src="/assets/try/Scheme.png" height="100" loading="lazy">
      <p>How to use Jupyter with Calysto Scheme</p>
    </div>
  </a>
</section></div>
  </div>
</article>

    </section>
    <footer class="footer">
      <section class="linklists">
        <div class="content content--wide">
        <div class="footer-links">
          <h2 id="project-jupyter">Project Jupyter<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#project-jupyter" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
          <ul><li>
                <a href="/try">
                    Try
                </a>
            </li><li>
                <a href="/install">
                    Install
                </a>
            </li><li>
                <a href="/community">
                    Get Involved
                </a>
            </li><li>
                <a href="https://docs.jupyter.org/" target="_blank" rel="noopener noreferrer">
                    Documentation
                </a>
            </li><li>
                <a href="https://blog.jupyter.org" target="_blank" rel="noopener noreferrer">
                    News
                </a>
            </li><li>
                <a href="/governance/">
                    Governance
                </a>
            </li><li>
                <a href="/security">
                    Security
                </a>
            </li><li>
                <a href="/about">
                    About
                </a>
            </li>
          </ul>
        </div>
        <div class="footer-links">
          <h2 id="subprojects">Subprojects<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#subprojects" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
          <ul><li>
              <a href="/binder">
                  Binder
              </a>
            </li><li>
              <a href="/hub">
                  JupyterHub
              </a>
            </li><li>
              <a href="https://jupyterlab.readthedocs.io/" target="_blank" rel="noopener noreferrer">
                  JupyterLab
              </a>
            </li><li>
              <a href="https://jupyter-notebook.readthedocs.io/" target="_blank" rel="noopener noreferrer">
                  Jupyter Notebook
              </a>
            </li><li>
              <a href="https://voila.readthedocs.io/" target="_blank" rel="noopener noreferrer">
                  Voilà
              </a>
            </li><li>
              <a href="/widgets">
                  Widgets
              </a>
            </li>
          </ul>
        </div>
        <div class="footer-links">
          <h2 id="follow-us">Follow us<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#follow-us" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
          <ul><li>
              <a href="https://github.com/jupyter/" target="_blank" rel="noopener noreferrer">
                  GitHub
              </a>
            </li><li>
              <a href="https://twitter.com/projectjupyter" target="_blank" rel="noopener noreferrer">
                  Twitter
              </a>
            </li>
          </ul>
        </div>
      </div>
      </section>
      <section class="footer-text">
        <div class="content content--wide">
          <img src="/assets/logos/rectanglelogo-blacktext-blackbody-blackplanets.svg" width="189" height="51" alt="Project Jupyter logo">
          <p>
              The Jupyter Trademark is registered with the U.S. Patent &amp; Trademark Office. © 2022
          </p>
        </div>
      </section>
    </footer>
    <script src="/assets/js/bootstrap-native.min.js" defer=""></script>
  
</body></html>
