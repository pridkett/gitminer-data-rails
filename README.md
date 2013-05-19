gitminer-data-rails
===================

Collected by [Patrick Wagstrom](http://patrick.wagstrom.net/) &lt;<patrick@wagstrom.net>&gt;

This is a [Neo4j Database][neo4j] database containing most of the data
surrounding the [Ruby on Rails][rails] project on Github. The data were
collected in May 2012.  [GitMiner][gitminer] project. More information about
how to use the data is avaialble on the [GitMiner project page][gitminer].

understanding the data
----------------------
The best way to get a grasp of the data is to read our paper from MSR 2013, "[A Network of Rails: A Graph Dataset of Ruby on Rails and Associated Projects][paper]". It describes the data in more detail and provides a handful of [Gremlin][gremlin] queries that might be helpful for someone exploring the data.

After reading the paper you should take a look at [overview.txt][overview], which contains summary information regarding all of the vertices and edges in the dataset and covers how they're linked together. This is particularly useful if you want to know how to get from one vertex type to another.

Finally, [our presentation from MSR 2013 is available online][presentation]. Feel free to check it out.

usage rights
------------

It's just data, however it was produced under the auspices of a joint
study agreement between IBM and the University of Nebraska-Lincoln, therefore
the data are licensed are the terms of that agreement which requires that all
output be licensed under the [Apache License v2.0][license].  I'm not certain
what that means for data, but that's the rules.

If you're an academic and publish a paper using this data then a citation is
*highly* appreciated (co-authorship is even more appreciated, I can help you
make sense of the data). If you're looking for a citation use something like
this:

P. Wagstrom, C. Jergensen, and A. Sarma, “A Network of Rails: A Graph Dataset of Ruby on Rails and Associated Projects,” in Proceedings of the 2013 Working Conference on Mining Software Repositories, San Francisco, CA, 2013.

Also, [shoot me an email][mailto] so I can keep track of publications that use
this data.

[neo4j]: http://www.neo4j.org/
[rails]: https://github.com/rails/rails
[gitminer]: https://github.com/pridkett/gitminer
[license]: http://www.apache.org/licenses/LICENSE-2.0.html
[mailto]: mailto:patrick@wagstrom.net
[overview]: https://raw.github.com/pridkett/gitminer-data-rails/master/overview.txt
[paper]: https://raw.github.com/pridkett/gitminer-data-rails/master/MSR_2013_A_Network_of_Rails.pdf
[presentation]: https://docs.google.com/presentation/d/1i5b1AeBxna2JY6tTWIxetSs3WEXPzN_Tn3aetyC3cWc/edit?usp=sharing
