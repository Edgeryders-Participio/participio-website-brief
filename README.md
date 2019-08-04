# Participio website brief 

A website to present the projects collected and funded by the Participio project. Most of the content on the site will be retrieved from the Edgeryders Discourse platform by querying specific tags. This way of using Discourse as a CMS for websites has been done on two previous occasions, Edgeryders [Culture Squad](https://culturesquad.org/) ([Git repo](https://github.com/Edgeryders-Participio/culturesquad-site)) and [Internet of Humans](https://internetofhumans.eu/) ([Git repo](https://github.com/Edgeryders-Participio/NGI)). 

Both Culture Squad and Internet of Humans use a cache api at api.particip.io which caches content to not be restricted to the rate limits of the Discourse API. Any JSON response can be retrieved using this pattern: "api.particip.io/get-data?endpoint=http://edgeryders.eu/tags/webcontent-culturesquad-member" 

## Site sections

The Participio website should have the following sections:

 * A "hero" banner, similar to https://internetofhumans.eu with text "A community collecting, curating and building software for participatory culture". Not dynamic. Should have button to "Join the community".

 * "How to Participate" section, also similar to that on https://internetofhumans.eu/. Not dynamic. Copy TBD. Basically, will explain that Participio exists both to collect good existing apps for participatory culture and to develop new stuff. People can submit their own projects by making a post on the platform which can then be tagged as a project if it's relevant and mature enough.

 * Projects section. List of projects with image and some text. Could for example be displayed like in the "Our projects" section on https://culturesquad.org/. Projects are retrieved through the [webcontent-participio-project tag](https://edgeryders.eu/tags/webcontent-participio-project). Clicking a project should bring you to a dynamically generated page based on the content of that post, like is the case with the events on the Culture Squad site (example: https://culturesquad.org/event/save-the-date-culture-culture-brussels-june-28/10142/). Page should also contain a button to "Join the conversation" linking to the thread. By the way, we will also add Pretix (and our custom stuff?), Loomio and other stuff here as examples of good open source shit to use.

 * Use cases section. List of use cases for the tools curated by Participio. This section is similar to the Projects section, but should be different enough that they can easily be told apart. For example, it could look similar to "Latest Topics", and when a card is clicked you are brought to a dynamically generated page like for the projects. This content is retrieved through the [webcontent-participio-example tag](https://edgeryders.eu/tags/webcontent-participio-example) tag.

 * Latest conversations section. This is a curated list of recent conversations. List could look similar to "Latest events" section at https://internetofhumans.eu. This content is retrieved through [webcontent-participio-featured tag](https://edgeryders.eu/tags/webcontent-participio-featured).

 * Partners section, also similar to http://opencare.cc/. Including Edgeryders, Blivande, The Borderland, Kulturbryggan.

## Site navigation 

Top menu similar to that on https://internetofhumans.eu, with links to Participate, Projects, Use cases

## Notes

As always, tell me if I'm being an idiot or requesting stupid stuff that we could solve in a saner way. Working with the two codebases available, there are examples for how to do all of the things above, but there is a lot of room for improvement. Also, I don't really have any graphical profile for you to work with, apart from that you might detect some slight consistency between the three sites mentioned above. 
