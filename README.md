## Introduction

My name is Tyler Baum, and I am a software developer from Albuquerque, NM. I recently completed the CNM Ingenuity Deep Dive Java + Android bootcamp, my first formal educational experience in the industry &ndash; I was an autodidact up to that point. While I'm somewhat new to the industry, I'm definitely not new to creating things that people can use and enjoy. I'm aiming to specialize in blockchain technology, but am not unwilling to branch out into other areas of the industry if the right opportunity presents itself. In service of finding new opportunities, on offer below is a sampling of what I have already done.

## Links

* [GitHub](https://github.com/AugmenTab)
* [LinkedIn](https://www.linkedin.com/in/thebaum)
* [CodeSignal](https://app.codesignal.com/profile/augmentab)
* [Résumé](/resume) - This version can be printed from the browser in a print-friendly format. You can [download a PDF file version of the page as displayed](pdf/resume.pdf) (and with functional links preserved). If you would prefer to see a more traditionally formatted resume, you can [view that here](traditional/main.pdf).

## Recently Updated Repositories
{% assign exclude = 'AugmenTab.github.io' | split: ', ' %}
{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 9 %}
  {% unless exclude contains repo.name -%}
* [{{ repo.name }}]({{ repo.html_url }})
  {%- endunless %}
{% endfor %}

## Past Projects

While no means an exhaustive list, this is a small sampling of some of my completed projects and experiments.

### Applications

* Java/Android
    * [Animals](https://github.com/AugmenTab/animals) was an Android app that we as a class developed as part of the Java + Android bootcamp. It provided a number of exercises in UI design, and makes use of a number of APIs and Google's Gson library.
    * [AlbuQuirky](https://github.com/albuquirky/albuquirky) was an Android app built as one of the group capstone projects for the Java + Android bootcamp. It is an app designed to help local area artists sell their art and handle commissions during the COVID-19 crisis (and beyond). In addition to the Room persistence library, it also makes use of a [server-side application](https://github.com/albuquirky/albuquirky-service) supported by [Hibernate](https://hibernate.org/orm/documentation/5.4/) and Google's [OAuth 2.0](https://developers.google.com/identity/protocols/oauth2). As of the round table presentation at the graduation ceremony for the Java + Android bootcamp, it was also hosted on [Digital Ocean](https://www.digitalocean.com/), with the app communicating with the server (as opposed to communicating with a server running locally). For more information, you can [view the dedicated project site](https://albuquirky.github.io/).
    * [CodeBreaker](https://github.com/AugmenTab/codebreaker-android-v2) was an Android game built as a class project in the Java + Android bootcamp. It also uses Room, Hibernate, and Google OAuth 2.0 in a [server side application](https://github.com/AugmenTab/codebreaker-service-v2) to permit players to play games over the internet as well as in a "solitaire" mode by themselves.
    * [Viral](https://github.com/AugmenTab/viral) was an Android app built as my personal Android capstone project for the Java + Android bootcamp. It is a turn-based strategy game that takes place inside of a fictional social media app. It is a data-driven game that makes use of the [Room](https://developer.android.com/topic/libraries/architecture/room) persistence library and [Leaflet](https://leafletjs.com/reference-1.7.1.html) to simulate a local area map. For more information, you can [view the dedicated project site](https://augmentab.github.io/viral/).
* JavaScript
    * [Aponia](https://github.com/AugmenTab/work-tools) was a small suite of custom-built tools I developed for a former employer. These tools were part of a major change to my department's operating procedures I suggested and assisted in implementing, which had a tremendous impact on my team's ability to organize and access information. After these changes took hold, we were able to operate at less than half our expected staffing capacity for an extended period of time without getting behind, and continue to operate without significant delays during the switch to remote work due to COVID-19.
* Python
    * [Text Embiggeninator](https://github.com/AugmenTab/text-embiggeninator) is a Python tool that converts text into BIG TEXT emojis for use in the Discord instant messaging app. It makes use of [Eel](https://github.com/samuelhwilliams/Eel) to make a simple GUI using HTML, CSS, and JavaScript.
    * [Halo Medal Scraper](https://github.com/AugmenTab/halo-medal-scraper), a simple web scraper that downloads images and logs details for the multiplayer medals from the Halo first-person shooter franchise.
    * [True Random Dice Roller](https://github.com/AugmenTab/true-random-dice-roller), a dice roller that uses the [Random.org API](https://api.random.org/features) to get true random results.
    * A number of Python games:
        * [Pong](https://github.com/AugmenTab/py-pong)
        * [Snake](https://github.com/AugmenTab/py-snake)
        * [Connect Four](https://github.com/AugmenTab/py-connect-four), with variable game board dimensions

### Websites

* [React](https://github.com/AugmenTab/react-studies)
    * [Catch of the Day](https://github.com/AugmenTab/react-studies/tree/master/wes-bos/beginner/catch-of-the-day) and [Sick Fits](https://github.com/AugmenTab/react-studies/tree/master/wes-bos/advanced/sick-fits), a pair of React websites made through the Beginner and Advanced tutorials by the incredible [Wes Bos](https://wesbos.com/about).
* [Elm](https://github.com/AugmenTab/elm-studies)
    * [Photo Groove](https://github.com/AugmenTab/elm-studies/tree/main/photogroove) is the project site built by following along with [Richard Feldman](https://github.com/rtfeldman)'s excellent book, [Elm in Action](https://www.amazon.com/Elm-Action-Richard-Feldman/dp/1617294047/ref=sr_1_1?dchild=1&keywords=elm+in+action&qid=1610332687&sr=8-1).
* Hugo
    * [BaumBuilds](https://www.baumbuilds.com/) is an e-commerce website made for my dad's small business. It served as my first foray into Hugo, and was made by adapting a purchased Bootstrap theme to Hugo partials and reaching out to [Snipcart](https://docs.snipcart.com/v3/) to handle the credit card processing and digital goods distribution.
    * [Kangen Krew](https://kangenkrew.com/) was done as a freelance project for a local sales team selling Enagic alkaline water machines. It was also built using Hugo, with [DatoCMS](https://www.datocms.com/docs) serving as the content management system, allowing the client to modify the website copy and graphic assets themselves without having to know anything about coding.
* JavaScript/Other
    * [Anoxis Gate](https://anoxisgate.com/), a website that will eventually serve as the distribution platform for third-party tabletop roleplaying content published by a group I participate in. I used it as an opportunity to play around with animations in CSS, both by using established animations (the twinkling starry night background) and experimenting with my own (the scrolling gradient text and buttons). Currently, it is simply a placeholder site that allows interested parties to sign up for the newsletter, which is managed through [MailChimp](https://mailchimp.com/developer/). In the future, it will likely use either Elm or Gatsby.

## Future Plans

Even after classes end and gainful employment is found, the learning never ends (thankfully!). I am always seeking out new ideas and tools to better tackle my goals, and to that end,I make use of personal free time to add a number of skills to my repertoire. Some of those on my radar at the moment include:

* [Haskell](https://www.haskell.org/): This first started out as a way to capitalize on my current knowledge of Elm, to extend some of the same guarantees offered by Elm to other applications. It has instead become much more; in combination with Elm, Haskell has taught me a lot about myself as a programmer - namely, that I prefer working with strongly-typed static languages, and that I prefer functional languages. Haskell has also emerged as a (perhaps unlikely, considering its popularity, or rather lack thereof) favorite in blockchain technology. It is quickly becoming one of *my* favorites, if nothing else, and I'm excited to begin using it for some planned projects, ranging from servers to blockchain to even small video games.
* [Clojure](https://clojure.org/): My experience with Java, Elm, and Haskell have made me prefer static over dynamic languages, but there's a lot to Clojure that draws me to it. In particular, it's the design philosophy and the determination of Rich Hickey to stick to that. Refusing to implement requested features because he feels they would just add bloat to the language is, at least in my eyes, a wise choice. My experience with Java should also give me a small but not insignificant advantage due to Clojure's [Java Interop](https://clojure.org/reference/java_interop).
* [Solidity](https://docs.soliditylang.org/en/v0.8.2/) and [Vyper](https://vyper.readthedocs.io/en/stable/): For someone looking to get into blockchain, knowing one of these EVM languages seems to be a requirement. Out of the two, I definitely prefer Vyper: it's far simpler and easier to deal with, and Solidity is based on JavaScript, a language I don't much care for. I figure that knowing both will be more secure, though I'm definitely not shy about my preference for the latter.
* [Dart](https://dart.dev/) and [Flutter](https://flutter.dev/): Simply put, the ability to deploy to both iOS and Android greatly outweighs the missing features. I have a number of projects planned for mobile, and I would rather deploy to both platforms using one tool set and language than two or more, especially with the possible (eventual) release of [Google Fuschia](https://fuchsia.dev/fuchsia-src/development).
* [Prolog](https://www.swi-prolog.org/): This one is more of a curiosity than a language I intend to make use of in projects, though it does have some utility to me through Clojure's [core.logic](https://github.com/clojure/core.logic) library that is based heavily on Prolog.
* [Dyalog APL](https://www.dyalog.com/): Moreso even than Prolog, APL is a language that finds its way into my future plans out of curiosity alone. I have seen some incredible code golf solutions using APL and I think it could be valuable as an educational language. While I can't imagine finding many jobs with it, I can at least use it to justify a recent interest in custom programmable mechanical keyboards, if nothing else.
* Smalltalk: I know I talked a big game earlier about not liking object-oriented or dynamic languages, but somehow, yet another has managed to capture my attention. Why? Again, curiosity. There's something endearing about a language [that can fit on a postcard](https://richardeng.medium.com/syntax-on-a-post-card-cb6d85fabf88). I even have some ideas for projects that could benefit from Smalltalk, and despite the original Smalltalk-80 being dynamic, there are some versions that implement optional static typing, like [Strongtalk](http://strongtalk.org/).
* [Rust](https://www.rust-lang.org/): My main interest in Rust is for low-level applications; I believe that it will soon begin to catch on for use in embedded systems, and possibly even overtake C. While I'm not currently looking to get into embedded systems, I do have a couple project ideas that might require it. 
* [Go](https://golang.org/): Go interests me as a language for servers, but its ease of use may inspire me to replace Python as my current "rapid prototyping" language for quickly developing proofs of concept on project ideas.
* [Erlang](https://www.erlang.org/) / [Elixir](https://elixir-lang.org/): These two round out my future language learning plans. They're seeing a lot of use in blockchain, and are famous for use in telecom should I ever go that route.