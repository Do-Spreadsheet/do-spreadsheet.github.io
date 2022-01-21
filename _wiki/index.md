---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
regenerate: true
---

## wiki items

* [[from-Obsidian-github]]
* [[하위 개념 문서 연결 테스트]]
* [[하위 테스트2]]
* [[vimwiki-obsidian sync]]
* [[히스토리 관리]]
* [[how-to]]

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public != false %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

