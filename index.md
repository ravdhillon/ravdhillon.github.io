### Home | [Blog](/blog) | [Resume](/resume) | [Portfolio](/portfolio)
---
<div class="profile-summary">        
    {% if site.logo %}
        <img src="{{site.logo | relative_url}}" alt="Logo" style="border-radius: 50%"/>
    {% endif %}

    <p class="headline">{{ site.headline | default: site.github.project_tagline }}</p>
    <p class="profile">{{ site.profile }}</p>
    {% if site.github.is_project_page %}
    <p class="view"><a href="{{ site.github.repository_url }}">View the Project on GitHub <small>{{ site.github.repository_nwo }}</small></a></p>
    {% endif %}

    {% if site.github.is_user_page %}
    <p class="view"><a href="{{ site.github.owner_url }}">View My GitHub Profile</a></p>
    {% endif %}

    {% if site.show_downloads %}
    <ul class="downloads">
        <li><a href="{{ site.github.zip_url }}">Download <strong>ZIP File</strong></a></li>
        <li><a href="{{ site.github.tar_url }}">Download <strong>TAR Ball</strong></a></li>
        <li><a href="{{ site.github.repository_url }}">View On <strong>GitHub</strong></a></li>
    </ul>
    {% endif %}
</div>
<div class="content">
    <span class="about-me">ABOUT ME</span>
    <br />
    I am a seasoned Software Engineer experienced in building Enterprise SAAS application. With the data shift paradigm, I have upscaled my skills towards Machine Learning domain.
</div>
