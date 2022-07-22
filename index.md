<!-- HEADER -->
<div id="header_wrap" class="outer">
    <header class="inner">
      <a id="forkme_banner" href="{{ site.github.repository_url }}">View on GitHub</a>
      <h1 id="project_title">{{ site.title | default: site.github.repository_name }}</h1>
      <h2 id="project_tagline">{{ site.description | default: site.github.project_tagline }}</h2>
      {% if site.show_downloads %}
        <section id="pages">
          <a class="about page testing" href="https://disease-psa.github.io/PSA-webpage/about">go to about page</a>
          <a class="Also about page testing" href="./about">
          also go to about page</a>
          <a class="tar_download_link" href="{{ site.github.tar_url }}">Download this project as a tar.gz file</a>
        </section>
      {% endif %}
      {% include nav.html %}
    </header>
</div>

### Testing 

This is some text. 

This is a link:
[Link Text](https://disease-psa.github.io/PSA-webpage/about)

<a href="./about">Go to next page</a>


<details open>
<summary>Want to ruin the surprise?</summary>
<br>
Well, you asked for it!
</details>


__

# A collapsible section with markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>