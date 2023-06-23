# State management

*Report generated June 23, 2023*


| type        | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10   |   NPS |
|:------------|:----|:----|:----|:----|:----|:----|:----|:----|:----|:-----|------:|
| async_redux |     |     |     |     |     |     |     |     | 2   |      |   100 |
| bloc        |     |     |     |     | 1   |     | 2   | 3   | 4   | 12   |    68 |
| get_it      |     |     |     |     |     |     |     | 1   |     |      |     0 |
| getx        | 1   |     |     |     |     |     |     | 1   |     | 1    |     0 |
| mobx        |     |     |     |     |     |     |     |     |     | 1    |   100 |
| provider    |     |     |     |     |     | 1   |     | 4   | 1   | 4    |    40 |
| redux       |     |     |     |     |     |     |     | 1   |     |      |     0 |
| riverpod    |     |     |     |     |     |     | 1   | 7   | 6   | 22   |    77 |
| stacked     |     |     |     |     |     |     | 1   |     | 1   | 1    |    66 |


## async_redux

### What could be improved?

- Not many people use it. Maybe a bit more marketing.  

### What do you like about it?

- Great documentation, not using streams, comprehensible (it is easy to comprehend how a specific app state forms)  
- Redux itself is very simple to understand and thus perfect for smaller and medium teams  


## bloc

### What could be improved?

- Cubits should be de facto elements. Blocs are bloated.  
- Bloc's amount of boilerplate could be reduced and a new member to the bloc & cubit family could be added that doesn't use streams, but notifiers instead. Flutter's notifiers could have their family extended in the framework with things like package:state_notifier  
- Needs a lot of code xd  
- Absolutely nothing, i find it to be perfect.  
- Here logic  
- it's Verbouse  
- Bloc to bloc communication  
- Tests  
- Love it.  
- Seems perfect to me.  
- I think it's bit bit complex and with boilerplate. Sharing data between blocs is difficult.  
- Documentation and more examples for advanced projects/complex functionality  
- Simplify the builders for wrapping widgets else access the data using context and render like in react-redux where you don't need to wrap your UI components with something else   
- To many boilerplate   
- Maybe the plugins for the IDE's that generate code for the package. It uses a different style than I do.  
- Cubit is great - could also just be a state notifier, but the thought process with tree based injection is much easier to reason about.  

### What do you like about it?

- Simple to understand, testable.  
- having full control on emitting states and ui rebuilds  
- The bloc architecture & data flow are awesome in my opinion. Flutter's notifiers are amazingly simple and intuitive, and also part of the framework.  
- Its simple  
- Ease of use, isn’t complicated, and the separation of concerns architectural design.  
- Powerful   
- Docs, simplicity  
- The structured way of working with it gives confidence and consistency to the code  
- The level of control we can achieve with states if applicable in a good architecture such as TDD  
- Nothing  
- The documentation is great and so as the community. flutter_bloc is quite flexible too and it's  suitable for most (mostly medium to very large) project.   
    
  The best part is, there's example for most usecases and that's a good thing for newbies and even experienced hackers.  
- Separation from UI and business logic   
- Flutter bloc :^8(cubit) is really simplified and easy to use.   
- It the best  
- I like that up till now it has always been able to solve every case I've thrown add it.  
  When trying to create my own state management solutions I always ended up implementing bloc-like features which made my solution look very similar.  
- I like to refer to Cubit as „WidgetModel“ as a reference to Viewmodels - this works pretty well and is easy to understand and follow as a pattern   
- Ez testing  


## get_it

### What could be improved?


### What do you like about it?



## getx

### What could be improved?

- make it smaller , it does too much , routing, state management, localization , etc   
- no need to improve, just don't use it  
- better docs and name ;)  

### What do you like about it?

- state management, dependency injection   
- getx was fast for small app development  
- Easy to understand, less typing, not verbose, makes sense even at fast glance  


## mobx

### What could be improved?

- Tracking async action oob, no generation (meta programmming will solve this soon)  

### What do you like about it?

- Easy to build full reactive apps with a lot of observables / computed ones  


## provider

### What could be improved?

- have not coded in a long time in Flutter  
- JS Signals approach in Flutter. Package ASP is promissing  
- It’s old. Riverpod is its next iteration.   
- Improve ChangeNotifier  
- no complaints  

### What do you like about it?

- simplicity  
- The ease of learning and using.  
- It’s robust.   
- notifyListener  
- Easy to use...   
- Easy to grasp,got lot of resources online and really efficient for beginners.  
- simple, not fancy, easy to use, works for all my cases, if it work doesn't then something that shouldn't be done is probably being done.  


## redux

### What could be improved?

- Asynchronous actions, without using additional packages  

### What do you like about it?

- Single store architecture   


## riverpod

### What could be improved?

- Some of the handling of FutureProviders could be cleaner for me, or some distinctive uses of .map and .when with them could be super helpful. Only thing that's ever tripped me up a bit.  
- Generics support  
- Documentation, better examples, tutorials   
- Riverpod to be integrated with hot reload.  
- Documentation fr  
- Less complexity is always welcomed (like Getx) without sacrificing features, performance, scalability, and robustness   
- Documents, and common usecase  
- Documentation  
- More diverse examples.  
- Inbuild local cache support  
- Alignment of syntax with idiomatic flutter, ala context.  
    
  Ability to preload async providers, particularly for families, when data is loaded from some other API.  
