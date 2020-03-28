
公告, 文宣, 資訊, 建言, 活動, 通知 To inform, to service, to outreach, to link and to defend our rights, values and justice. 
A bilingual bridge

<li><a href="http://classic-blog.udn.com/usakmt" > usakmt blog </a></li>

# Home

# post

<article class="post h-entry" itemscope itemtype="http://schema.org/BlogPosting">

<header class="post-header">
<h1 class="post-title p-name" itemprop="name headline">{{ page.title | escape }}</h1>
<p class="post-meta">
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
<time class="dt-published" datetime="{{ page.date | date_to_xmlschema }}" itemprop="datePublished">
{{ page.date | date: date_format }}
</time>
{%- if page.modified_date -%}
~ 
{%- assign mdate = page.modified_date | date_to_xmlschema -%}
<time class="dt-modified" datetime="{{ mdate }}" itemprop="dateModified">
{{ mdate | date: date_format }}
</time>
{%- endif -%}
{%- if page.author -%}
• {% for author in page.author %}
<span itemprop="author" itemscope itemtype="http://schema.org/Person">
<span class="p-author h-card" itemprop="name">{{ author }}</span></span>
{%- if forloop.last == false %}, {% endif -%}
{% endfor %}
{%- endif -%}</p>
</header>

<div class="post-content e-content" itemprop="articleBody">
{{ content }}
</div>

{%- if site.disqus.shortname -%}
{%- include disqus_comments.html -%}
{%- endif -%}

<a class="u-url" href="{{ page.url | relative_url }}" hidden></a>
</article>
# Civic Watch Wiki
<li><a href="https://github.com/uskmt/Civic-Watch/wiki"> Civic Watch Wiki </a></li>




<div class="footer-col-wrapper">
<div>Title: Civic Watch Blog </div>
<div>Author: USAKMT GitHub User</div>
<div>Email: usakmt@gmail.com</div>
<div>Description: Civic Watch blog</div>
<div>Github_username:  USKMT</div> 
<div class="footer-col">
