# Backend

*Report generated June 23, 2023*


| type               | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10   |   NPS |
|:-------------------|:----|:----|:----|:----|:----|:----|:----|:----|:----|:-----|------:|
| appwrite           |     |     |     |     |     |     |     |     |     | 1    |   100 |
| aws                |     |     |     |     |     |     |     |     | 1   |      |   100 |
| cloudflare         |     |     |     |     |     |     |     |     |     | 1    |   100 |
| dart_frog          |     |     |     |     |     |     | 1   |     |     | 1    |    50 |
| django             |     |     |     |     |     |     | 1   | 1   |     |      |     0 |
| echo               |     |     |     |     |     |     |     |     |     | 1    |   100 |
| firebase           |     |     |     |     |     | 2   | 1   | 6   |     | 7    |    31 |
| firebase + laravel |     |     |     |     |     |     | 1   |     |     |      |     0 |
| gin                |     |     |     |     |     |     |     | 1   |     |      |     0 |
| go                 |     |     |     |     |     |     | 1   |     |     | 1    |    50 |
| headless-cms       |     |     |     |     |     |     |     |     | 1   |      |   100 |
| laravel            |     |     |     |     |     |     |     |     |     | 1    |   100 |
| NestJS             |     |     |     |     |     |     |     |     | 1   | 2    |   100 |
| other              |     |     |     |     |     |     |     |     | 1   | 1    |   100 |
| phoenix            |     |     |     |     |     |     |     |     | 1   |      |   100 |
| pocketbase         |     |     |     |     |     |     |     |     | 1   |      |   100 |
| sanic              |     |     |     |     |     |     |     | 1   |     |      |     0 |
| shelf              |     |     |     |     |     |     | 1   |     |     |      |     0 |
| supabase           |     |     |     |     |     |     |     | 1   |     | 5    |    83 |


## appwrite

### What could be improved?


### What do you like about it?

- It's super easy to use, and, depending on where it's hosted, it's free... and it's super robust  


## aws

### What could be improved?

- Official SDKs and better documentation.   

### What do you like about it?

- Incredibly powerful and cheap. Great IaC tools make building sophisticated backends fun and simple.   


## cloudflare

### What could be improved?

- Authentication   

### What do you like about it?

- R2 workers durable objects   


## dart_frog

### What could be improved?


### What do you like about it?



## django

### What could be improved?

- The async part  
- Compared to a backend like firebase there is more setup and somewhat repeated code/ logic. One example is keeping flutter models and django models updated when adding new fields.   
    
  Speed in initial config and hosting/deploy is slower but once setup just as fast as other options.   

### What do you like about it?

- The ease to work with and the batteries included with it for almost everything   
- The full control over the backend. Less vendor lock-in, although still some.   
    
  Postgres vs NOSQL. Firebase can not handle complex relationships IMO   
    
  Cost at scale, especially for storage. My app will be streaming audio and doing that from firebase storage would be a lot more expensive.  
    
  I still love firebase and use it in other projects.   


## echo

### What could be improved?

- Type generation for dart  

### What do you like about it?

- Everything  


## firebase

### What could be improved?

- Not much of an improvement, just uncertainty around Google killing their products  
- Better doc of the issues with billing and how to avoid surprises  
- The risk of Google shutting it down  
- Remote messages, and caching system.  
- Could be better if it had an SQL based db  
- More Youtube tutorials on how to do various task..   
- Pricing  
- Using something more than just the functions framework, like server pod or dart frog (preferred)  
- More auth providers (eg. discord)  
- Dart for Functions!  
- Firestore feels incredibly limiting when it comes to querying. It requires a lot of upfront thought and planning, and even then you can wind up simply unable to satisfy certain requirements. Also, function support for Dart was completely lacking when I worked on this project (going back a few years now).  
    
  Also, maybe just me, but I experienced a lot of confusion at the time in how Firebase and Google Cloud Platform were related/integrated. Firebase just felt like an ugly stepchild or something. Perhaps that's improved by now.  
- Overall it is pretty good, the only thing I've been looking is the ability to write functions in a different language than typescript/javascript, recently they added support for python, but I'm not a fan of it  
- Could use a SQL version of Firestore  
- most of my complaints come from firestore, security rules, and building a tiered access model ontop of it. Sometimes a “single read” can perform up to 4 reads while trying to figure out if the requester has access.  
- Probably the Cloud Messaging Flutter package. They should start looking towards making the support for background messaging even better. Also Why can't we write Cloud Functions for Firebase with Dart. I'm going crazy!!!  

### What do you like about it?

