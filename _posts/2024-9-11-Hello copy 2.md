---
tags: 
    - networks
    - learn
layout: post
title: التجريد والـlambda expressions
---

فلنتعلم أصول الـlambda expressions وكيف دخلت في لغات البرمجة الحديثة


<div dir="ltr" class="codeblock shadow">
{% highlight javascript linenos %}
    let dates =
        document.querySelectorAll(".date span")
            .length != 0
            ? document.querySelectorAll(".date span")
            : document.querySelectorAll(".date");
    dates.forEach((date) => {
        date.textContent = format(date.textContent);
    });
{% endhighlight %}
</div>