---
title: Webmasterism
---

Hello {{ 'tobi' | upcase }}

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

{% highlight php %}
<?php
	echo "Teste";
?>
{% endhighlight %}

<ul>
{% for t in site.categories[page.category] %}
    <li>{{ t.title }}</li>
{% endfor %}
</ul>

{{ BASE_PATH }}{{ ASSET_PATH }}