# Speaking
I love teaching, sharing knowledge and speaking at conferences. Ping me on [Twitter](http://twitter.com/steipete) or via [Email](mailto:steipete+speaking@gmail.com).

## Upcoming Talks and Interviews in 2021

Location | Date | Conference
---------|------|------------
Remote | April 16 2021 | Swift Heroes Digital 2021

![BA: Swiftable in Buenos Aires](https://raw.githubusercontent.com/steipete/speaking/master/Pictures/baswiftable-1.jpg)

![Pioneers 2019 in Vienna](https://raw.githubusercontent.com/steipete/speaking/master/Pictures/pioneers-2019-6.jpg)

[![dotSwift 2018 in Paris](https://raw.githubusercontent.com/steipete/speaking/master/Pictures/dotSwift2018-4.jpg)](https://www.dotconferences.com/2018/01/peter-steinberger-binary-frameworks-in-swift)

[![try! Swift  in New York, USA](https://github.com/steipete/speaking/blob/master/Pictures/try-swift-nyc-2018-2-small.jpg?raw=true)](https://speakerdeck.com/steipete/hacking-marzipan)

Ping [@steipete](https://twitter.com/steipete) on Twitter or reach out via email (steipete at gmail) if you organize a conference where you'd like me to speak. I direct the day-to-day work as CEO of [PSPDFKit](https://pspdfkit.com) and also share knowledge on our [company blog](https://pspdfkit.com/blog/all/).

### Topics 2021

### Evolving existing Projects with SwiftUI

We're looking into strategically evolving existing older projects (that still contain Objective-C) with SwiftUI. We explore different strategies to support down to iOS 12 and how to work around shortcomings of SwiftUI 1.0. (WIP - TALK WILL EVOLVE)

This talk will be made speficically for Swift Heroes Digital 2021

### Continuous Integration for the Rest of Us

Every project benefits from a good Continuous Integration & Delivery system. While there's countless articles on the latest Swift or SwiftUI tricks, there's surprisingly little talk about strategies around CI & CD. You will find case studies by industry giants like Shopify or Uber that talk about their solutions, however their CI/CD team in many cases is larger than some middle-sized companies.

At PSPDFKit, we don't have a separate team for CI/CD, our engineering team also owns testing and delivery. In this talk I'll give you an overview of the options today, and will explore what path we took for fast, automated testing in a multi-platform environment. We'll also talk about money, because running cost is an important topic for bootstrapped companies. Lastly, we'll look at options around configuration management tools to automate machine setups.

This talk was made for iOS Conf SG 2021. [slides](https://speakerdeck.com/steipete/continuous-integration-for-the-rest-of-us) [video](https://vimeo.com/503127515)

Feedback from Attendees via Zoom: "thank you. great talk." "Peter! I'm impressed by your optimism :)" "Super cool the script about removing default apps, adding that to my dot files!" "Honestly installing Xcode on just one machine does it for me!" ["Thank you Peter, amazing talk 👏🏻👏🏻👏🏻"](https://twitter.com/zntfdr/status/1352569199705513985?s=21)

### Topics 2020

### Building a PDF Viewer in 40 Minutes (aka Wrapping a Complex View Controller in SwiftUI)

Follow me along as I take the main view controller of PSPDFKit and wrap it into a SwiftUI view, add custom configuration properties, make methods on the view controller accessible via Combine publishers, use a Coordinator to wrap the delegate into modern closures and call pre-built popovers from a SwiftUI Navigation Bar. This will be a Xcode coding session where I explain the concepts as I'm building the component. We look at tradeoffs with iOS 13 vs iOS 14 compatibility, some tricks to work around bugs, SwiftUI lifetime, considerations for Combine cancellables and much more.

Feedback via Brella: Tim Oliver: Oh man. Damn that's impressive Peter!, Cristina De: Thank you very much Peter! 👏🏻👏🏻👏🏻👏🏻👏🏻, Moein Barzegaran: Thanks Peter!, Sammy Smallman: Thanks Peter, that was awesome!, Nissi Miranda: Very good! 😄, Fernando Bunn: Really awesome talk Peter.

This talk was hand-crafted and recorded for Swift Heroes Digital 2020. [video](https://vimeo.com/463560058)

### UI Testing over the years

UI testing has been around since iOS 4, but it never really caught on. I've asked various members of the iOS community about their experience and tips. Join me on a trip of different frameworks, strategies and tools to find a solution that fits your app. You will hear about KIF, EarlGrey, XCU and various open source projects to help you write better tests, to parallelize them or even to remind you to write tests. "
Feedback via hopin.to: [Daniel Steinberg](https://twitter.com/dimsumthinking): nice job @Peter Steinberger thanks, Alexander Lonsky thanks Peter!, Thomas Besnehard: 👏👏👏👏, Hugo Saynac: Congrats, great talk 👏, Heiko Goes: Thanks a lot Peter for this extensive overview, Seán Labastille (Organizer): 👏 👏 👏 👏, Shai Mishal: Great overview, thanks !, Vincent Pradeilles: Thank you!, Paris Buttfield-Addison: Fabulous talk, thanks!, Andrea Antonioni: Great talk!!, Andreas Hegenberg: 👍👍 very nice!, Eben Kok: That was awesome!, Alexander Weiß: Very interesting talk !, Martin Fitzka-Reichart: Great talk Peter!!, Matej Malesevic: thanks a lot 👏👏👏, ["very informative talk about UI testing."](https://twitter.com/ekurutepe/status/1259781082225967105?s=21),  ["When can I watch this over and over again please?"](https://twitter.com/ashtondev/status/1259788241005211649?s=21)

This talk was hand-crafted and recorded for App Builders 2020. [slides](https://speakerdeck.com/steipete/ui-testing-over-the-years), [video](https://vimeo.com/416980950)

### Supporting Pointer Interactions in iPadOS 13.4 

With the just released iPadOS 13.4, Apple added support for trackpad and mouse devices! Watch me life-coding support for pointer interactions into a large project ([PSPDFKit](https://pspdfkit.com/), a PDF SDK) using Xcode 11.4 and Swift. You'll learn how the API works, how you can create bezier paths in-code (and what tools are there to help), and how to structure the handler in a way that is easy to read and extensive. We'll also discuss a few tricks and hacks how to make progress faster, how to make buttons react to events, and official and unofficual ways how to differentiate between finger touches and pointer taps.

This talk is based on my blog post [https://pspdfkit.com/blog/2020/supporting-pointer-interactions/](https://pspdfkit.com/blog/2020/supporting-pointer-interactions/) but is much more hands-on and shows a few tricks we learned since then.

Feedback from Attendees: (Via ClickMeeting Platform) Tiago Mergulhão: OMG! SO COOL!, Christian Beer: One more thing! Thank you very much, Peter! That was really awesome!!, Akshat Patel: hahaha now THIS looks like real code, Stefan Steinbauer: Thanks for the ride, Nico du Plessis: Awesome session!, Liviu C: haha. nice tweak!, Mostafa: Thank you 👏, J.B.: *Good stuff, Peter, Mosbah: That was really cool thx !, Joao Pereira: great stuff! Thanks Peter & the organizers, Alexander: Peter, thank you very much! I'm always amazed at how you instantly manage to support new things, very grateful for doing pioneer work. By the way, besides this webinar and the aforementioned blog post by Peter I can highly recommend Apple's HIG article covering pointers in user interaction chapter and pretty decent sample code "Integrating Pointer Interactions into Your iPad App"., Gerry (WeAreDevelopers): Great session, thank you Peter!, Tamas Jaroli: Thank you Peter, this was amazing!, Eben: Pete that was epic!, Sead: Thanks Peter, it was awesome!

[video](https://www.youtube.com/watch?v=Yt3xVRYhDek&feature=emb_title)

### Contributing to PDFium (exclusive for PDF Days 2020 Berlin)

Learn how PSPDFKit builds on and improves world’s most popular PDF library.

Companies like Google, Microsoft, Opera, LG and Dropbox are working together to commoditize PDF render technology. The future is open source, fast and fuzzed/well-tested.

We walk you through the many powerful features of PDFium, where it can be used, and how you can contribute to the most used PDF library in the world.

### Topics 2019

### Shipping a Mac Catalyst app: The good, the bad and the ugly

PSPDFKit ported [PDF Viewer](https://pdfviewer.io), a project with over 2 MLOC and lots of UIKit code to the Mac via Catalyst. Having played with "Marzipan" in 2018, the team was able to port their huge app in a relative short timeframe. Learn what you have to do after checking the [X] Mac checkbox, how far Catalyst can be pushed, how it interacts with AppKit, and how to work around the worst bugs. We'll show real code, a selection of r̵a̵d̵a̵r̵ Feedback Assistant items, strategies to keep code branching low, and some design alterations that were necessary to make it feel more at home on the Mac." ([video](https://www.youtube.com/watch?v=Xo3zGlyxXcI), [slides](https://speakerdeck.com/steipete/shipping-a-mac-catalyst-app-the-good-the-bad-and-the-ugly))

Feedback from Attendees: ["Just learned a whole lot about the real life process for PSPDFKit to ship with Catalyst! Awesome talk by the one and only @steipete !"](https://twitter.com/Sommer/status/1180098843649744905), ["Peter 
@steipete is talking about not great and yet not terrible experience of shipping a Catalyst app 🚀"](https://twitter.com/Valzevul/status/1180095764619579394), ["“SwiftUI is the Austin Powers of frameworks: cool, if you like to live dangerously.” – @steipete at @mobiconf"](https://twitter.com/twostraws/status/1180089950940864514), ["Can’t wait to see what great things @steipete has to say about this year’s Xcode GM releases 😜"](https://twitter.com/chriscombs76/status/1180086470150955013), ["The excellent @steipete is sharing his experience porting the PsPdfKit app to Catalyst. So many holes he had to polyfill... Exceptional work! "](https://twitter.com/imerir/status/1181552646597091329), ["@steipete sharing the @PSPDFKit adventures on shipping a Catalyst app. Good stuff! #frenchkit"](https://twitter.com/basthomas/status/1181549689239478272), ["@steipete giving us a great talk on Catalyst @frenchkitconf #FrenchKit "](https://twitter.com/twannl/status/1181546535462604801), ["Amazing talk from @steipete showing us we just have to check a box to run our iPadOS app on macOS!"](https://twitter.com/Dimillian/status/1181545762112655360), ["Catalyst without cataclysm"](https://twitter.com/frenchkitconf/status/1181545485238226944), ["What was great about ⁦‪@steipete‬⁩ talk at ⁦‪@frenchkitconf‬⁩ ? You learn about technical stuff and you got a new movie to watch. Amazing talk btw !"](https://twitter.com/keuha/status/1181813133914071040?s=11), ["Thanks for sharing! Awesome talk, very interesting and funny :)"](https://twitter.com/FedeJordan90/status/1200157663600029707), ["@steipete
 talk about macOS catalyst at #BASwiftable was mindblowing. Thanks!"](https://twitter.com/betzerra/status/1200142915588284416), ["💪🏻 @steipete @baswiftable #swiftable"](https://twitter.com/__depa/status/1200139378519158784)

### How We Work at PSPDFKit

I explain our approach to SDK design, long-term product evolvement, feature/proposal development and support. This talk is interesting to developers and product planners alike. ([slides](https://speakerdeck.com/steipete/how-we-work-at-pspdfkit), [blog post](https://pspdfkit.com/blog/2019/how-we-work/))

### Should You Seek VC Money?

We discussed the up- and downsides of taking VC money vs boostrapping a business.
Many thanks to Natalie, Marcus, Anna for being great panel partners, the whole Pioneers team for being incredibly well organized and Florian for the tough audience question that later lead to an episode in his “Gründer&Zünder” podcast. 
Pioneers 2019 Photos (c) Emil Chalhoub for Pioneers

### Topics 2018

#### Hacking Marzipan

I will show the hacks currently needed to try Apple's new iOSMac platform, codenamed "Marzipan", and walk through what I needed to do to get [PDF Viewer](http://pdfviewer.io/) to run on macOS Mojave. Learn about the history, the current status, the timeline, and how to port your app today. [See preview research tweet](https://twitter.com/steipete/status/1006292370160316418)

Early version of this talk given [at mDevCamp 2018](https://twitter.com/mDevCamp/status/1007557562714279936), one week after the release of Marzipan.

Talk completely re-imagined at [try! Swift New York, Sept 5, 2018](https://www.tryswift.co/events/2018/nyc/#). [Slides](https://speakerdeck.com/steipete/hacking-marzipan) [Video](https://www.youtube.com/watch?v=2OuQarA0a7I)

Feedback from Attendees: ["Marizpandemic is coming."](https://twitter.com/PaulSolt/status/1037403766318931970), ["Awesome talk – really educational *and* entertaining 👏"](https://twitter.com/irace/status/1037408339444023296), ["excellent black magic"](https://twitter.com/stevenhepting/status/1037408730055364608), ["Having my mind blown (again)"](https://twitter.com/ioveracker/status/1037409108637433856), ["I can’t wait for Marzipan so I can get away with never having to learn AppKit!"](https://twitter.com/EugeneBelinski/status/1037404393769984001), ["words to live by"](https://twitter.com/bertadevant/status/1037405944097980416), ["Having fun with Marzipan"](https://twitter.com/BasThomas/status/1037406147047776258), ["Crash once  return 0, crash twice return it with 1 ... 😂😂😂"](https://twitter.com/lamar3_/status/1037407183682633730), ["educational and entertaining, well done 👍"](https://twitter.com/marwanalany/status/1037416514733961218), ["I would have liked to be there for this one!"](https://twitter.com/jcsorin/status/1037412673288396800)

#### Building Personal Brands for Introverts

Having a successful online identity will open many doors and help you to become a better developer, and person as a whole. I've been working on my professional persona since 2009, and it helped me so tremendously and pushed me forward into places I didn't think I could ever go.

This is the keynote talk for UIKonf for Day 2. [slides](https://speakerdeck.com/steipete/building-personal-brands-for-introverts) | [video](https://www.youtube.com/watch?v=0c6izSzP-KQ)

Feedback from Attendees: ["highly recommended"](https://twitter.com/cldrr/status/996313380112781312), ["really awesome"](https://twitter.com/christian_beer/status/996312445156249600), ["FANTASTIC talk, funny slides, nice pace"](https://twitter.com/akosma/status/996312176271949825), ["Absolutely inspiring. One of the most important skills in our field."](https://twitter.com/_harishussain/status/996308243956760576), ["Brilliant, powerful, warm, full of empathy"](https://twitter.com/qnoid/status/996308509246574592), ["very inspiring, motivational... feeling energized"](https://twitter.com/Shashikant86/status/997751919304237056)

#### Bootstrapping - The Long Road to Success

As part of the Founder & Investor Talks at Vienna University of Technology of 2018 I'll talk about my road from a freelancer to CEO of a succssful, growing international company with a deliberate choice of not taking VC money. This talk is about upsides/downsides and many lessions learned, the hard transition from "builder" to "manager", about teaming up with other people, building a team, core values, and strategies how to make a product work that sells B2B.

[I gave a variation of this talk as interview about Entrepreneurship at App Builders 2018 in Lugano. Watch here.](https://www.youtube.com/watch?v=eJ_BdSBxCZk)

[A quick summary video from my talk at the Vienna University of Technology from the i²c Founder & Investor Talk series](https://www.youtube.com/watch?v=CwZs64AnJf8)

Feedback from Attendees: ["Beautiful, eyes opening argument, funny stories"](https://twitter.com/PatrykPeszko/status/986494964631769089), ["Loved it! Detailed personal developer stories like this one are what make these conferences so interesting"](https://twitter.com/JosselinPello/status/986346792114642944), ["Inspiring tech entrepreneurship story"](https://twitter.com/krips/status/986162633958047744), ["Super interesting"](https://twitter.com/_Caro_N/status/986159569477996545), ["FANTASTIC talk, lots of wisdom and funny anecdotes"](https://twitter.com/akosma/status/986165844655968257)

#### Smart Debugging - Heavy Weapons for Hard Bugs

Debugging can be exciting, but often also very, very frustrating. We explore some lesser-known tools and techniques to find problems faster and make the Compiler mark issues, before they become a crash for the user. The second part is a case study of a particularily interesting bug hunts where I use some unconventional ways to find and resolve the issue. 

[slides](https://speakerdeck.com/steipete/smart-debugging-heavy-weapons-for-hard-bugs) [video](http://www.swifttube.co/video/smart-debugging)

Feedback from Attendees: ["really great structured overview"](https://twitter.com/mrackwitz/status/973306220244238337), ["great talk"](https://twitter.com/JaqBaldwin/status/973565519575113728), 

#### Strategies for Binary Frameworks in Swift

Binary frameworks? Without ABI? In Swift? What’s the deal with Swift Modules? In his talk, Peter discusses binary frameworks and stability, when and why ABI matters, and why his team writes in Objective-C. Learn more about what you can do right now, what other companies are doing, common pitfalls, and the future.

[slides](https://speakerdeck.com/steipete/binary-frameworks-in-swift) | [blog post](https://pspdfkit.com/blog/2018/binary-frameworks-swift/) | [video and transcript](https://www.dotconferences.com/2018/01/peter-steinberger-binary-frameworks-in-swift)

[Swift Weekly Shoutout](https://twitter.com/swift_weekly/status/963823928694239234), [Most Interesting Videos of dotSwift](https://twitter.com/flawlessappio/status/964526276026478592)

### Topics 2017

#### Building a Sustainable Codebase: 7 Years and Counting

Peter will discuss strategies how code can be written in a way where you can both 'ship it' and have a sustainable product that allows you to move fast and where new people don't run away screaming. At least most of the time :)

The talk is based on lessons learned while building PSPDFKit for iOS since 2010, yet most parts will be applicable to any language and team.

[video @ App Builders Switzerland 2017](https://www.youtube.com/watch?v=AxF2NuDKxdY)

#### Effective Remote Communication

How to Run a Distributed Company. ([video](https://vimeo.com/235530912) | [slides](https://speakerdeck.com/steipete/effective-remote-communication-how-to-run-a-distributed-company))

### Past Talks

#### 2021

Location | Date | Conference
---------|------|------------
Singapore (Remote) | Jan 20-21 2021 | iOS Conf SG [slides](https://speakerdeck.com/steipete/continuous-integration-for-the-rest-of-us) [video](https://vimeo.com/503127515)

#### 2020

Location | Date | Conference
---------|------|------------
Paris, France | April 2 | [Swift Paris Online #2](https://www.meetup.com/swiftparis/events/269742426/)
New York, US | April X | Spotify Engineering Conference (Cancelled, COVID-19)
Remote | April 15 | [WeAreDevelopers Live](https://twitter.com/WeAreDevs/status/1250050045921177602)
Berlin, Germany | April 27-29 | PDF Days Europe (Cancelled COVID-19)
Lugano, Switzerland | May 11-12 | App Builders (Remote, COVID-19) ([video](https://www.youtube.com/watch?v=LpHah3oQeyg))
Aveiro, Portugal | June 25th - 26th | SwiftAveiro (Cancelled COVID-19)
Brazil | Nov 5-6 2020 | NSBrazil (Cancelled COVID-19)
Remote | Oct 1-2 2020 | Swift Heroes Digital 2020 ([video](https://vimeo.com/463560058))

#### 2019

Location | Date | Conference
---------|------|------------
Karlsruhe, Germany | Dec 3-4 | [heise MacDev 2019](https://heise-macdev.de/)
Buenos Aires, Argentina | Nov 28-29 | [Swiftable](https://swiftable.io/)
Berlin, Germany  | Nov 12-13 | [{codemotion} Berlin](https://events.codemotion.com/conferences/berlin/2019/) (Cancelled)
Paris, France    | Oct 8-9 | [FrenchKit](https://frenchkit.fr/) ([video](https://www.youtube.com/watch?v=Xo3zGlyxXcI) [slides](https://speakerdeck.com/steipete/shipping-a-mac-catalyst-app-the-good-the-bad-and-the-ugly))
Kraków, Poland   | Oct 3-4 | [Mobiconf 2019](http://mobiconf.org/)
San Jose, California | June 4 | [AltConf](https://twitter.com/MacStadium/status/1136051430073090048) (Talk about CI Infra) ([video](https://www.youtube.com/watch?v=EHoT_RyriJk&list=PLljEvxF6pJBBSQXDRnQvACukLJGybS17O))
Vienna, Austria  | May 8-10 | [Pioneers'19](https://pioneers.io/pioneers19#/)
Budapest, Hungary| April 12 | [iOS Conf Budapest](https://iosconfbudapest.com/) [Cancelled]
Vienna, Austria  | Feb 21 | [Apple Store Vienna](http://apple.at) Talked about How We Work at PSPDFKit
Porto, Portugal  | Feb 4 | [CocoaHeads Porto](https://www.meetup.com/CocoaHeads-Porto/events/258522920/) Talked about How We Work at PSPDFKit

#### 2018

Location | Date | Conference
---------|------|------------
New York, US | Sept 4-5, 2018 | [try! Swift](https://www.tryswift.co/events/2018/nyc/) - Hacking Marzipan ([slides](https://speakerdeck.com/steipete/hacking-marzipan) [video](https://www.youtube.com/watch?v=2OuQarA0a7I))
Vienna, AT | July 12, 2018 | [Cocoaheads Vienna](http://cocoaheads.at/), Talk about Marzipan
Prague, CZ | June 15, 2018   | [mDevCamp](https://mdevcamp.eu/), 2 Talks: [iOS part of the Keynote](https://twitter.com/hello_paja/status/1007554093924192259) + [Highlights of WWDC 2018 & Hacking Marzipan](https://twitter.com/mDevCamp/status/1007557562714279936)
San Jose, US | June 4-8, 2018 | WWDC 2018 (No talk, but let's meet up!)
Berlin, DE | May 14-16, 2018 | [PDF Developer Days](https://www.pdfa.org/save-the-date-pdf-days-europe-2018-may-14-16/)
Berlin, DE | May 13-16, 2018 | [UIKonf](http://www.uikonf.com/) - Building Personal Brands for Introverts ([slides](https://speakerdeck.com/steipete/building-personal-brands-for-introverts) [video](https://www.youtube.com/watch?v=0c6izSzP-KQ))
Vienna, AT | April 25, 2018 | [Founder & Investor Talks at Vienna University of Technology](https://i2c.ec.tuwien.ac.at/home/events-1/founder-investor-talk-series/) ([event](https://www.eventbrite.com/e/i2c-founder-investor-talk-bootstrapping-the-long-road-to-success-by-peter-steinberger-tickets-43095087567))
Lugano, CH | April 16-17, 2018 | [App Builders Switzerland 2018](https://www.appbuilders.ch/) ([video](https://www.youtube.com/watch?v=eJ_BdSBxCZk))
Atlanta, US | March 12-14, 2018 | [Teki Con🍍](https://teki-con.com/) ([slides](https://speakerdeck.com/steipete/smart-debugging-heavy-weapons-for-hard-bugs))
Paris, FR | January 29, 2018 |  [dotSwift 2018](https://www.dotswift.io/) ([slides](https://speakerdeck.com/steipete/binary-frameworks-in-swift), [blog post](https://pspdfkit.com/blog/2018/binary-frameworks-swift/), [video](https://www.dotconferences.com/2018/01/peter-steinberger-binary-frameworks-in-swift))

#### 2017 and Earlier

Location | Date | Conference
---------|------|------------
Logroño, Spain | Sept 13-15, 2017 | [NSSpain](http://www.nsspain.com/) ([Video on Vimeo](https://vimeo.com/235530912))
Berlin, Germany | May 27, 2017 | [STICKS & STONES](http://www.sticks-and-stones.com/)
Vienna, Austria | May 11-12, 2017 | [WeAreDevelopers](http://www.wearedevelopers.org/) ([video](https://www.youtube.com/watch?v=wOuth_7xj8Y))
Budapest, Hungary | April 25-28, 2017 | [CRAFT Conf](https://craft-conf.com/) ([Video on UStream](http://www.ustream.tv/recorded/102891080))
Lausanne, Switzerland | April 24, 2017 | [App Builders](https://www.appbuilders.ch/) ([Video on YouTube](https://youtu.be/AxF2NuDKxdY))

Between 2013-2016 I've given talks at following conferences: (list incomplete, PRs welcome!)

https://vimeopro.com/steipete/conference-talks-peter-steinberger

* [UIKonf](http://www.uikonf.com/) 2013 (Berlin, DE) - [How to bend UIKit to your will.](https://www.youtube.com/watch?v=psPNxC3G_hc)
* [NSConference](http://nsconference.com/) (London, UK)
* [Top Devs Share Their Reactions to WWDC 2016](https://academy.realm.io/posts/wwdc-2016-developer-perspective/) (San Francisco, US)
* [NSSpain](https://nsspain.com) 2012 and 2017 - (Logroño, Spain) - How to Run a Distributed Company. ([video](https://vimeo.com/235530912) | [slides](https://speakerdeck.com/steipete/effective-remote-communication-how-to-run-a-distributed-company))
* [AltTechTalks Berlin](http://www.alt-tech-talks.com/) - Foundation Collection Classes (Berlin, DE)
* [Mobile Central Europe](https://2014.mceconf.com/) (Poland) - Practical Runtime Hackery ([video](https://www.youtube.com/watch?v=frgnVhBcIFA))
* [⌘R Conf 2014](https://twitter.com/cmdrconf) (London, UK) - Scaling Your Indie Business ([video](https://www.youtube.com/watch?v=0iQeaoP3Nh8))
* [Istanbul Tech Talks](http://www.istanbultechtalks.com/) (Istanbul, Turkey) ([highlights video](https://vimeo.com/istanbultechtalks/ittpromo#t=81s))
* [AltConf](http://altconf.com/) (San Francisco, US) - [Objective] C++: What Could Possibly Go Wrong? ([video](https://academy.realm.io/posts/altconf-peter-steinberger-objective-c++-what-could-possibly-go-wrong/)) ([One of the 5 most popular talks of AltConf 2015!](https://academy.realm.io/posts/most-popular-altconf-2015-videos/))
* [WeAreDevelopers](https://www.wearedevelopers.com/) (Vienna, AT) -  Building a sustainable codebase: 7 years and counting ([video](https://www.youtube.com/watch?v=wOuth_7xj8Y))
* [Bacon Biz](http://baconbiz.com/) (Philadelphia, US)
* [Macoun](https://macoun.de/) (Frankfurt am Main, DE)
* [Cocoaheads](https://cocoaheads.at/) meetups in Vienna, Germany, Ukraine, [Stockholm](https://speakerdeck.com/steipete/building-aspects) and abroad.

[Video Recordings for some of my talks can be found at my Vimeo.](https://vimeopro.com/steipete/conference-talks-peter-steinberger)

### Bio

>Peter founded and bootstrapped PSPDFKit in 2011 and since then grew the company to 50 employees, with the goal of providing the highest quality PDF framework for all platforms. He stepped down as CEO in late 2019 and moved to a research role to focus on new products and technologies. His latest mission was becoming an expert in Apple's SwiftUI. 
> Peter has worked with iOS since the inception of the iPhone, and is regularly invited to speak at conferences around the world. He also organizes [Cocoaheads](https://twitter.com/cocoaheads_at), a meetup for developers that work with Apple platforms. Prior to PSPDFKit, he worked as a Senior iOS Engineer at a startup in San Francisco and taught iOS and Mac development at his alma mater, the Vienna University of Technology.

### Slides

[Many of my past talks are on SpeakerDeck](https://speakerdeck.com/steipete)

### Avatar

![dotSwift 2018 in Paris](https://raw.githubusercontent.com/steipete/speaking/master/Pictures/dotSwift2018-4.jpg)

![My avatar image is in this repo.](https://github.com/steipete/speaking/blob/master/steipete-avatar-2016%2B.jpg)

### Pictures

More Pictures see the pitures folder in this repo.

[![App Builders 2018 in Lugano, Switzerland](https://raw.githubusercontent.com/steipete/speaking/master/Pictures/appbuilders-2018-1.jpg)](https://www.youtube.com/watch?v=eJ_BdSBxCZk)

[![FrenchKit in Paris, France](https://github.com/steipete/speaking/blob/master/Pictures/frenchkit-2019-1-small.jpg)](https://speakerdeck.com/steipete/shipping-a-mac-catalyst-app-the-good-the-bad-and-the-ugly)

### Podcasts

* Semaphore CI: [Peter Steinberger on his startup journey, quirks of PDF and what’s exciting about WWDC19](https://www.youtube.com/watch?v=tcZPdMKz9xQ) (May 29, 2019)
* The raywenderlich.com Podcast: [Peter Steinberger – Podcast S09 E03](https://www.raywenderlich.com/3249277-peter-steinberger-podcast-s09-e03) (May 15, 2019)
* Swift by Sundell Podcast: ["Long-term code evolution"](https://pspdfkit.com/blog/2018/swift-by-sundell-podcast/)

### Articles

* [PSPDFKit: Wie ein Wiener Startup ohne Investment zum globalen Player wurde](https://www.derbrutkasten.com/pspdfkit-wiener-startup/)

### Credits

Credits go to [Felix Krause](https://github.com/krausefx/speaking) for the idea to post this here - thanks!
