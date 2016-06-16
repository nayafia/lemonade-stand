# A handy guide to making money in open source.
*"I do open source work, how do I get paid for it?"*

Below I've listed every way I know of that people get paid for open source work, roughly ordered from small to large. Each funding category links to several real examples. (Wherever possible, I've tried to link to a useful article or page instead of just a homepage.)

The categories are not mutually exclusive. For example, a project might have a foundation but also use crowdfunding to raise money. Someone else might do consulting and also have a donation button. Etc. The purpose of this guide is to provide an exhaustive list of all the ways you can get paid, so that you can figure out what works best for you.


---


# Table of Contents
1. [Donation button](#donation-button)
2. [Bounties](#bounties)
3. [Crowdfunding (one-time)](#crowdfunding-one-time)
4. [Crowdfunding (recurring)](#crowdfunding-recurring)
5. [Advertising & sponsorships](#advertising--sponsorships)
6. [Get hired by a company to work on project](#get-hired-by-a-company-to-work-on-project)
7. [Start a project while currently employed](#start-a-project-while-currently-employed)
8. [Grants](#grants)
9. [Consulting & services](#consulting--services)
10. [Open core & paid versions](#open-core--paid-versions)
11. [Managed or hosted services](#managed-or-hosted-services)
12. [Foundations & consortiums](#foundations--consortiums)
13. [Venture capital](#venture-capital)

APPENDIX: [Contributing to this guide](#contributing-to-this-guide) // [License & attribution](#license-and-attribution)


## Donation button

#### Pros
* Few strings attached
* Little work involved: "set it and forget it"

####Cons
* Usually not much money unless you have dedicated fundraising efforts
* Need a legal entity to donate to (ex. [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com) are fiscal sponsors for this purpose). Harder for individuals or international donations to manage
* Sometimes not clear who “deserves” money in a project or how it gets distributed

####Case Studies
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)

##Bounties

####Pros
* Open to community participation
* Money is tied to doing specific work (more like paying for service than donations)
* Especially popular for security work

####Cons
* Can create perverse incentives in a project (low quality PRs, distracting priorities)
* Usually not much money per bounty (~<$500)
* Doesn’t provide recurring revenue

####Case Studies
* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

##Crowdfunding (one-time)

####Pros
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Kickstarter](https://kickstarter.com/)

####Cons
* Lots of work involved to market campaign
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$50K for one time)
* Companies not always comfortable donating to campaigns

####Case Studies
* [Rvm](https://www.bountysource.com/teams/rvm/fundraiser)
* [Django](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [CPAN](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)

##Crowdfunding (recurring)

####Pros
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

####Cons
* Harder to get commitments to recurring donations (often requires preexisting brand/reputation)
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$1-4K monthly)
* Companies not always comfortable donating to campaigns

####Case Studies
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)

##Advertising & sponsorships

####Pros
* Business model aligned with something people are willing to pay for

####Cons
* Need large enough audience to justify sponsorships
* Need to manage trust and transparency with user base (ex. no tracking)
* Can be a lot of work to find and manage clients

####Case Studies
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

##Get hired by a company to work on project

####Pros
* Taps into those who have resources (i.e. companies)
* Can be well-aligned with company needs
* Steady income

####Cons
* Usually involves “getting lucky”: no clear, repeatable path to finding this arrangement
* Project already needs to be well-known and used
* Person not contributing to company’s bottom line, which makes them expendable
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

####Case Studies
* [Hewlett-Packard and Python packaging](https://twitter.com/dstufft/status/594119386333609984)
* [Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [ManageIQ and Ruby, Rails](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Joyent and Node.js (opens a YouTube video)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

##Start a project while currently employed

####Pros
* Freedom to test new ideas without worrying about salary
* Can be well-aligned with company needs
* Suitable for newer, experimental ideas

####Cons
* Need to do it as a side project or be approved to work on it during salaried time
* Risk of undue company influence
* Can lead to complicated governance later down the line

####Case Studies
* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)

##Grants

####Pros
* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

####Cons
* There aren’t many software-related grantmakers (philanthropic, gov’t, corporate)
* Grants are finite. Still need to find sustainability beyond the life of a grant

####Case Studies
* [Dat](https://usopendata.org/)
* [Urllib3 and Stripe Open-Source Retreat](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django and Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

##Consulting & services

####Pros
* Business model aligned with something people are willing to pay for

####Cons
* Consulting requires human power, doesn’t scale well (except for rare outliers)
* Business needs can distract from writing code or other tasks related to the project itself
* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay for related services

####Case Studies
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

##Open core & paid versions

####Pros
* Business model aligned with something people are willing to pay for
* Can scale well if successful

####Cons
* Need to have something you can charge for (which often means making certain features exclusive)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy

####Case Studies
* [Sidekiq](http://sidekiq.org/)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)

##Managed or hosted services

####Pros
* Can build community around open project and make money off of services for hosting
* Allows open source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

####Cons
* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* Same “Two tiers” of product support as Open Core and paid services

####Case Studies
* [Wordpress Engine](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Gitlab](http://gitlab.com)


##Foundations & consortiums

####Pros
* Neutrality. Foundation protects the code and helps steward community
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

####Cons
* Only really worth it for big projects
* Difficult to set up for IRS reasons (many do 501c6 instead of 501c3), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

####Case Studies
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

##Venture capital

####Pros
* Institutional support can be helpful for growing a business
* Large amounts of capital available

####Cons
* Venture capital comes with expectations of an exit (i.e. returning the money to investors at a multiple). History suggests this is structurally difficult to achieve for open source businesses
* Venture capital can change motivations and distract from priorities

####Case Studies
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)

---

### Contributing to this guide
I wrote up this guide to aggregate knowledge off the top of my head, but I'm not planning to make major contributions or changes. I recognize the pros/cons are somewhat subjective, but they reflect my views.

If something is factually incorrect (especially with a case study example), I welcome your edits. Also, if there's a category you know of that I missed, I would also welcome that addition.

### License and attribution
This guide is available under the Creative Commons CC0 1.0 License, meaning you are free to use it for any purpose, commercial or non-commercial, without any attribution back to me (public domain). If you do use it, I'd love to hear about it! (Find me here: [@nayafia](http://twitter.com/nayafia)) But you are in no way required to do so.
