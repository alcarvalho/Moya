Documentation
=============

Moya is about working at *high levels of abstraction* in your application. 
It accomplishes this with the following pipline. 

![Pipeline](https://raw.github.com/ashfurrow/Moya/master/web/pipeline.png)

----------------

<p align="center">
    <a href="Targets.md">Targets</a> &bull; <a href="Endpoints.md">Endpoints</a> &bull; <a href="Providers.md">Providers</a> &bull; <a href="ReactiveExtensions.md">ReactiveCocoa</a>
</p>

----------------

You _should not_ have to reference Alamofire directly. It's an _awesome_ 
library, but the point of Moya is that you don't have to deal with details
that are that low-level. 

If there is something you want to change about the behaviour of Moya, there is 
probably a way to do it without modifying the library. Moya is designed to be 
super-flexible and accommodate the needs of every developer. It's less of a 
framework _of code_ and more of a framework of _how to think_ about network 
requests. 

Remember, if at any point you have a question, just [open an issue](http://github.com/AshFurrow/Moya/issues/new) 
and we'll get you some help.
