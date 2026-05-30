---
weight: 1
---

[About Me](#about-me) | [Skills and Tools](#skills-and-tools) | [Notable Credits](#notable-credits) | [Philosophy](#philosophy) | [Work History](#work-history) | [Education](#education) | [Fun Facts](#fun-facts)

## Skills and Tools

|**Category**|**Tools**|
|:---|:---|
|*CI/CD & Build*|Jenkins \| Fastlane \| Python-based build frameworks|
|*Version Control*|Perforce (P4D, P4V, Swarm, P4P) \| GitHub (administration) \| Git|
|*Languages*|Python \| Bash/Shell \| Groovy \| C++ \| HTML|
|*Cloud & Infrastructure*|AWS \| On-Prem/On-Metal \| Colocation|
|*Game Engines*|Unreal Engine \| Unity|
|*Shipped Platforms*|iOS \| tvOS \| macOS \| Android \| Windows \| PlayStation 4|
|*Stores Shipped To*|Google Play Store \| Apple Store Connect \| TestFlight \| Apple Arcade \| Steam|
|*IDEs*|PyCharm \| Rider \| VS Code \| Visual Studio|
|*Art Tools*|Affinity Designer \| Affinity Photo|

## About Me

In my 20 years in the game industry, I’ve had the privilege of contributing to some great franchises such as Temple Run and Gears of War all the time working alongside some truly amazing people.  It’s mind boggling to think that the products we worked on have been played by millions and millions of people.  The Temple Run franchise alone has over a billion downloads.

For the last eight years, I've served as the sole DevOps/Build Engineer and Perforce Administrator at Imangi Studios.   I owned everything from CI/CD pipelines and build farm infrastructure to developer support and source control administrator for a studio with distributed workforce. My colleagues call me the Perforce wizard because I've made sure that any issue they had was dealt with quickly as well as providing know-how through documentation, videos, and to make sure others can become wizards too.

My career has been defined by being the one assigned to the projects no one else wanted. I’ve taken on everything from figuring out automation testing in Unreal Engine, to inheriting a home‑brew CI/CD system, to suddenly becoming the owner of the Perforce server because the senior engineers were done with it. I don’t mind a challenge, and I’m always ready to learn something new.

Reliability and kindness are the two things I want to be known for. I care genuinely about the people I work with and when someone's stuck, I want to help, and when things go wrong, I'd rather we figure it out together than point fingers. I try and want to be the kind of teammate who shows up, shares what they know, and leaves the team better than they found it.

I also like leaving my mark in small ways where ever I am.  That would include such things as fist-bumping everyone and the camera at the end of a virtual meeting, leaving an inspirational quote on the office coffee carafe, or spending way too long Photoshopping a colleague's face onto a baseball card just to make them laugh.

Outside of work, I’m big into baseball as I have coached my kids' team for several seasons, and I still play as an adult in a local men's recreation league.  I’m also a life-long Magic the Gathering collector who’s recently got back into playing.   I’m also a gamer as well which should go without saying.  I enjoy making my own board, cards, and video games at home too.

## Notable Credits

- Temple Run Legends | Temple Run 3 | Temple Run 2 | Temple Run 1 | Temple Run+ | Temple Run Idle
- Radical Heights
- LawBreakers
- Fortnite
- Infinity Blade Series
- Gears of War Judgement | Gears of War 3 | Gears of War 2 | Gears of War 1
- Unreal Tournament 3
- Unreal Engine 4 | Unreal Engine 3 | Unreal Development Kit (UDK)

## Philosophy

**Developer-First Engineer** -- My goal is to make every developer around me more impactful by eliminating friction and creating an environment where they can feel confident and engaged with their work. I also make it clear that no one has to suffer in silence. If someone is stuck, uncertain, or overwhelmed then I’m the person they can come to. This is achieved by:

- Being available and open for communication.
- Following up.
- Automating mundane tasks.
- Writing tools and scripts to assist with their task.
- Listening to feedback.
- Collaborating with the dev on their workflows and processes.
- Providing and writing documentation.
- Creating short support videos. <- very effective
- Never being rude or talking down to them.

**The spice must flow** -- The goal is to ship and to ship on time. If you want to gain the most value from a product, you must keep development moving smoothly and predictably. No one wants the emperor mad at them. This is achieved by:

- Identifying any potential future issues.
- Promoting processes and workflows that'll keep bigger issues at bay.
- Determine any action items from a blocking issue.
- Document major blockers and fixes.
- Fixing items before they reach the developers.
- Working with the developer who caused a blocker to prevent it from happening again.
- Notifying others of the issue.

## Work History

**Lead DevOps Engineer**
| Imangi Studios, LLC | *May 2018 – May 2026*

Walked into a studio with no CI/CD pipeline and a Jenkins server that had already been abandoned once. Rebuilt it from the ground up, this time to last. Designed and implemented a full build and release workflow using Jenkins backed by an on-premise farm of Mac Minis, which later moved to colocation with AWS to scale it when necessary. To make pipelines something developers actually wanted to use, I authored a Jenkins shared library and introduced pipelines-as-code, making builds more reliable and far easier to maintain.

On top of that, I became the sole owner of the studio's Perforce infrastructure, administering and supporting version control for a worldwide team of up to 90 developers across several countries. If the depot went down, that was my problem to fix and thankfully that was a very rare occurrence.

Reducing friction is something I enjoy doing. I built out a knowledge base of documentation and around 300 short-form support videos covering everything from Perforce workflows to Jenkins usage to Unity so developers could unblock themselves without filing a ticket. I also handled the setup of Google Play and Apple App Store presences for new projects, and worked closely with QA and dev teams to keep the path from code to shipped build as smooth as possible.

Jenkins | Python | Groovy | Perforce | GitHub | AWS | Unity | Google Play Store | Apple Store Connect | Macs | Scripting

**Build Engineer**
| Boss Key Productions | *Oct 2015 – Apr 2018*

Inherited a custom build system in Python built by the lead engineer which was functional, but missing most of what you'd expect from a CI/CD pipeline: no messaging, no scheduling, no error reporting, no artifact storage. With LawBreakers moving fast toward ship, there was no time to swap in a new framework, so I extended what was there. I built out the missing core capabilities myself — Slack and email notifications, task queuing, error reporting, scheduling, multi-project support, app signing, local game server test launching, and artifact storage. Then came the optimization pass: by the end, full builds of LawBreakers went from two and a half hours down to 30 minutes.

Alongside the build system work, I owned Perforce support for the studio handling developer issues, managing branching strategy, and creating new depots as the project grew. I also wrote internal tooling to automate common Perforce tasks and save developers the tedium. With all infrastructure on-premise (Perforce, CI/CD servers, and storage) storage capacity management was a constant responsibility, especially given the project's size and the volume of DDC data that accumulated over time. While there I also managed Incredibuild.

Python | Unreal | Linux | Windows | Steam | HTML | Javascript | Perforce | On-Premise Infra | Incredibuild | Scripting

**Associate QA Engineer / Automation Test Coordinator / Software Tester**
| Epic Games, Inc. | *Sep 2006 – Sep 2015*

The first half of my career was rooted in testing and supporting Unreal Engine. It's where I learned what it actually means to be a developer; how to test and troubleshoot, how to build levels and content in the Unreal Editor, how to write and compile code, how to ship, and how to support the people around me without hoarding knowledge.

*Aug 2015 — Sep 2015*

Shifted into automation when Epic needed someone to bring test automation to life inside Unreal. Got up to speed on the Unreal Engine automation framework, then turned around and taught it to others. Partnered with external companies to expand the framework and accelerate test coverage. Also used the role to improve internal developer workflows with one example being a validation task for the UE Marketplace team that automatically checked submitted content and surfaced errors, cutting down their review cycle considerably.

*Aug 2008 — Aug 2015*

Led a team of 15 software testers through years of Unreal Engine releases: UE3, UDK, and UE4. The milestone I'm most proud of: consistently shipping monthly engine updates to licensees and the public without missing a beat. Keeping that cadence reliable across a team of 15, over multiple engine generations, for years, is the kind of thing that looks easy from the outside and isn't. On top of that I also created a lot of test content and levels using the Unreal Engine along with a lot of written test documentation as well. Supported the local artists and engineers with their Unreal Engine and Perforce issues.

*Aug 2006 — Aug 2008*

Where it all started. Black-box tested Gears of War 1, Unreal Tournament 3, and Gears of War 2 across PC, Xbox 360, and PS3 — campaigns, multiplayer, mod support, certification bugs, and everything in between. Learned early how to communicate a bug clearly enough that a developer could actually reproduce and fix it.

| Unreal Engine | Unreal Editor | Perforce | QA Testing | Test Track Pro | Python | Perl | MS Excel and MS Word | Windows | Linux

## Education

B.A. in Multimedia (Game Design Emphasis) – University of Advancing Technology, Tempe, AZ – 2006

## Fun Facts

- I have a design credit in Gears of War: Judgment for making the the [Junkyard](https://youtu.be/m3m_9wyx50A?si=I4xT4q5H4uxt7AMG) multiplayer map. I designed it, shelled it, and iterated on it based on playtest feedback while an artist made it look like an actual place.
- I won first place in the World of Level Designs ["Storytelling Level Design Challenge"](https://www.worldofleveldesign.com/categories/level_design_challenges/storytelling2-2012-level-design-challenge-04-top-5-and-winner.php). Using the UDK, I handcrafted a small scene built around a single quote about fire and loss. You can see the final result here: [NightCluckers entry](https://youtu.be/286i7U26yEU?si=AyclIzHKsPDhfBXy)
- I was a volunteer travel league baseball coach for ages 9-13 for several years.  A lot of work, genuinely one of the most rewarding things I've done.
- Baseball doesn't stop at coaching. I still play in a local adult rec league.
- My all-time favorite game is Wing Commander.
- One of my first real jobs was raising chicken for Foster Farms... I'll occasionally just start talking about my time there in what my friends call my "chicken stories".  It was a... memorable time.

<div class="about-images">
  <img src="/images/me_circle_01.png" alt="This is me">
  <img src="/images/me_circle_00.png" alt="This is me, too">
  <img src="/images/me_circle_02.png" alt="This is me pretending to be a middle manager.">
  <img src="/images/me_circle_03.png" alt="This is me looking tough, as the kids would say.">
  <img src="/images/me_circle_04.png" alt="This is me looking tough, as the kids would say.">
</div>

[Back to top](#about-me)
