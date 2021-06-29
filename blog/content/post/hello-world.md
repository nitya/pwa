---
title: "Hello World"
date: 2021-06-26T15:19:12-04:00
draft: true
tags: [fundamentals, performance, capabilities, case-studies, pwa-builder]
---

> New to this site? Read [about this project](/about) to understand the objectives and explore the learning resources on your own.

## Welcome!

"Hello World!" is typically the first program you write when starting a coding journey. It helps validate your development environment and gives you the foundational structure from which you build up your knowledge.

My "Hello World" blog posts serve a similar purpose. They validate my blogging setup and workflow, and help me set the stage for what I want to achieve with the content. So let's talk about both those things.

You're reading this now - I consider that #AchievementUnlocked on the first goal! So let me focus on the second! Let's talk about _All Things PWA_, starting with the basic questions:
 * What is it?
 * How is it different from other app frameworks?
 * Why should I learn it now?
 * What's next?


## What is a Progressive Web App?

Here's the simple Wikipedia [definition](https://en.wikipedia.org/wiki/Progressive_web_application). 

A Progressive Web App (PWA) is _a type of application software delivered through the web, built using common web technologies including HTML, CSS and JavaScript. It is intended to work on any platform that uses a standards-compliant browser, including both desktop and mobile devices._

And a more nuanced definition from ["web.dev"](https://web.dev/what-are-pwas/) site:

Progressive Web Apps are _web applications that have been designed so they are capable, reliable, and installable. These three pillars transform them into an experience that feels like a platform-specific application._

We can summarize the PWA value proposition with 3 points:

 * They're built with common _web technologies_ - lowers the learning curve.
 * They work _cross platform_ - target mobile, desktop and browser platforms.
 * They have _native-like_ experiences - comparable to platform-specific apps.
 
🚨 `Terminology Alert:` <br/>
From here onwards I'll use _platform-specific_ (instead of _native_) to refer to apps or experiences that reflect the look-and-feel associated with a specific device platfom or operating system.

## Why use a PWA?

We already have great frameworks and tools to develop web-apps (that run cross-platform, in the browser) and platform-specific apps (that are optimized to use innovative features and performance enhancements on the target OS). 

_Why do we even need progressive web apps?_ This image from [web.dev](https://web.dev/what-are-pwas/) gave me a glimpse into the value propositions that each class of apps provides.

![A graph plotting capabilities on Y axis vs. Reach on y-axis, with PWA at the top corner as a technology that delivers both ](https://web-dev.imgix.net/image/tcFciHGuF3MxnTr1y5ue01OGLBn2/1DKtUFjXLJbiiruKA9P1.svg)

Here's how I looked at it:

 * **Web Apps >** Have the _broadest reach_ and discoverability. They can reach anyone, anywhere, on any device - with a single codebase!
 * **Platform-Specific Apps >** Have the _best capabilities_. They feel like they're part of the device they run on, and take advantage of its built-in features.
 * **PWA >** Are built with web technologies and have _comparable reach_ to web apps. And they have enhanced web capabilities, reliability and installability - to give them a _comparable platform-specific experience_.


## PWA All The Things?

Not quite! 

As an application developer, or as a decision maker, you need to evaluate various tradeoffs before you pick your path. Some things to think through:

 * PWAs have [additional requirements](https://docs.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/#requirements) to ensure that platform-specific experiences behave consistently across mobile, web and desktop targets. _If your core audience is web-only, a traditional web app may be faster and easier to develop and support with modern frameworks and tooling._ 

 * PWAs depend on enhanced [web capabilities](https://developers.google.com/web/updates/capabilities) to deliver platform-specific experiences. Unlike platform-specific apps (which target a device family or app store, and can benefit from device-specific innovations), progressive web apps rely on open web standards that must be supported by major browser platform vendors, before they can be used by app developers. _If your application relies on a platform-unique software or hardware feature, a proprietary framework may suit best._ 
 
The good news: the path to PWA development and adoption is getting easier!
 * More **modern web frameworks** offer PWA support. <br/> _Ex: [Create-React-App](https://create-react-app.dev/docs/making-a-progressive-web-app/) has guidance for building a first-class PWA._
 * More **cross-platform app frameworks** offer PWA support. <br/> _Ex: [Flutter-Create](https://flutter.dev/docs/deployment/web#pwa-support) now offers PWA support in it's web template_
 * More **device platform vendors** are supporting PWA in their app stores <br/> _Ex: [Windows 11](https://blogs.windows.com/windowsexperience/2021/06/24/introducing-windows-11/) has
 [guidance](https://blog.pwabuilder.com/docs) on shipping PWA to Windows app store._
 * **Browser platforms** are closing the capabilities gap with device platforms. <br/> 
_Ex: [Project Fugu](https://www.chromium.org/teams/web-capabilities-fugu), an multi-org standards-driven effort on web capabilities._


## Why Learn PWA Now?

 *  **PWA hit an inflexion point in 2021** according to [Forrester](https://go.forrester.com/blogs/are-pwas-at-an-inflection-point/) given that _modern development systems are starting to provide the ability to generate PWA as an output format_.

 * **New PWA training was released** [by Google Developers](https://web.dev/new-pwa-training/) to reflect huge strides made in four years and _to teach you how to build reliable, installable, and capable Progressive Web Apps for all devices._

 * **New PWABuilder (v3) was released** [by Microsoft](https://www.pwabuilder.com/) with starter kits and guidance for [shipping PWA to app stores](https://blog.pwabuilder.com/posts/introducing-the-brand-new-pwa-builder/), including a report card that evaluates app-store readiness and suggests fixes if required.

What's next?

I'm collecting [learning resource](about/#learning-resources) for self-study and exploration. My plan is to _explore core concepts first_ using the [PWA training](https://web.dev/new-pwa-training/), then _explore development and workflow_ using the [PWA Builder](https://www.pwabuilder.com/) resources. I hope you can join me.