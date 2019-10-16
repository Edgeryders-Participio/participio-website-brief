# Participio website brief 

A website to present the projects collected and funded by the Participio project. Most of the content on the site will be retrieved from the Edgeryders Discourse platform by querying specific tags. This way of using Discourse as a CMS for websites has been done before, for the [Edgeyrders Festival](https://festival.edgeryders.eu/), [NGI Exchange](https://exchange.ngi.eu/) project, and [Wellbeing in Europe](https://wellbeing.edgeryders.eu/) project. 

These sites get their content dynamically from the Edgeryders.eu Discourse, through a custom built middleware caching app ([code on GitHub](https://github.com/edgeryders/edgeryders-now-api) and hosted at https://edgeryders.herokuapp.com. This new website for the participio project should also use this cache app. For now, fork the Edgeryders Now app, modify it and host it separately and then we will then merge changes into the main repo once it's done.

## Site sections

The Participio website should have the following sections:

 * A "hero" banner, similar to https://exchange.ngi.eu/ with text "A community collecting, curating and building software for participatory culture". Not dynamic. Should have button to "Join the community".

 * "How to Participate" section, also similar to that on https://exchange.ngi.eu/. Not dynamic. Copy TBD. Basically, will explain that Participio exists both to collect good existing apps for participatory culture and to develop new stuff. People can submit their own projects by making a post on the platform which can then be tagged as a project if it's relevant and mature enough.

 * Projects section. List of projects with image and some text. Could for example be displayed like in the "The People" section on https://festival.edgeryders.eu. Projects are retrieved through the [webcontent-participio-project tag](https://edgeryders.eu/tags/webcontent-participio-project). Clicking a project should bring you to the thread.

 * Use cases section. List of use cases for the tools curated by Participio. This section is similar to the Projects section, but should be different enough that they can easily be told apart. This content is retrieved through the [webcontent-participio-example tag](https://edgeryders.eu/tags/webcontent-participio-example) tag.

 * Latest conversations section. This is a curated list of recent conversations. List could look similar to "Latest events" section at https://exchange.ngi.eu/. This content is retrieved through [webcontent-participio-featured tag](https://edgeryders.eu/tags/webcontent-participio-featured).

 * Partners section, similar to the "What else are we working on?" at https://festival.edgeryders.eu/. Including Edgeryders, Blivande, The Borderland, Kulturbryggan.

## Site navigation 

Top menu similar to that on https://festival.edgeryders.eu/, with links to Participate, Projects, Use cases

## Notes

You can get a lot of this for free by starting with the code available at https://github.com/edgeryders/festival. However, the design can't be identical to that site and needs to differ substantially. I leave it up to you to come up with a good style for this as long as you feedback with me.