- It is perhaps getting a bit over engineered and too complex, has a bit high learning curve. Docs have been a bit so, so, but are improving, plenty of 3rd party guides covers the gaps. No built-in architecture, bring you own wiring, can be both good and bad. It is nice, but maybe not the ultimate solution I thought it would be. Until something "better" comes along, sticking with it for now.  
- Use context instead of ref  
- The mental model is hard figure out. It's hard at first to think the "riverpod" way  
- Two or three name for the same thing   
- More use case examples  
- The definition of the providers, I feel that it could be optimized how the different providers and their modifiers are declared  
- if it is  default included inside flutter or flutter provide its own state management solutions than it would be great   
- Documentation  
- The need to extend a consumer widget bothers me. It should be just context.read / context.watch.  
  This would be easily be possible if the flutter team fixes a bug with inherited widgets, but they wont for whatever reason (there were multiple tries also from remi).  
    
  Also the documentation is lacking a lot which makes it hard for beginners to fully grasp. This also relates to its framing since its not really sm, but more a caching and service locator package.   
  Because of that I always feel weird to compare ie. riverpod and bloc. I have actually used both together, riverpod as the service locator and bloc as the 'service' instance, and it was great because you get the best of both worlds.  
    
  In that manner I think it would be great if a developer could easily create their own providers on top of riverpod. But that api is currently very restricted and complex.  
- Docs  
- Removing code generation for the new syntax, but will have to wait for static meta programming. It's not too big a deal if you run build_runner watch  
    
  Hidden dependencies can also be a problem with riverpod  
- Less syntax changes. Documentation but that’s already being worked on  
- Documentation  
- having some sort of thinking the "riverpod" way in the docs and project architecture recommendations  
- documentation, chaining async actions stuff together without 1 frame loading states   
- The documentation can use a bit more advanced providers in explaining some stuff like pagination.  
- A bit complex to apprehend the first times.  
- Documentation and handling mutations  
- More transparency for riverpod - there is too much magic going on.  
  Riverpod feels like a m*m matrix which is very hard to track.  

### What do you like about it?

- Made it so easy to map out the state pieces of my app and how to connect them to have derived state and reactive state.  
- Simplicity, development speed, using as a dependency injection tool, custom lints  
- Ease of use, built in cache  
- Data caching right out the box  
- Dependency injection and how easy it is to update state by just using consumerstateful  
- It doesn't interfere with the UI side, scalable, good performance,   
- My app state are separate from my UI , and they can easily communicate with each other outside the UI.   
- I like how it satisfies my DI and SM needs. It isn't as verbose as bloc and it also doesn't require I add another package for DI if I was using bloc.  
- StateNotifier which is just like a ValueNotifier on steroids.  
- Code genaration simple to user variety of providers  
- By and large just works.  
- Powerful, has a solution for pretty much everything. You can build/use only simple basic patterns with it, or go all-in on its codegen, own linter etc. No built-in architecture, bring you own wiring, can be both good and bad. Bigger teams might prefer flutter_bloc, although some dev shops have switched to Riverpod.  
- The syntax.  
  Pattern matching for async value   
  Simple dependencies injection   
- Provider are not scoped. It seems weird at first but it's not a bad idea it seems  
- I like because it’s straightforward, easy to learn , easy to use , with DI out of the box make things smoother   
- It simplicity.  
- Which is simple, accessible, and less verbose than other state handlers  
- It can work on both statefull and state less widget   
- Simplicity  
- Its both good for simple small stuff (ie counter app) and complex large stuff. It has next to zero boilerplate code and a great reactivity pattern.  
- Flexible, easy to read and use  
- Simple to use and understand, just write a function and annotate it and it's ready to be used. It is also easy to depend on other providers in a provider.  
- It simplifies logic to a great extent. It helps think about individual pieces of state as opposed to the state per page  
- Elegant, minimal, feature rich  
- Simplicity, not hard to use once you understand the concept and widely used/support  
- easy to reason about global state, easy to inspect, no "walls" that prevent state from being accessible when the requirements change,   
- What I like most about riverpod is it's easy straightforward syntax, the learning curve and the community support. You can easily get stuck if you need help. Also, since there's plenty of projects using it sometimes, I get to check many different implementations of a particular feature and based on that decide on a way to implement mine.  
- The type safety.  
- It's more a data fetching library than a state management library, state management only highlights one of its features.  


## stacked

### What could be improved?

- More flutter web support  
- I love stacked but its not very popular among flutter developers, which means i have to learn other state management while working with other developers   
- It's documentation, sample projects, community engagement on it. It feels like an island as folks around it only wait for the maintainer to do something.  

### What do you like about it?

- Easy to setup  
  cli  
  no boilerplate   
- MVVM architecture, out of the boss services like snack bar, navigation, bottom sheet etc, dependency injection etc  
- The ease of doing things as it's a syntactic sugar on provider.  
