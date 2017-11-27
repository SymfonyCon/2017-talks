# [Symfony Con - Cluj 2017](https://clujcon2017.symfony.com/) talks

- All talks are in **english**.
- Comment and rate talks on [joind.in](https://joind.in/event/symfonycon-cluj-2017/schedule/list)

## Keynote

[Slides](https://speakerdeck.com/fabpot/flex)  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Decoupling an application with message queues

<dl>
  <dt>Description</dt>
  <dd>Quick response times are crucial. Time consuming tasks triggered in web requests should be executed asynchronously, if at all possible. In this talk I will give a short overview of what message queues are and then show a case study how we split up an application into smaller services and how we use message queues to coordinate the services.</dd>
</dl>

[Slides](http://davidbu.ch/slides/2017-11-16-symfonycon-messagequeues.html)  
~~Video~~

By [David Buchmann](https://connect.sensiolabs.com/profile/dbu)  
![github](icon/github.png) [@dbu](https://github.com/dbu)  
![twitter](icon/twitter.png) [@dbu](https://twitter.com/dbu)

---

## Keep calm and update your Symfony app!

<dl>
  <dt>Description</dt>
  <dd>The talk will present a real life case study of how we upgraded an enterprise application from Symfony 2.7 running PHP 5.6 to Symfony 3.4 and PHP 7.1. We will go through what was the conceived plan and what were the biggest challenges. It will be separated in 3 chapters: upgrading PHP, upgrading Symfony and achieved benefits. In the first chapter we will take a look in upgrading the PHP version and related packages, how we fixed common backward incompatible changes and what parts of our code we updated to take advantage of the new features. Also, a glimpse into what helpful tools can be used ( php7cc, phan, PhpStorm PHP 7 Compatibility Inspection). In the second chapter we discuss about upgrading from Symfony 2 and related bundles to Symfony 3, updating to the new directory structure and making code deprecation free. As in the first chapter, we will also talk about helpful tools for this step. We will wrap it up with a look on the end result and what are the achieved improvements.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Caliman Alin Adrian](https://connect.sensiolabs.com/profile/acaliman)  
![github](icon/github.png) [@adrcal](https://github.com/adrcal)

---

## Optimizing for PHP 7 - the example of Symfony

<dl>
  <dt>Description</dt>
  <dd>Symfony keeps evolving adding new features, fixing bugs and reorganizing its structure to support more and more projects. But Symfony also evolves in term of performances. This talks will detail how the PHP 7 engine works, how memory and CPU are used in the heart of PHP, how classes, objects, variables and arrays work. Then we'll see how Symfony got patched to take care of the latest optimizations brought to the PHP engine. We'll dive into OPCache, into the memory manager and the internals of PHP 7 to notice why Symfony's code has been patched in such ways that it now performs better.</dd>
</dl>

[Slides](https://www.slideshare.net/jpauli/symfonycon-2017-php7-performances)  
~~Video~~

By [Julien Pauli](https://connect.sensiolabs.com/profile/jpauli)  
![github](icon/github.png) [@jpauli](https://github.com/jpauli)  
![twitter](icon/twitter.png) [@julienPauli](https://twitter.com/julienPauli)

---

## Workflow in real life

<dl>
  <dt>Description</dt>
  <dd>In this report, I would like to talk about the integration of Symfony Workflow component, its practical use, problems and advantages of its use by the example of a corporate trouble ticket system for telecom operators. The report highlights such topics as: 1. Security - using Expression Language to control transitions. 2. Data validation - switching the entities by places is not interesting without entering additional data it validation and handling. 3. Coupling Workflow component with Tactician (by PHP League) to separate transition handling and postprocessing in small reusable classes. 4. Developing abstract factory which is elegant way to create symfony forms and command for Tactian depending on the requested transition. Examples of real cases.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Artem Dekhtyar](https://connect.sensiolabs.com/profile/artemd)  
![github](icon/github.png) [@tigokr](https://github.com/tigokr)

---

## From Legacy to Symfony

<dl>
  <dt>Description</dt>
  <dd>How can one use Symfony 4.0 and PHP 7.2 while working with a legacy application? Starting new projects on latest technology is a no-brainer but how often are you in this position? Most of the time it feels like you're stuck with what you have. In this talk I'll share my experience migrating a legacy monolith from 2007 (powering a high traffic social network) and an API-centric web application (running an e-commerce marketplace) to Symfony. Although the talk will be largely technical I'll also share some insights on ROI, non-technical benefits and pitching the idea to your boss.</dd>
</dl>

[Slides](https://speakerdeck.com/sgrodzicki/from-legacy-to-symfony-at-symfonycon-cluj-2017)  
~~Video~~

By [Sebastian Grodzicki](https://connect.sensiolabs.com/profile/sgrodzicki)  
![github](icon/github.png) [@sgrodzicki](https://github.com/sgrodzicki)  
![twitter](icon/twitter.png) [@sgrodzicki](https://twitter.com/sgrodzicki)

---

## Event Sourcing: The good, the bad and the complicated

<dl>
  <dt>Description</dt>
  <dd>Event Sourcing is a more frequently heard buzzword, but is it solving all our development problems, or is it introducing new ones? Let's see it in practice! Event Sourcing can look like an attractive solution for any of your applications, but does it actually pay off? What if it is all just buzzwords and no gain? We’ll look at how we implemented event sourcing in our own app, code-reviews.io: what made us fast; what made us super slow; what made us cry. This talk will give you a good idea of what kind of challenges you will encounter when approaching event sourcing for the first time.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Marco Pivetta](https://connect.sensiolabs.com/profile/ocramius)  
![github](icon/github.png) [@Ocramius](https://github.com/Ocramius)  
![twitter](icon/twitter.png) [@Ocramius](https://twitter.com/Ocramius)

---

## What we learned by merging two big Symfony based applications

<dl>
  <dt>Description</dt>
  <dd>Due to complex web projects we work on, there was a need for deeper integration between content management system and eCommerce solution. As eZ Platform is based on Symfony we searched for a Symfony based ecommerce solution and found Sylius as the best choice. We combined the two systems in one Symfony instance so we can integrate on much deeper level. Learn about our experience with merging and maintaining such a solution.</dd>
</dl>

[Slides](https://www.slideshare.net/IvoLukac/merging-two-big-symfony-based-applications-symfonycon-2017)  
~~Video~~

By [Ivo Lukač](https://connect.sensiolabs.com/profile/gof)  
![github](icon/github.png) [@ilukac](https://github.com/ilukac)  
![twitter](icon/twitter.png) [@ilukac](https://twitter.com/ilukac)

---

## Building your translation process

<dl>
  <dt>Description</dt>
  <dd>The Translator component is the one you learned how to use in 5 minutes and you have not thought much about it since. It just sits there in almost every project and just works. That is great, that is what a great component should do. The tricky part is how you build your development processes to work together with the translation process. You will start to notice problems when you have 4 or more languages. What other tools and services should you use? And how do you teach external translators to edit xliff files? Of course your should not force XML on non-developers. Taking the experiences learned from JMSTranslationBundle, Happyr’s translation bundles and the PHP-Translation organization; I will give you example of a few very concrete processes working with translations in a Symfony environment.</dd>
</dl>

[Slides](https://www.slideshare.net/TobiasNyholm/building-your-translation-process-82158757)  
~~Video~~

By [Tobias Nyholm](https://connect.sensiolabs.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

---

## Neo4j + PHP = <3

<dl>
  <dt>Description</dt>
  <dd>Traditional relational databases — ironically — are not that good at the complex relationships some modern applications need. Multiple joins and complex sub-queries can gradually take a toll on performance. Graph Databases, on the other hand, are all about relationships. In this talk we will look at using the popular Neo4j graph database with PHP to build efficient relational data for OmNomHub: not your average recipe site.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Michelle Sanver](https://connect.sensiolabs.com/profile/michellesanver)  
![github](icon/github.png) [@michellesanver](https://github.com/michellesanver)  
![twitter](icon/twitter.png) [@michellesanver](https://twitter.com/michellesanver)

---

## A Journey from Hexagonal Architecture to Event Sourcing

<dl>
  <dt>Description</dt>
  <dd>Event-based architectures such as Event Sourcing provide multiple benefits: scalability, complexity management, auditing, etc. However, let’s face it, getting there is quite hard. We lack skills, expertise and courage. In this talk, I’m going to show you some tips and tricks to painless evolve your current architecture towards Event Sourcing, one small step at a time. We’ll start from an Hexagonal Architecture application and we’ll end up in the Event Sourcing doors. The path that we’ll follow is: Hexagonal Architecture; Hexagonal Architecture with Domain Events; Stepping Stone Architecture (CQRS without Event Sourcing); Event Sourcing</dd>
</dl>

[Slides](https://www.slideshare.net/carlosbuenosvinos/a-journey-from-hexagonal-architecture-to-event-sourcing-symfonycon-cluj-2017)  
~~Video~~

By [Carlos Buenosvinos](https://connect.sensiolabs.com/profile/carlosbuenosvinos)  
![github](icon/github.png) [@carlosbuenosvinos](https://github.com/carlosbuenosvinos)  
![twitter](icon/twitter.png) [@buenosvinos](https://twitter.com/buenosvinos)

---

## Building a cloud-friendly application

<dl>
  <dt>Description</dt>
  <dd>The days of hand-crafted artisanal servers are long over. Modern web applications need to be able to run on many different servers without code changes. Not just different hosting providers, but different environments on the same hosting provider. Whether you're using a legacy dev/stage/prod setup or a modern branch-is-environment host, modern hosting imposes some requirements on your application design but also offers a huge potential for new and powerful tools. In this session, we'll explore some key guidelines for building a cloud-friendly application, as well as look at some architectural options that a modern hosting platform like SensioCloud enables.</dd>
</dl>

[Slides](https://www.garfieldtech.com/presentations/slides-cloud-friendly/sfconcluj2017/)  
~~Video~~

By [Larry Garfield](https://connect.sensiolabs.com/profile/crell)  
![github](icon/github.png) [@Crell](https://github.com/Crell)  
![twitter](icon/twitter.png) [@Crell](https://twitter.com/Crell)

---

## Trend analysis and machine learning in PHP

<dl>
  <dt>Description</dt>
  <dd>The world we live in is one where data is one of the most valuable assets. There are many different pieces of data we can analyse on all kind of data from analytics of user behaviour of your platform, user generated content, monitoring of exception rates, or when your core business model is to provide some kind of analytics platform. This talk will talk about how you can, in your Symfony applications, perform some simple trend analysis techniques to build models, analyse data to get useful information and spot anomalies.</dd>
</dl>

[Slides](https://speakerdeck.com/michaelcullum/trend-analysis-and-machine-learning-in-php)  
~~Video~~

By [Michael Cullum](https://connect.sensiolabs.com/profile/unknownbliss)  
![github](icon/github.png) [@michaelcullum](https://github.com/michaelcullum)  
![twitter](icon/twitter.png) [@michaelcullumuk](https://twitter.com/michaelcullumuk)

---

## A GraphQL API: from hype to production

<dl>
  <dt>Description</dt>
  <dd>This talk will not offer you the ever-lasting debate between REST and GraphQL but intends to show you some real stuff. Increasingly used by web giants like Facebook, GitHub, Pinterest, or Shopify, GraphQL has attracted my curiosity, up to the point to make me use it in production. This conference aims to detail the different problems that I encountered while implementing GraphQL, and give you a description of what it is possible to obtain (we speak of schema). We’ll also discuss the new queries paradigm : giving the client the ability to ask for exactly what one needs, including sorting, pagination without puting aside security. Eventually, we’ll explore the new way of writing data using mutations, while maintaining good performance with application cache.</dd>
</dl>

[Slides](https://spyl.net/slides/symfonycon-cluj-2017)  
~~Video~~

By [Aurélien David](https://connect.sensiolabs.com/profile/spyl)  
![github](icon/github.png) [@spyl94](https://github.com/spyl94)  
![twitter](icon/twitter.png) [@spyl94](https://twitter.com/spyl94)

---

## Making the most out of Symfony Forms

<dl>
  <dt>Description</dt>
  <dd>All web applications have forms, either simple or complex. This talk will address some of the complex scenarios with forms that change depending on the data entered and have dynamically generated fields (server and client side). Using form events and taking advantage of the form rendering flexibility can create some impressive results. The examples are based on real-life scenarios I have encountered in the five years of using the Symfony Framework.</dd>
</dl>

[Slides](https://speakerdeck.com/redecs/making-the-most-out-of-symfony-forms)  
~~Video~~

By [Mihai Nica](https://connect.sensiolabs.com/profile/redecs)  
![github](icon/github.png) [@redecs](https://github.com/redecs)  
![twitter](icon/twitter.png) [@redecs](https://twitter.com/redecs)

---

## Discovering and solving performance issues

<dl>
  <dt>Description</dt>
  <dd>Over the last few years I mostly worked with legacy PHP applications and one thing that comes up in each project is performance. Unfortunately more often than not discussion around performance issues are purely hypothetical or around micro-optimizations or the collected data is misinterpreted. In my talk I want to lay out how to effectively anticipate, identify and mitigate performance issues in a Symfony application. I want to discuss how to approach performance optimizations including micro-optimizations, some tools available to a developer for investigating and monitoring performance issues as well as some ways to improve performance, including a quick introduction to both application and HTTP-caching.</dd>
</dl>

[Slides](https://speakerdeck.com/dbrumann/discovering-and-solving-performance-issues-1)  
~~Video~~

By [Denis Brumann](https://connect.sensiolabs.com/profile/dbrumann)  
![github](icon/github.png) [@dbrumann](https://github.com/dbrumann)  
![twitter](icon/twitter.png) [@dbrumann](https://twitter.com/dbrumann)

---

## Lessons learned building the Composer internals

<dl>
  <dt>Description</dt>
  <dd>This session will dive into Composer's guts to see which choices we made worked and which ones did not. After six years and a few hundred thousand users, the Composer code has been through many iterations, problems and successes. Let's have a retrospective to see what we can learn from it.</dd>
</dl>

[Slides](http://slides.seld.be/?file=2017-11-16+Lessons+Learned+Building+the+Composer+Internals.html)  
~~Video~~

By [Jordi Boggiano](https://connect.sensiolabs.com/profile/seldaek)  
![github](icon/github.png) [@Seldaek](https://github.com/Seldaek)  
![twitter](icon/twitter.png) [@seldaek](https://twitter.com/seldaek)

---

## PHP 7 and beyond: 7.2+

<dl>
  <dt>Description</dt>
  <dd>Still desperately clinging to your PHP 5 installation? We'll take a look into the latest offerings of PHP 7 from raw performance, to exciting new language features bringing developer efficiency to a higher level. With the next release of PHP a mere two weeks away, now is the time to take the plunge and never look back.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Sara Golemon](https://connect.sensiolabs.com/profile/sgolemon)  
![github](icon/github.png) [@sgolemon](https://github.com/sgolemon)  
![twitter](icon/twitter.png) [@saramg](https://twitter.com/saramg)

---

## Mastering regex incantations

<dl>
  <dt>Description</dt>
  <dd>Regular Expressions are one of the most powerful tools for every engineer in the IT industry. Though their reputation suffers from being misused or misunderstood, they still provide vast amounts of power coming from the theory behind them. In this talk, I will provide not only the necessary knowledge to understand how they work and what powers they bring to the table but I'll also explain some of the "arcane incantations", ie. some of the very powerful but hardly known RegEx constructs.</dd>
</dl>

[Slides](https://speakerdeck.com/thunderer/mastering-regex-incantations)  
~~Video~~

By [Tomasz Kowalczyk](https://connect.sensiolabs.com/profile/thunderer)  
![github](icon/github.png) [@thunderer](https://github.com/thunderer)  
![twitter](icon/twitter.png) [@tmmx](https://twitter.com/tmmx)

---

## Webpack Encore - Pro JavaScript and CSS for Everyone

<dl>
  <dt>Description</dt>
  <dd>Ready to write an amazing front-end for your app? There are so many great tools, like React, Vue.js, module loaders, Sass, LESS, PostCSS and more. But, they all have one thing in common: you need to configure a build system before you write a single line of code! Thankfully, there's Webpack: the leading tool for processing & bundling your JavaScript and CSS. There's just one problem: configuring Webpack is tough and requires a lot of Webpack-specific knowledge. Say hello to Webpack Encore: a library built by Symfony to quickly bootstrap a sophisticated asset setup, complete with minification, SASS processing, automatic versioning, Babel support and everything you need to start writing great JavaScript quickly. In this talk, we'll also learn about using JavaScript modules, how to bootstrap a framework (like React) and other important modern practices. Give your assets a huge boost with Webpack Encore!</dd>
</dl>

[Slides](https://www.slideshare.net/weaverryan/webpack-encore-symfony-live-2017-san-francisco)  
~~Video~~

By [Ryan Weaver](https://connect.sensiolabs.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)

---

## Auditing Symfony apps

<dl>
  <dt>Description</dt>
  <dd>Often clients already have a working product that they want to improve. In these cases starting to work on the project right away may turn into a development nightmare. Therefore assessing the technical status of the product is very important. Depending on the needs of the client this can be done from several points of view : technical standards, maintainability, performance, security, etc. This talk is going to cover how can you prepare an audit of a Symfony application, what should you look out for and how can the result of the audit impact further development on the project. I will talk also about what I found to be the best tools for the job and how can you get clients to see the benefits of it.</dd>
</dl>

[Slides](https://speakerdeck.com/lenardpalko/symfonycon2017-auditing-symfony-apps)  
~~Video~~

By [Palko Lenard](https://connect.sensiolabs.com/profile/lenardpalko)  
![github](icon/github.png) [@lenardpalko](https://github.com/lenardpalko)  
![twitter](icon/twitter.png) [@lenardpalko](https://twitter.com/lenardpalko)

---

## API Platform and Symfony

<dl>
  <dt>Description</dt>
  <dd>We'll start by creating a fully-featured API in just a few minutes with API Platform, Symfony and Doctrine. The API will support pagination, data validation, access control, relation embedding, filters and error handling. It will expose many formats (JSON-LD, Hydra, JSONAPI, HAL, JSON, XML, YAML and CSV), will be documented with Swagger/OpenAPI and will have a nice UI done in React. Last but not least, the API will respond in a just few milliseconds thanks to its builtin invalidation based cache mechanism. Then, we will use the ReactJS tools provided by the API Platform to consume the exposed Hydra documentation. In a few more minutes, we will get a Material Design administration interface (a la Sonata / EasyAdmin - but 100% client-side) built with React. Finally, we'll discover 2 nice code generators to bootstrap a SPA (React, Redux and React Router) and iOS and Android mobile apps (React Native).</dd>
</dl>

[Slides](https://www.slideshare.net/coopTilleuls/api-platform-and-symfony-a-framework-for-apidriven-projects)  
~~Video~~

By [Kévin Dunglas](https://connect.sensiolabs.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Dependency Injection Component v4.0

<dl>
  <dt>Description</dt>
  <dd>The Dependency Injection component is one of the central pieces of any Symfony applications since version 2.0. Starting this winter, it has gained many new features that were needed to build the new Symfony 4 experience around Flex. While used extensively in core, can you leverage them in your own apps? Can you create a lazy iterator in Yaml? A scoped service locator? Configure auto-configuration? During this talk, I'll tell you about the new tags, interfaces or annotations that allow building powerful services. The goal: making your apps always more expressive, thus maintainable.</dd>
</dl>

[Slides](https://speakerdeck.com/nicolasgrekas/dependency-injection-component-v4-dot-0-symfonycon-cluj-2017)  
~~Video~~

By [Nicolas Grekas](https://connect.sensiolabs.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Building an Open-Source Campaign Platform for the new President of France

<dl>
  <dt>Description</dt>
  <dd>This case study will take you to the technical backdrop of Emmanuel Macron's victorious campaign in the French presidential elections of 2017. We will reveal how the En-Marche and SensioLabs teams worked closely together to develop a collaborative, Open-Source and citizen platform with PHP 7 and Symfony to structure the movement. In addition to the technical and political issues involved in this project, we'll present solutions such as continuous deployment with Docker under Kubernetes, continuous integration with Circle CI, SCRUM and Kanban project management, use of Rabbitmq, Symfony 3 new features, and more. We'll demonstrate the importance of choosing these solutions to meet the agility and scalability needs of the highlights of the campaign.</dd>
</dl>

[Slides](https://speakerdeck.com/hhamon/building-an-open-source-campaign-platform-for-the-new-president-of-france)  
~~Video~~

By [Hugo Hamon](https://connect.sensiolabs.com/profile/hhamon)  
![github](icon/github.png) [@hhamon](https://github.com/hhamon)  
![twitter](icon/twitter.png) [@hhamon](https://twitter.com/hhamon)

---

## Doctrine Performance Optimization

<dl>
  <dt>Description</dt>
  <dd>Is your Doctrine too slow or using too many resources on the server? In this presentation, you will learn the memory, I/O and CPU usage of different approaches. You will also see learn how to create proofs of concept and benchmarks to make a decision based on science instead of your gut feeling. I will even show you how to automate your performance testing.</dd>
</dl>

[Slides](https://speakerdeck.com/afilina/doctrine-performance-optimization)  
~~Video~~  
[Code](https://github.com/afilina/doctrine-perf)

By [Anna Filina](https://connect.sensiolabs.com/profile/afilina)  
![github](icon/github.png) [@afilina](https://github.com/afilina)  
![twitter](icon/twitter.png) [@afilina](https://twitter.com/afilina)

---

## Symfony at OpenSky

<dl>
  <dt>Description</dt>
  <dd>OpenSky is one of the first large ecommerce platforms to use Symfony2. The whole marketplace has been running on Symfony for many years. Over this talk we will share: how we use the framework and other PHP components; our deployment process; using Doctrine with MySQL and MongoDB; things we learned to avoid; running a large PHPUnit test suite; And more interesting tips on how our team operates with a large code base with a fully remote operation with teams across multiple continents.</dd>
</dl>

[Slides](https://www.slideshare.net/pgodel/symfonycon-cluj-2017-symfony-at-opensky)  
~~Video~~

By [Pablo Godel](https://connect.sensiolabs.com/profile/pgodel)  
![github](icon/github.png) [@pgodel](https://github.com/pgodel)  
![twitter](icon/twitter.png) [@pgodel](https://twitter.com/pgodel)

---

## A year of Symfony

<dl>
  <dt>Description</dt>
  <dd>A lot happened! 52 blog posts to help you keep up with all new things, a looooot of pull requests, 2 new versions out… Well I'm sure you missed something. Let's review what happened during last year: basically we'll see and/or discover nice new features that appeared since the last year.</dd>
</dl>

[Slides](https://speakerdeck.com/saro0h/symfonycon-cluj-a-year-of-symfony)  
~~Video~~

By [Sarah Khalil](https://connect.sensiolabs.com/profile/saro0h)  
![github](icon/github.png) [@saro0h](https://github.com/saro0h)  
![twitter](icon/twitter.png) [@Saro0h](https://twitter.com/Saro0h)

---

---

---

# Lightning Talks

## 5 new initiatives to grow the community

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

And [Lukas Kahwe Smith](https://connect.sensiolabs.com/profile/lsmith)  
![github](icon/github.png) [@lsmith77](https://github.com/lsmith77)  
![twitter](icon/twitter.png) [@lsmith](https://twitter.com/lsmith)

---

## composer.lock demystified

[Slides](http://www.naderman.de/slippy/slides/2017-11-16-SymfonyCon-composer-lock-demystified.pdf)  
~~Video~~

By [Nils Adermann](https://connect.sensiolabs.com/profile/naderman)  
![github](icon/github.png) [@naderman](https://github.com/naderman)  
![twitter](icon/twitter.png) [@naderman](https://twitter.com/naderman)

---

## Eeek. My tests are mutating

~~Slides~~  
~~Video~~

By [Caliman Alin Adrian](https://connect.sensiolabs.com/profile/acaliman)  
![github](icon/github.png) [@adrcal](https://github.com/adrcal)

---

## Simplify your application with a command bus

[Slides](https://speakerdeck.com/romaricdrigon/simplify-your-application-with-a-command-bus)  
~~Video~~

By [Romaric Drigon](https://connect.sensiolabs.com/profile/romaricdrigon)  
![github](icon/github.png) [@romaricdrigon](https://github.com/romaricdrigon)

---

## PHX - PHP syntax extension framework

~~Slides~~  
~~Video~~

By [Pascal Münst](https://connect.sensiolabs.com/profile/timesplinter)  
![github](icon/github.png) [@timesplinter](https://github.com/timesplinter)  
![twitter](icon/twitter.png) [@PascalMySelf](https://twitter.com/PascalMySelf)

---

## Sulu: Tired of fixing your CMS instead of building great applications

[Slides](https://speakerdeck.com/wachterjohannes/symfonycon-cluj-2017-batteries-included-thanks-to-symfony)  
~~Video~~

By [Wachter Johannes](https://connect.sensiolabs.com/profile/wjohannes)  
![github](icon/github.png) [@wachterjohannes](https://github.com/wachterjohannes)  
![twitter](icon/twitter.png) [@WachterJohannes](https://twitter.com/WachterJohannes)

---

## Diversity in the Symfony community

~~Slides~~  
~~Video~~

By [Lukas Kahwe Smith](https://connect.sensiolabs.com/profile/lsmith)  
![github](icon/github.png) [@lsmith77](https://github.com/lsmith77)  
![twitter](icon/twitter.png) [@lsmith](https://twitter.com/lsmith)

---

## ChubbyPHP - How to use a simple serializer

[Slides](https://slideshare.net/dominikzogg/chubbyphp-deserialization)  
~~Video~~

By [Dominik Zogg](https://connect.sensiolabs.com/profile/dominik.zogg)  
![github](icon/github.png) [@dominikzogg](https://github.com/dominikzogg)  
![twitter](icon/twitter.png) [@dominikzogg](https://twitter.com/dominikzogg)

---

## Lets talk about Sylius and ecommerce with Symfony components

~~Slides~~  
~~Video~~

By [Gabriel Udrescu](https://connect.sensiolabs.com/profile/gabiudrescu)  
![github](icon/github.png) [@gabiudrescu](https://github.com/gabiudrescu)  
![twitter](icon/twitter.png) [@gabiudrescu](https://twitter.com/gabiudrescu)

---

## Symfony Development Environment Automatio

~~Slides~~  
~~Video~~

By [Cosmin-Romeo TANASE](https://connect.sensiolabs.com/profile/tanasecosminromeo)  
![github](icon/github.png) [@tanasecosminromeo](https://github.com/tanasecosminromeo)  
![twitter](icon/twitter.png) [@tcr92](https://twitter.com/tcr92)
