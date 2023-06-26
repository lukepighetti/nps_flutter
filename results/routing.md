# Routing

*Report generated June 26, 2023*


| type          | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10   |   NPS |
|:--------------|:----|:----|:----|:----|:----|:----|:----|:----|:----|:-----|------:|
| auto_route    |     |     |     |     |     |     | 1   | 1   | 1   | 2    |    60 |
| beamer        |     |     |     |     |     |     | 1   |     |     |      |     0 |
| Fluro         |     |     |     |     |     | 1   |     |     |     |      |  -100 |
| getx          |     |     |     |     |     |     |     |     | 1   |      |   100 |
| go_router     | 1   |     |     |     |     | 1   | 3   | 4   | 7   | 2    |    38 |
| Navigator 1.0 |     |     |     |     | 1   |     |     |     | 1   | 2    |    50 |
| Navigator 2.0 |     |     |     |     |     | 1   |     |     |     |      |  -100 |


### NPS Details


| type          |   total |   detractors |   neutral |   promoters |   NPS |
|:--------------|--------:|-------------:|----------:|------------:|------:|
| auto_route    |       5 |            0 |         2 |           3 |    60 |
| beamer        |       1 |            0 |         1 |           0 |     0 |
| Fluro         |       1 |            1 |         0 |           0 |  -100 |
| getx          |       1 |            0 |         0 |           1 |   100 |
| go_router     |      18 |            2 |         7 |           9 |    38 |
| Navigator 1.0 |       4 |            1 |         0 |           3 |    50 |
| Navigator 2.0 |       1 |            1 |         0 |           0 |  -100 |


## auto_route

### What could be improved?

- Documentation, examples  
- Mixing declarative and stack navigation  
- Easier nested navigation api  
- Deep linking is still not ideal, but works mostly how I expect  

### What do you like about it?

- Very easy to use, generates everything I need. Can handle more complex situations  
- Easy to use yet very powerful  
- Easy  Tab navigation,typesafe routing   
- Been using it for like 3 years and have only had to do a single small refactor. Have yet to run into anything I couldn’t solve with Auto Route.  


## beamer

### What could be improved?

- The whole routing thing is just :puke: not really beamers fault tho  

### What do you like about it?

- Able to deal with nested navigation properly. (Bottom tab navigation), guards.  


## Fluro

### What could be improved?

- It’s kind of deprecated   

### What do you like about it?

- Easy to use, easy to understand   


## getx

### What could be improved?

- It is very simple and I beleive not explored it so much to suggest improvements  

### What do you like about it?

- Ease of use  


## go_router

### What could be improved?

- go_router_builder is not always up-to-date with the latest versions of go_router which makes it difficult to use the newest features.  
- Nested Routing, there is not a way to preserve the state of a nested router  
- Simple way to implement guards or middlewares  
- Interaction with WillPopScope  
- In general seems very verbose and the new stateful routes and so is super tedious  
    
  Miss the docs from Chris :'(  
- Specifying top-level and nested routes could be simplified, maybe something similar to Rails routes.rb?  
- Documentation was better when it had its own website, but flutter being flutter ruined it :(  
  Be more like SwiftUI :)  
- Implement the base line features available in all other competitors.   
  Take us seriously because it made no sense to make a breaking change to rename queryParams to queryParameters   
  I just don’t trust the package anymore tbh   
- Path naming can be tricky.  
- Web based file routing   
- Docs, examples  
- there should be a simple way to pop until it gets to a specified page  

### What do you like about it?

- Easy to setup and type safety brought by go_router_builder code generation also it is maintained by the Flutter team.  
- Mostly that is maintained by Google and that the original creator was part of the original Flutter team.  
- It simplicity and no need to use the code generator for declare the routes  
- Simple API and no need of build runner  
- Simplicity  
- It works at least haha  
- Setting up routes is familiar if you’ve worked with other web-based routers, so picking it up is simpler.  
- Nothing. I actually joined the company and it was there.   
- Can be used in the web also, is complete and more similar to frontend routing.  
- Shell route, easy redirect, easy setup  
- simple  
- Easy to setup   
- Supported with flutter team  
- I like the page builder for animating pages and redirect for page accessibility  


## Navigator 1.0

### What could be improved?

- Looks perfect for its purpose (Mobile Navigation)  
- Web: it's pretty wild that we still don't have a decent enough navigation solution on the web other than bloated libraries that apply heavy patches on top of something that should've been resolved long ago.  
- out of context routing, make it easier   

### What do you like about it?

- It's simplicity compared to Navigation 2.0  
- Simplicity and how easy it is to setup/understand/work with on a number of different use cases.  
- consistent, reliable   


## Navigator 2.0

### What could be improved?

- I should be able to specify the type of object my route receives as an argument instead of always typecasting from Object to a custom type.  

### What do you like about it?

- The fact that each route has access to RouteSettings and BuildContext.  
