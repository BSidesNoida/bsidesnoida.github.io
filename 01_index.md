---
title: Home
layout: default
year: 2024
permalink: /
---

# [+]--> What's BSidesNoida?

BSides is a community organized series of events all over the world promoting independent security research and education as well as discourse and collaboration within the community. We think it's important to have a BSides in Noida as these events have spread globally by now and are an important source of input to the information security community (more information on what Bsides events are and how they're organized is available at [securitybsides.com](http://www.securitybsides.com)).

Bsides usually go hand-in-hand with a lot of tracks. As these events are free and have less of a commercial or academic conference atmosphere than a meetup-atomos, many people just come to talk to old friends, get new perspectives, and chat with people they've never met before. Of course, there are always great talks and workshops, and that's the main focus of every BSides event!

# [+]--> [Become a Member](https://nas.io/bsides-noida) 


# [+]--> Socials

You can find us on the following social media sites:

[X formerly known as Twitter](https://twitter.com/BSidesNoida)

[Instagram](https://www.instagram.com/bsidesnoida/)

[Linkedin](https://www.linkedin.com/company/bsidesnoida/)

[Commudle](https://www.commudle.com/communities/security-bsides-noida)


# [+]--> News

{% for news_entry in site.data.bs_2024.news %}
### [{{ news_entry.timestamp }}]: {{ news_entry.title }}
{{ news_entry.content }}
{% endfor %}


# [+]--> Event details

TBD


# [+]--> Tickets

[TBD](#)


#### Location

TBD


#### Cost

Oops! CMA is on holiday...


#### What's BSides

> "Each BSides is a community-driven framework for building events for and by information security community members.  The goal is to expand the spectrum of conversation beyond the traditional confines of space and time.  It creates opportunities for individuals to both present and participate in an intimate atmosphere that encourages collaboration. It is an intense event with discussions, demos, and interaction from participants. It is where conversations for the next-big-thing are happening."
-- [Security Bsides](http://www.securitybsides.com)

...

> "BSides is a framework for organising and holding security conferences. The concept began in the US in 2009 with Mike Dahn, Jack Daniel, and some others because the CFP for Blackhat Vegas or DEF CON was oversubscribed and those unable to present decided to hold their own conference on the 'b side'. Now, many have been arranged in several countries throughout the world. BSides has come to be known as a 'conference by the community for the community'. Events are generally free to attend and rely on sponsorship to pay for the venue and other costs and are run as not-for-profit. [...]  Because the events of B-Sides offer smaller, more intimate networking atmospheres and breakout discussions, they foster strong audience participation and overall group interaction."


#### Volunteers

You want to volunteer? Get in touch with us [via twitter](https://twitter.com/BSidesNoida), [via Instagram](https://instagram.com/BSidesNoida) or be old fashioned and send us an e-mail to [info@bsidesnoida.in](mailto:info@bsidesnoida.in).


#### Tag for Twitter, Instagram, Linkedin etc

Please use [#BSidesNoida](https://twitter.com/search?q=BSidesNoida) for content related to this event.


#### Crew

* {% for member in site.data.bs_2024.crew %} [{{ member.name }}]({{ member.url }}) {% endfor %}
* ..and anonymous others
