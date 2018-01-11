# slack-emoji
Let's build a library of slack emoji!

![Alt text](/gif/pedro.gif?raw=true "Optional Title")

All emoji meet Slack's max file sizes and dimentions.
* 128px x 128px
* 64K

# PRs welcome
Anything goes.

[![ghit.me](https://ghit.me/badge.svg?repo=TheBox193/slack-emoji)](https://ghit.me/repo/TheBox193/slack-emoji)

{% for image in site.static_files %}
    {% if image.path contains 'gifs' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="Slack emoji" />
    {% endif %}
{% endfor %}
