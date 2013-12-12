[ALSP]: https://github.com/jermnelson/aristotle-library-apps
[DJANGO]: https://www.djangoproject.com/
[FEDORA]: http://www.fedora-commons.org/
[FLASK]: http://flask.pocoo.org/
[RLSP]: https://github.com/jermnelson/redis-library-services-platform

Aristotle Library Services Platform
===================================

The Aristotle Library Services Platform is a collection of loosely coupled web applications 
for enhancing bibliographic and semantic descriptions of resources actively managed 
and curated by memory institutions like libraries. This project is an evolution of 
the [Redis Library Services Platform][RLSP].

## Reason for Name Change
With development of the [Aristotle Library Services Apps][ALSP] there started to develop
a disconnect between most of the active development being apps that communicated with 
[Fedora][FEDORA] digital repositories and never interacted with the Redis bibliographic
datastore, the [Redis Library Services Platform][RLSP] was much more than Redis an may
unduly focus addition on Redis instead of the broader application of open-source 
web apps for Linked Data based interactions with people and systems. 

## Shift from Django to Flask
Another shift is switching Python web frameworks between [Django][DJANGO] used in the [Redis Library Services Platform][RLSP] to [Flask][FLASK](http://flask.pocoo.org/) used in this project. While [Django's][DJANGO] rich ecosystem is desirable, [Django][DJANGO] applications are too closely dependent on the framework making it harder for other people to deploy and use bits and pieces in their own applications. Getting [Django][DJANGO] to run on Windows is harder than getting [Flask][FLASK] applications. 
