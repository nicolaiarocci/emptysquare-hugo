+++
type = "page"
title = "Black Pipe Testing"
date = "2015-10-11T18:24:49"
description = "A series of articles on black-box testing networked applications."
category = []
tag = ["testing", "best"]
enable_lightbox = false
thumbnail = "lower-east-side-pipes@240.jpg"
draft = false
disqus_identifier = "561adf91539374099687d6ed"
disqus_url = "https://emptysqua.re/blog/561adf91539374099687d6ed/"
+++

<p><a href="https://www.flickr.com/photos/emptysquare/477797865"><img style="display:block; margin-left:auto; margin-right:auto;" src="lower-east-side-pipes.jpg" alt="Pipes" title="Pipes" /></a></p>
<p>In this series of articles I argue that "black box" testing is insufficient to validate a networked application. Such a program has two ends that take inputs and provide outputs: one is its public API, but the other is its communication over the network. Only by treating it as a black pipe can we test both surfaces.</p>
<ul>
<li><a href="/black-pipe-testing/">Black Pipe Testing: Preface</a></li>
<li><a href="/black-pipe-testing-pymongo/">Testing PyMongo As A Black Pipe</a></li>
<li><a href="/mockupdb-test-libmongoc-mongodb-c-driver-python/">MockupDB: Testing The MongoDB C Driver With Python</a></li>
<li><a href="/libmongoc-black-pipe-testing-mock-server/">Black-Pipe Testing A Connected Application In C</a></li>
<li><a href="/test-mongodb-failures-mockupdb/">Testing MongoDB Failure Scenarios With MockupDB</a></li>
<li><a href="/black-pipe-testing-in-summary/">Generalizing the black pipe idea to other connected programs</a></li>
</ul>