## Introduction

After nearly three years of poking and proding at code, I finally decided to try and make it my new career by taking the plundge into the CNM Ingenuity Deep Dive Coding Bootcamp's Java + Android program. Now that I have completed that course, I'm looking to add to my experience, and in service of that, a sampling of what I have already done is on display below.

## Links

* [LinkedIn](https://www.linkedin.com/in/thebaum)
* [Résumé](/resume) - This version can be printed from the browser in a print-friendly format. You can [download a PDF file version of the page as displayed](pdf/resume.pdf) (and with functional links preserved).

## Recently Updated Repositories
{% assign exclude = 'AugmenTab.github.io, viral, codebreaker-service, room-schema-parser, codebreaker, codebreaker-android-v2, codebreaker-service-v2' | split: ', ' %}
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
    * [Anoxis Gate](https://anoxisgate.com/), a website that will eventually serve as the distribution platform for third-party tabletop roleplaying content published by a group I participate in. I used it as an opportunity to play around with animations in CSS, both by using established animations (the twinkling starry night background) and experimenting with my own (the scrolling gradient text and buttons). Currently, it is simply a placeholder site that allows interested parties to sign up for the newsletter, which is managed through [MailChimp](https://mailchimp.com/developer/). In the future, it will likely use either Elm, Hugo, or Gatsby.

## Future Plans

Even after classes end and gainful employment is found, the learning never ends (thankfully!). In addition to further developing the skills gained through the Deep Dive bootcamp, I intend to make use of personal free time to add a number of languages, frameworks, and other skills to my tool box. Some of these include:

* [Haskell](https://www.haskell.org/) to capitalize on my current knowledge of Elm, and to be able to provide some of the same guarantees offered by Elm in other applications
* [Clojure](https://clojure.org/), since knowing Java will give me an advantage due to Clojure's [Java Interop](https://clojure.org/reference/java_interop) 
* [Dart](https://dart.dev/) and [Flutter](https://flutter.dev/) to continue improving my app-development skills (and maybe in anticipation of the possible release of [Google Fuschia](https://fuchsia.dev/fuchsia-src/development))
* [C#](https://docs.microsoft.com/en-us/dotnet/csharp/) to capitalize on my current knowledge of Java
* [Gatsby](https://www.gatsbyjs.com/docs/) for more front-end development flexibility
* [Rust](https://www.rust-lang.org/), [Go](https://golang.org/), and [Erlang](https://www.erlang.org/) for their exemplary concurrency models and the wide range of applications in which they excel