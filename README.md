# Curriculum Vitae

## Guilherme Silveira dos Santos

- From: Florianópolis, BR
- Living in: Berlin, DE
- Email: xguiga@gmail.com
- Phone: +49 (173) 979-9383

## Summary

I'm a Computer Engineer since 2011 but I started coding a long time before that. I consider myself a self-learner, who is always looking for new technologies, usually, my learning process is very quick. I have started to study PHP at home since I was a teenager what gave me good knowledge to develop several web applications. During the college and internships, I learned other programming languages, such as C, C++, Java, and Lua, and of course could improve myself with other skills. In 2015 I started to work with Go and it's been my main programing language since then.

I've already contributed to many open-source projects like EFL - Enlightenment Foundation Libraries, Zend Framework, Elastic (Elasticsearch client fo Go), gRPC-Gateway, and other small libraries in Go, PHP, and JavaScript. I really like to work with open-source projects and I usually do it in my spare time. I had the opportunity to work with TDD from 2009 to 2013 but write unit test still part of my daily basis.

I've built several projects over the years, some of them are still active nowadays, for example [Giox](http://giox.com.br) and [Patrimoniando](https://patrimoniando.com). Those projects helped me to become an experienced Web Developer and DevOps, also taught me how to listen to my customers and how to break down bigger problems. Apart from the projects, I've worked in companies with several different technologies and it made me an open-minded developer, with a can-do attitude and a good interpersonal relationship.

Currently, I'm based in Berlin working remote with Go as a Senior Software Engineer, but always looking for new challenges.

## Education

UNIVALI University, BSc in Computer Engineering, June 2011.

## Experience

#### Zalando Lounge (Jun 2020 - Present)

*Senior Software Engineer*

**Main Technologies:** Go, MySQL, Kafka, AWS, Kubernetes;

I work as an Engineer responsible for several internal projects for the CCS - Campaign and Content Solution. My team and I have designed and developed several new microservices to replace a legacy PHP application. Now the data is published on Kafka, which is later consumed, enriched, and saved in a MySQL database, replacing old legacy SOAP calls. Also, a new microservice was built to import data from other areas (e.g. supplier, logistics) inside of the platform, the most relevant is the article onboarding which needs to orchestrate several API calls and publishing events.

#### ProShare - Car Sharing by Volkswagen (Nov 2019 - Jun 2020)

*Senior Software Engineer*

**Main Technologies:** Go, gRPC, MariaDB, GraphQL, Docker, AWS, Kubernetes;

I helped to develop a whole car-sharing platform focused on professionals from scratch. All backend was written in Go and MariaDB as database, the communication between our microservices was done through gRPC. For external communication, we provided a RESTful API and a GraphQL API for easy integration with our Web App and our Mobile apps.

The infrastructure was built using Terraform running in a Kubernetes cluster on AWS.

#### Foodora/Foodpanda - DeliveryHero (Jan 2018 - Nov 2019)

*Senior Software Engineer*

**Main Technologies:** Go, ElasticSearch, MySQL, Redis, Docker, AWS, Kubernetes;

I was working on Pandora's platform (Foodora + Foodpanda), moving away from a monolithic application to microservices using event-driven architecture and Go evangelist.

I was a member of Search & Discovery team with a high traffic API where I built a service to handle the search of 4 different brands in 20 different countries, cutting in 6x the average response time. ElasticSearch, Redis, and MySQL were intensively used.

As a Go evangelist, I helped the whole business unit to develop a new open-source library, define new guidelines and best practices for Go projects.

#### Ridelink (Sep 2016 - Dec 2017)

*Tech Lead*

**Main Technologies:** Go, PHP, Python, ElasticSearch, MySQL, Redis, Docker, AWS;

I was the Tech Lead of a polyglot team responsible for developing a car-sharing platform. Most of the microservices were developed using PHP with Symfony and Silex frameworks, but a couple of services were written in Go and Python. The infrastructure was relying on several AWS services, such as ECS, SQS, ElasticCache, ElasticSearch, RDS, and CloudWatch.