- Ease of use and other features built around the ecosystem. Firebase messaging, cloud functions, crashlytics  
- Simple and direct  
- Easier integration with flutter  
- Security, efficiency and robustness   
- The amount of resources available and ease of use. For a beginner ig it's a really handy option.  
- Easy to use...   
- Easy integration, remote config is dope as fuck.  
- The client flutter app only knows about firebase, and just reacts to firestore changes.  
- Easy, fast, great start pack and services, wide range of essential services, documentation, top notch and outstanding integration with main tools used to build apps.  
- It is super easy to setup and get started.  
- Simply works  
- The offline and syncing experience was pretty nice, as was the performance.  
- Database, storage and functions, you can build almost (if not) anything with these 3, I have the feeling auth and analytics can be switch with other providers, but these 3 are pretty useful for my use cases. Crashlytics is also pretty good, but I have not much experience with it.   
- Easy to implement, easy to plugin to any Flutter app. No backend setup. Just code and done.  
- user auth is hella easy. Firestore “just works” although I do have some gripes about it. Having crashlytics, remote config and more in one portal feels very nice. Firebase suite feels good, and cohesive. Easy to add new features from their toolkit and a generally good DX outside of firebase emulators.  
- Ease of Integration  


## firebase + laravel

### What could be improved?

- Firebase otp ask for recaptcha soo many times wish it would be improved   

### What do you like about it?

- Just that im confident with building with it i feel like if you are confident with the technologies you working with it's all it metters   


## gin

### What could be improved?

- It's not beginner friendly but it works for me because we have a similar stack at work so it avoids me the context switching  

### What do you like about it?

- It's mostly free to run so I don't spend money on my side projects and it scales well in case it succeeds. Without the auth layer it can be done in a day with chatgpt. Boilerplate so perfect for ai autocompletion and I like I don't have to use my brain to read smart code. I use the repository + service pattern. I spin up side projects with chatgpt + copilot very easily. I ask chatgpt to pitch me my idea back, then I ask it to make a sql schema for a MVP of this idea, then I give it the context of https://bun.uptrace.dev/guide/relations.html ask it to create the golang structs for it with the correct bun tags. Then it's a matter of setting up the migrations, and adding the routes / controllers with the correct repositories. Then I comment the routes with the corresponding curl commands to get the autocompletion from copilot + I add an example response. Then I generate models for dart using quickwit, and ask chatgpt to create the dart client based on the routes I commented with the curl commands and responses. Then comes the auth layer which is the hard part but you do it only once and copy paste it between projects  


## go

### What could be improved?

- my biggest complaint is lack of multi platform support for MSAL — I’m using azure ad b2c for user management here and while ADB2C is actually really neat, seeing the benefits from it in Flutter just isn’t really that feasible given the open source implementations of MSAL that I’ve found.  

### What do you like about it?

- I have complete control over more the server side application. App service is easy to use, MSAL and ADb2c seems very powerful, and I’m able to run cosmosdb serverless which is heckin’ nice from a cost saving perspective.  


## headless-cms

### What could be improved?

- Headless CMS: good when you need something fast, bad for any computation/complex backend task.  

### What do you like about it?

- Nest.js: architecture.  


## laravel

### What could be improved?

- websockets 😭,  

### What do you like about it?

- fast, reliable, Auth and OAuth😎  


## NestJS

### What could be improved?

- Nest.js: the fact it runs on Node. Barely waiting for Bun.sh to work well with Nest.  

### What do you like about it?

- Nest.js: architecture.  
- It’s well documented and the project is actively used by a lot of bigger companies. A lot of features that make life easier when writing code for production are built in already such as a CLI and stuff like customizable decorators and many more. Solid courses and learning material are provided by the founder of the project himself.  


## other

### What could be improved?

- Could be written in Dart. Hey! Looks like I'm apparently working on one :D dartseid.ex3.dev is still in *VERY* early development. But one to keep an eye on ;)  

### What do you like about it?

- Love batteries included nature of most of these. Which is why I want Dartseid to be batteries included too. Slowly getting there :)  


## phoenix

### What could be improved?

- it is still a pain to get push. notifications configured and working properly on both android and ios. Better cross platform widgets that are visually close to the native os.  It would be awesome if this become easier. Dart code is a bit verbose, not sure how that could be addressed easily.     

### What do you like about it?

- Phoenix(elixir) and postgres work great together and the backend is fast.I find it easier to work sql vs nosql. Postgres has  a lot of tools for tuning and configuring for high performance. Granted, i dont' know all of them :-) .   Phoenix/Elixir provides a lot of built in primitives for concurrency and background tasks.  It is quite easy to spin up a cron like task without any external tools.   


## pocketbase

### What could be improved?

- More integrations  

### What do you like about it?

- The ease of use and no hassle setup.  


## sanic

### What could be improved?

- Python - It's the side chick that spoils us all.  

### What do you like about it?

- It's easy to write complex queries.   


## shelf

### What could be improved?

- more middleware  

### What do you like about it?

- ultra stable API  


## supabase

### What could be improved?

- Documentation  
- Authentication gets expired after a week :(  
- API documentation, logs, and more robust RLS  
- Creating new databases is supabase is tricky  
  Self hosting and migration should be easier   
- Offline caching, native login  

### What do you like about it?

- Reliability, feature set, ease of development  
- Postgresql, can deploy my own, easy migration   
- Very fast to spin up, cheap, robust UI  
- Simple, great docs, self hostable, runs locally  
- Simple to use, has a GUI, a generous free tire  
- We can have a SQL database with Firebase-like developer experience.   
