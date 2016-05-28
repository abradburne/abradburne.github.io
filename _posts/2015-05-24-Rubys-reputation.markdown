---
layout: single
title: Ruby's Reputation
---

### {{ page.title }}

[This blog post](http://hawkins.io/2015/05/the-ruby-community-the-next-version/) by Adam Hawkins stuck a chord with me. The current state and the trend of Rails as an industry has been on my mind a lot recently.

In ten short years we’ve gone from the ’[How to build a blog in 15 minutes’ demo](https://www.youtube.com/watch?v=Gzj723LkRJY)  (wups!) to it becoming a major part of the web infrastructure and the basis of tens (hundreds?) of thousands of careers - mine included. It’s simply mind-blowing how far we’ve come. And it’s happened because of the sheer hard work and dedication of a (relatively) small number of individuals who are obsessed with making web development better, smarter and more fulfilling and rewarding.

But with the massive growth of Rails comes a huge responsibility for us as developers who build and maintain Rails apps, and even more so those of us that train and mentor upcoming Rails developers.

I’m sure anyone who has been working with Rails for any amount of time has inherited apps with absolutely enormous Gemfiles. Of course, Rails itself is just a collection of gems, but when auditing these applications it seems to be also guaranteed that there will be numerous out-of-date and abandoned gems, gems that are essentially one-liners or monkey patches, completely untested (or worse, _badly_ tested) gems, or very worryingly, gems that appeared new and shiny - often with too-clever-for-their-own-good DSLs - that have influenced the design and architecture of the entire application so much that removing them would require major rewrites (how’s your test coverage looking?)

This reflects very badly on Rails as a whole and does serious damage to the reputation of Ruby and Rails developers and, more seriously, Rails and Ruby itself.

How did we get here and what do we do to begin to improve things?

I think part of the reason we arrived as this point is that Ruby and Rails make it so easy to play! In that way they’ve somewhat been a victim of their own success. I firmly believe that play is the absolute best way to learn and experimentation with new techniques is essential to becoming a better developer. But being a developer for a client (whether it’s as a freelancer, contractor or employee) carries large responsibilities. As developers who care about the products we build, the happiness and success of our clients, and also the reputation of Ruby, Rails and Web Developers, we need to ensure that we both practice and preach good, responsible development. That means taking responsibility for the code you write and also for the code you include.

Just because there’s a Gem that appears to solve your problem doesn’t mean you should immediately add it to your project. Read the code, read the tests, understand how it works, what it does, what it _doesn’t_ do, what dependencies it has, how well it is supported, is the developer responding to issues and pull requests? And very importantly, consider how difficult it would be to remove it. If it is going to change the way the application is coded in ‘clever’ ways, it may not be a good choice. Carefully consider all of these things before dropping it into your Gemfile.

Ask yourself how you think the problem should be solved. If you used it in an application, is it's use clear and explicit? When you've moved on from the project and some poor soul has inherited your code, are the new developers going to understand what's happening, or are they going to start checking git logs and cursing your name?

We need to consider how we encourage responsible development practices in people just starting out in Rails development while also not discouraging play and experimentation.

I was recently speaking with a CEO of a successful, rapidly growing company whose business is based around a large Rails app. Up to this point, Rails has delivered on all of it’s promises, allowing him to get the company to where it is now. But now, development choices that seemed innocuous a long time ago are beginning to impede the company’s ability to develop new features and test new business ideas. This is most definitely _not_ the first time I’ve heard exactly this problem.

As I said earlier, this is beginning to impact the reputation of Ruby and Rails developers. Maybe my concern about this is just me being selfish, but if Rails gets a bad name, by affiliation I do too. Ruby is better than this. Rails is better than this. WE are better than this.

I fully support all of the points Adam makes in his post. If you are a Rails developer, I _highly_ recommend you read it and consider the suggestions. But _please_ don’t stop playing, experimenting and, most importantly, _enjoying_ working in Ruby.  
