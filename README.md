# HookUP

## Mission statement

There is a growth of services that take some FLOSS piece of software and wrap
it in a web service. I think this model is basically a waste since it reduces
the possibility of contribution to the orginal software. Work on these services
is (partly) better spent on improving the API of the original software and make
it easy to ingegrate into the end user's systems. Also, these services often
add security and privacy considerations.

Are these services evil? No, but they promote laziness and needless dependency
on network interaction.

I call this model ARLAAS: Access to Random Library As A Service.

Do these services add something of value? Often, yes. They generally provide
one or more of:

* Integration with source control (like GitHub)
* Runners: server power to run something or other for you
* Notifications: they tell you when something is wrong
* A nice UI
* A nice API

Any cases that only provide the last option are really not worth it. Instead,
the original tool should be improved so that is usable as-is.

HookUP aims to provide the first three and possibly the fourth item.
