---
layout: page
title: Uncovering coordinated networks on social media
description:
tags: manipulation, misinfo
image: assets/img/research/uncover.png
img_alt: Schema of the framework
importance: 1
category: work
related_publications: pacheco2021uncovering
bibliography: uncover.bib
---

We introduce a general, unsupervised network-based methodology to uncover social media coordinated campaigns. The framework is then tested on five case studies using Twitter data from diverse contexts: U.S elections, Hong Kong protests, the Syrian civil war, and cryptocurrency manipulation.

This post gives a summary about our work on Uncovering inauthentic coordinated actors on social media <d-cite key="pacheco2021uncovering"></d-cite> <a href= "https://ojs.aaai.org/index.php/ICWSM/article/view/18075">

<a href="https://slate.com/technology/2020/07/coordinated-inauthentic-behavior-facebook-twitter.html"> <b> Coordinated campaigns </b></a> are used to manipulate social media platforms and influence their users, a critical challenge to the free exchange of information. 
Our paper introduces a general, unsupervised, network-based methodology to uncover groups of accounts that are likely coordinated. The proposed method uncovers coordination networks based on arbitrary behavioral traces shared among accounts. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/research/uncover.png" title="Schema of the framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Detection framework
</div>

We present five case studies of influence campaigns:

1. We examine accounts swapping identities (Twitter handles) to avoid detection. Examples include fake accounts that impersonate pro- and anti-trump campaigns to collect fraudulent donations.

2. Accounts that share suspiciously similar sets of images were used to influence online discussions around Hong Kong protests.

3. Some users knowingly or unknowingly "donate" their credentials to apps controlled by campaigns, which then post on their behalf. Accounts involved in this "astroturfing" were detected because they post identical long sequences of hashtags. 

4. In the Syrian civil war, coordinated accounts were used in disinformation campaigns targeting the White Helmets. We detected them because they displayed suspiciously (unlikely) similar retweeting patterns.

5. Finally, coordinated networks of inauthentic accounts are widely used in cryptocurrency pump-and-dump schemes, a type of fraud that manipulates prices by creating the false appearance of online chatter. We detect these accounts because they tweet at the same time.