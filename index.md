### Welcome to _Writing for Future_ ! 💙


Here you can find abundant resources related to <a href="https://gallifrey23.github.io/technical-writing.html">technical writing</a>, <a href="https://gallifrey23.github.io/English-teaching.html">English teaching</a> and <a href="https://gallifrey23.github.io/translation.html">translation</a>
compiled by an experienced English teacher who is currently striving to become a technical writer in China. 

ℹ️**NOTE**:   
The resources here are mainly for English/Chinese speakers, though some of the links may provide other Language option in their own websites. This website is still under active development and for personal reference only. 

If you are interested to know more about me, click [here](https://gallifrey23.github.io/about-me.html).  
If you have any questions or suggestions，feel free to [contact me](https://gallifrey23.github.io/contact.html).  
If you are looking for someone to produce clear technical documentation for your products or service, feel free to check out my [CV](https://) and find me through any platform that is convenient for you.  

{% for tag in site.tags %}
  <h2>{{ tag[0] }}</h2>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

