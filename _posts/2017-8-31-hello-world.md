---
layout: default
title: 你好，世界
---
<h2>{{ page.title }}</h2>
<p>我的第一篇文章</p>
<p>{{ page.date | date_to_string }}</p>
{% highlight c++ %}
def show
#include<iostream>
using namespace std;

int main(){
	cout << "hello" << endl;
}
{% endhighlight %}