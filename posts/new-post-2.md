<!--
.. title: New Post 2
.. slug: new-post-2
.. date: 2018-11-17 21:33:34 UTC-05:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Write your post here.


X sim N(mu, sigma)

```python

   def sieve_of_eratosthenes():
       factors = defaultdict(set)
       for n in count(2):
           if factors[n]:
               for m in factors.pop(n):
                   factors[n+m].add(m)
           else:
               factors[n*n].add(n)
               yield n
```