I have also developed an open-source tool called [deploy-ecs](https://github.com/guilherme-santos/deploy-ecs) to help us in our continuous deployment process.

#### Neoway Business Solution (Jun 2015 - Sep 2016)

*Senior Software Engineer*

**Main Technologies:** Go, ElasticSearch, MongoDB, RabbitMQ, Docker, Rkt, AWS;

I was a member of the Core team in the development of a Big Data platform for Market Intelligence. I've developed several RESTful APIs to communicate with different backends like ElasticSearch, MongoDB, and RabbitMQ.

DevOps culture was really strong there which helped me improve myself and develop some tools to enable us continuous integrations, and continuous deployment at AWS.

#### uTech Tecnologia (Nov 2014 - Feb 15)

*Software Engineer*

**Main Technologies:** C++, Qt, QML, JavaScript, SIP;

Freelance project to develop a Softphone to integrate with company’s
PABX. The application was multi-platform, running in Windows 7, Linux, and MacOS. The technologies used were C++, QML, and JavaScript through the Qt library, for VoIP communication and SIP stack the library PJSIP was used.

#### GIOX Tecnologia (Mar 2013 - Present)

*Founder*

**Main Technologies:** Go, PHP, JavaScript, MySQL, MongoDB, Docker, NSQ, Ansible, SOAP, XML;

As an entrepreneur I founded [Giox Tecnologia](http://giox.com.br) in 2013, a company focused on creating SaaS ERP for small businesses.

The monolithic was developed using PHP as backend with ZendFramework2 and Silex with MySQL as database. Later the project started to grow and new microservices were needed which were written in Go and new technologies were added e.g. MongoDB, and NSQ (message broker). I also worked as Frontend using jQuery, Backbone.js, Underscore.js, and Bootstrap3 which were later migrated to a modern SPA using Vue.js, Firebase, and Vuetify.

I was not only the Backend and Frontend Engineer I worked quite a lot as SysAdmin and DevOps, to automate and scale as easily as possible. The company runs at DigitalOcean, I use Ansible, Docker Compose, Docker Swarm, Git, and Gitlab-CI to automate and maintain the Linux servers.

#### Digitro Tecnologia (Dec 2009 - Mar 2013)

*Software Engineer*

**Main Technologies:** C, C++, Lua, SIP, uCLinux, GStreamer, Blackfin;

I was responsible for the development of a UI for an IP Phone with a touchscreen display using a Blackfin processor embedded with uCLinux. The UI was built using EFL graphic library, GLib, GObject, and Sofia-SIP as SIP stack.

Development of a web service for speaker recognition. The service creates audio models from a voice, those models were later used to identify someone talking on an audio recording. Some of the technology used was Lua, lighthttpd, GStreamer, FastCGI, and MongoDB.

Development of keyword spotting, which was a service to perform text search on audios using a proprietary protocol to communicate with clients, was built using Lua, C, and GStreamer.

Development of an audio streaming server, a web service responsible for loading audio recordings in different audio codecs, transcode then, apply filters and effects and send to the client through the RTMP protocol, technologies used was C++, C, and GStreamer.

## Skills Base

- **Programming Languages:** Go, PHP, Python, JavaScript, C, C++ and Lua;
- **Databases:** MySQL, MongoDB, ElasticSearch and Redis;
- **Agile practices:** Kanban, SCRUM, Pair programming, TDD;
- **Tools:** Git, Makefile, Ansible, GitLab CI, Kubernetes, Jenkins;
- **Languages:** Native in Portuguese and Fluent in English;
- **Others:** RabbitMQ, NSQ, Nats, Docker, Kubernetes, AWS;

## More Info

- **Linkedin:** https://www.linkedin.com/in/guilhermesilveirasantos
- **Github:** https://github.com/guilherme-santos
