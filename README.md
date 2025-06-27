# WebDev Architecture

What is a good Architecture?
How to create better Web Apps, and what makes an App Good?

There is Stuff we see and Stuff we don't see. 

The Stuff we see is the View-Layer of an Application. The GUI, the Design, the though given into Colors, UX and UI.
But the Stuff what we don't often see is the Logic Layer. All the things which happen on the Background without us even noticing.
And this Stuff is imporant. The Problem? This Stuff changes. Often. 

Back in the day there were a lot of Problems seperating Logic and UI Elements from each other. Than came Programming patterns like MVC (Model View Controller) which gave a Simple Solution for avoiding confusion and give clearer separation of concerns in the Code. 

## What are the main Struggles of WebDevelopers Today?

You would guess it's writing code. But i guess writing code is the least problematic part of writing Apps.

The biggest Problem in Web is the change in modern WebDev which happens every 2-3 Years. 
We are changing tools, frameworks and technologies way too often. 

Someone could say: "so don't!" But not doing it is even worse!

I have worked on hundres of Projects in the past 10 years. And the past 10 years were crazy. 
We went from jQuery, Konckout, Meteor.js to Angular, React, Vue, and than to more Abstracted Layers like Gatsby, Next.js (Pages), Nuxt, Remix and than again to more refined Layers like Astro or soon TanStack.

And that's only Frontend Frameworks. There are also Bundlers, Packaging Tools, UI Libraries and Testing Frameworks.

And in every realm of things there is a change.

## Is the tooling better?

Yes. Older Tools just can't keep up with the Technological changes and get thrown away. 

"Deprecated" - Tooling is no longer supported.

But don't worry, we have a new shiny tool. But all you need to do is... Rebuild your whole Code-Base.

## Modern Architectural Approach

While Building Modern WebApps you need to consider that the tooling you are going to use, could change in 2-3 Years. 
The best way to achieve that is to keep all the Tools seperated in different packages or places in your App. Try to not mix Logic and UI View of your App together. It should be possible to replace the UI without even touching the elements of your app handling the Logic. 
