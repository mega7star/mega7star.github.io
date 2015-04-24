---
layout: post
title: Hello world :)
---

# Это мое первое сообщение asdasdasd


это пример кода
messsds


sgdgsdgssgdsgsdg
sd
g
sg
sd
g
sg
sd

{% highlight js %}
// try innerHTML approach
var parentTag = this.NODEMAP[elementName] || 'div';
var parentElement = document.createElement(parentTag);
try { // prevent IE "feature": http://dev.rubyonrails.org/ticket/2707
parentElement.innerHTML = "<" + elementName + "></" + elementName + ">";
} catch(e) {}
var element = parentElement.firstChild || null;
// see if browser added wrapping tags
if(element && (element.tagName.toUpperCase() != elementName))
element = element.getElementsByTagName(elementName)[0];
// fallback to createElement approach
if(!element) element = document.createElement(elementName);
// abort if nothing could be created
if(!element) return;
{% endhighlight %}


