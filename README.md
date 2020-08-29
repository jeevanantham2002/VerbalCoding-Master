# VerbalCoding-Master
Verbal Coding is a combined verbal programming language and platform, which empowers visually impaired people to engage in coding for recreational, educational, and profressional uses.

The app includes a proprietary pipeline that converts between verbal programming language and a mainstream language (currently Python, Java, JavaScript are supported). This way, visually impaired users are integrated with existing software engineering teams.

Verbal Coding is on a mission to democratize programming for marginalized communities. With the power of AI, assistive design, and UI/UX design principles, we believe we will make this happen.

# Features
* Saving Project: Users are able to have their own projects and continue coding where they left off. (Feature in beta testing)
* Custom Interperator: Custom verbal coding interperator which processes spoken code (in verbal coding syntax) to an output.
* Custom User Authentication:Through firebase users are givien indiidvual profiles and accounts on the verbal codding platform when they log in using their google suite accoutns.
* Function componentization - the nesting of large functions is described to the user, and they get metrics on how large and fragmented their code is.
* Sentiment analysis - recognizes tone and inflection in the user's voice, in order to understand emphasis and frustration when using different code structures.

# Tech Stack
* Frontend - AngularJS, HTML, CSS, and Bootstrap
* Google Speech To Text API: Ran on NodeJS server in beta versions (currently using Javascript Webkit in production application)
* Backend - SpringBoot Server Hosted on AWS Elastic BeanStalk and Elastic Compute Cloud
* Database and user Authentication - Firebase (Document-based, NoSQL)
