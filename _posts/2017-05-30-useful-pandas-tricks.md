---
layout: post
title:  "Useful Pandas Tricks"
date:   2017-05-30 00:00:00 +0000
---

Pandas is a very effective tools for doing data manipulations.

### Import pandas library
{% highlight python %}
import pandas
{% endhighlight %}

or,

{% highlight python %}
import pandas as pd
{% endhighlight %}

### Load data from csv file
        A,B,C,D
        1,0,1,1
        1,0,0,1
        1,1,0,1

{% highlight python %}
pd.read_csv('data.csv')
{% endhighlight %}

### information content

```math
I(E) = - \log_2(p(E))
```
