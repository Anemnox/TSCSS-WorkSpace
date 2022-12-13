# The Architecture of SAAS Applications

> **_NOTE:_**  This content comes from [lecture 2](http://faculty.washington.edu/wlloyd/courses/tcss360/tcss360_lecture_2.pdf), [lecture 3](http://faculty.washington.edu/wlloyd/courses/tcss360/tcss360_lecture_3.pdf) and [videos](http://www.saasbook.info/videos). Much of the content is paraphrased from the lecture.

Before talking about SAAS Applications, there are a few basics to be outlined
about computer architecture. One of the first key terms to know is design
patterns. Software developers outlined a general architectural solution for a
family of similar problems. For object-oriented design patterns, there is a well
known book known as _Design Patterns:Elements of Reusable Object-Oriented Software_
which can be easily found through a search engine. This book outlines many
design patterns for object-oriented architectures. Though there are more than
just object-oriented design patterns.

## Example patterns

The first design pattern to look at is the client-server architecture. This is
where an application labeled as the client communicates with an application
dedicated as the server. Although the server may be a network of applications,
in the client's perspective, the communications are centralized to a server.
Servers. on the other hand, can communicate and provide service to many clients.
This is in comparison to a peer-to-peer architecture which is where clients and
servers are not defined and applications communicate directly with each other.

The model-view-controller design pattern is another very notable architecture
which generally describes the structure of a graphical user interface (GUI). The
architecture outlines an application based on its functionality: the data
structure (model), the visualizer (view), and the modifier (controller). The
idea is to make sure that the flow of information is one directional to prevent
conflicts between the 3 functionalities. The view relies on the model to display
the information and changes to the model will change the view. The controller
has the ability to change the model and the view but is separated through an
interface. This allows flexibility in the presentation and allows for one model
to have multiple different views.

## SAAS Architecture

As time passed, developers started to think of the web as more than just static
pages. Now, the web is viewed as a medium that passes information to clients
that can be in any form which allows for a much broader idea of services that
can be provided to customers around the world. There have been many ideas around
the method of communicating information over the network but the main protocol
that has been dominant was HTTP. At first, HTTP was not designed to manage
cookies, login sessions, and persistent information. Though, with the innovation
of the web, http evolved to include these functionalities and provide the main
backbone behind the internet. In addition, a standard of communicating
information had also been laid out known as REST. REST stands for
Representational State Transfer which was the idea that each request should have
all of the information that is required for the communcation. REST was built on
top of HTTP and had the advantage of being performant, scalable, simple,
modifiable, visible, portable, and reliable.

> HTTP lists methods of requests within the transport protocol. This includes
GET, POST, UPDATE, and more which describes the intent behind the request. This
is read by the server which can then reply with a response based on the given
information provided by the HTTP request.

With HTTP being independent, there needed to be a way to manage http request
that was presistent to a single user. An idea could have been to use IP
addresses to identify returning users but with public ip addresses and now,
dynamically set ip addresses, this would have been impractical if not impossible
to accomplish. Another idea was to embed unique user junk into the URI query
string. However, this would break the idea of caching (though, that hasn't
prevented developers to use this method). This led to the idea of cookies which
would be used to track users within their browsers and manage sessions for
users. There are many ways to make sure that cookies are safe and have not been
tampered with and most frameworks manage this for you. An example of this is
shown in [here](https://www.youtube.com/watch?v=Xlt7xeqVfO4).
