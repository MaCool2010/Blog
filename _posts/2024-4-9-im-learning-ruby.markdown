---

layout: post

title: "I'm learning Ruby"

date: 2024-4-9 18:49:55 -0600

categories: programming

---
I'm learning Ruby, and it's really fun. Here are some differences I've noticed between Ruby and Python so far.

{% highlight ruby %}# hello world in Python   
print("hello")       # hello world in Ruby   puts "hello" # prints with new line   print "hello" #does not make new line{% endhighlight %}

It's interesting because in Python, `print()` defaults to end with `"\n"`. This is the new line character. Adding `end=' '` would end with a space instead.  
In Ruby, `puts` ends with a `"\n"`, but `print` does not. I'm not sure if this is a better way than Python, but it's an interesting difference.

Ruby also has `unless`. It's the oposite of an if statment.

  {% highlight python %}#Python     hp = 0     if not hp == 0:       print("alive") {% endhighlight %}        
   {% highlight ruby %}#Ruby     hp = 0          unless hp == 0       puts "alive"     end{% endhighlight %}    

Those are just somethings I've found while tinkering with Ruby.
