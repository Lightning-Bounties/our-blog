---
description: 1/13/2025 - 1/20/2025
cover: ../../.gitbook/assets/Blog Banner TB (2).png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Week 2: LB x Top Builder Recap

## PlebLab's Week 2 Recap: Lightning Bounties

In this weeks edition, we’ll explore the key milestones and achievements from the second week of the Top Builder competition. For week 2, Lightning Bounties focused on expanding our business development efforts, documenting our journey, and fostering collaboration with other teams. From publishing our **Week 1 Recap** and featuring Branta as a partner to launching a metrics dashboard and simplifying documentation contributions, we’ve made significant progress. Join us as we reflect on these accomplishments and look ahead to what’s next!

## Development Milestones&#x20;

#### GiHub\[-as-a-Service] Updates

A day before releasing the new version to production, our service calls to GitHub broke due to a schema change on their end, which had been stable for the past \~2 months.

At first this was frustrating because it delayed roll-out even further. But after consideration, this was great timing: it never broke for our \[first] users and we realize we should run regular health checks for this service to see if GH is returning a schema that matches our expectations of both positive and negative cases.

Even better - looks like this update was around a core functionality to LightningBounties that was considered unstable (or "fuzzy") the link between merging PR's and closing associated Issues. The verbiage has changed from:

> merging PR `#XX` **may** close Issue `#YY`

to:

> merging PR `#XX` **will** close Issue `#YY`

Reflecting this feature has more guarantees around it. We'll continue to monitor and test.



## Business Development Milestones&#x20;

In Week 2, the Business Development team achieved key milestones, including publishing our  [**Week 1 Recap**](week-1-lb-x-top-builder-recap.md), featuring [**Branta**](../top-builder-x-lightning-bounties/top-builder-teams/branta-guardrails-for-bitcoin-and-lightning.md) in a blog post, and launching initiatives like a metrics dashboard and rolling out our first iteration with documentation bounties.

Now, let’s dive into what happened on the business development front in Week 2!

***

### **Documenting Our Journey: Week 1 Recap and Branta Spotlight**

For week 2, we kicked off our journey in the Top Builder competition by publishing our [**Week 1 Recap**](week-1-lb-x-top-builder-recap.md), highlighting our interactions with fellow Top Builder Teams, what we learned from the Week 1 workshops, development progress and lessions we learned along the way. This[ blog post](week-1-lb-x-top-builder-recap.md) provides a transparent look into our progress while celebrating collaborative milestones. We also featured [**Branta**](../top-builder-x-lightning-bounties/top-builder-teams/branta-guardrails-for-bitcoin-and-lightning.md), a Top Builder team and valued partner of Lightning Bounties, in a dedicated article. [Branta’s ](https://www.branta.pro/)important solutions, such as wallet verification, transaction protection, and Lightning Network integration, provide essential safeguards for Bitcoin users, aligning perfectly with our mission to enhance security and usability in the Bitcoin ecosystem.

<div><figure><img src="../../.gitbook/assets/Blog Banner TB.png" alt="Week1 Recap Banner"><figcaption><p><a href="week-1-lb-x-top-builder-recap.md">Click Here to Read Full Article</a></p></figcaption></figure> <figure><img src="../../.gitbook/assets/branta_banner.png" alt="Branta Banner"><figcaption><p><a href="../top-builder-x-lightning-bounties/top-builder-teams/branta-guardrails-for-bitcoin-and-lightning.md">Click Here to Read Full Article</a></p></figcaption></figure></div>

We’re excited to continue featuring Top Builder teams in future posts and invite others to contact [**mike@lightningbounties.com**](mailto:mike@lightningbounties.com) for an interview to share their story with the community!

### Metrics Dashboard for Lightning Bounties

Thanks to Enrique's efforts, the Biz Dev team has developed an internal dashboard to visualize key metrics for our bug bounty platform. This dashboard tracks essential data, including the percentage of open versus solved bounties, average and total sats per bounty, the number of developers, unique repositories, and Twitter follower growth. These insights will enhance our understanding of user engagement and help us refine our strategies. In the coming weeks, we will actively monitor these metrics and make necessary adjustments to ensure our platform remains attractive to both bounty issuers and hunters.

Below are some screenshots of our Dashboard in action:

<div><figure><img src="../../.gitbook/assets/bounty_details_page_pie_chart.JPG" alt="Stats Overview"><figcaption><p>Metrics Dashboard</p></figcaption></figure> <figure><img src="../../.gitbook/assets/google_analytics.JPG" alt="Where Our Users Come From"><figcaption><p>Data on User Demographics</p></figcaption></figure> <figure><img src="../../.gitbook/assets/bounty_claim_time.JPG" alt="Bounty Solve Time Metrics"><figcaption><p>Data on Time Spent Solving a Bounty</p></figcaption></figure></div>

### **Documentation Bounties Are Live—Contribute with Ease!**

The Lightning Bounties team reached an exciting milestone by creating a [**Contributing Guide**](../top-builder-x-lightning-bounties/top-builder-teams/suggesting-changes.md) that makes it easier than ever for open-source contributors to improve our Blog and Documentation sites. This [guide ](../top-builder-x-lightning-bounties/top-builder-teams/suggesting-changes.md)offers simple, step-by-step instructions for making edits directly through GitHub—no need to fork the entire repository. With GitBook seamlessly integrated into GitHub, contributors can quickly find, edit, and propose changes, streamlining the entire process.

<figure><img src="../../.gitbook/assets/editOnGitHub.png" alt="Edit on GitHub Located Top Right of Each Doc/Blog Page"><figcaption><p>Edit on GitHub Located Top Right of Each Doc/Blog Page</p></figcaption></figure>

This effort not only improves the quality of our written content but also encourages community engagement by rewarding  approved contributions with a minimum of **5,000 sats**. If you have ideas to further simplify or improve our documentation, we’d love to hear from you! Visit our platform at [app.lightningbounties.com ](https://app.lightningbounties.com/issue/40bbd95b-929b-4502-92d3-2028159fb79c)and help us make our documentation better for everyone. Your contributions matter!



## YoPaki Mentorship Session

The YoPaki Mentorship workshop, led by Francisco, whom we met at the 2024 PlebLab Startup Day in Mexico City, provided valuable insights for developers and entrepreneurs looking to build on Bitcoin Lightning. Francisco anticipates a significant influx of developers entering this space within the next 12-18 months, highlighting the growing importance of Lightning Network applications. The workshop emphasized the challenges of getting apps approved on Apple and Android app stores, particularly for those dealing with Bitcoin payments. Key advice included being prepared for initial rejections, appealing decisions after multiple rejections, and carefully framing the app's functionality to avoid raising red flags with app store reviewers.

The session also touched on the complexities of navigating Geo-IP restrictions and jurisdictional rules, emphasizing the need for patience and collaboration with other Bitcoin companies to overcome these hurdles. Francisco encouraged Top Builder teams to collaborate with each other and stressed the importance of discerning good advice from bad when receiving feedback. For those seeking funding, the workshop highlighted that VCs often look for founders with a track record of successful fundraising and teams capable of delivering on their roadmaps. Setting realistic goals and maintaining momentum throughout the development process were identified as crucial factors for success in the Lightning Network ecosystem.

To learn more about YoPaki, click the images below to view their presentation and elevator pitch at PlebLab’s 2024 startup day, and YoPaki's website. Also, stay tuned for their Android app store release coming soon and if you have an iPhone check out YoPaki's website to download the app and start stacking sats!&#x20;

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="https://www.yopaki.com/"><strong>Website</strong></a></td><td><a href="../../.gitbook/assets/yopaki_logo_no_bg.png">yopaki_logo_no_bg.png</a></td><td><a href="https://www.yopaki.com/">https://www.yopaki.com/</a></td></tr><tr><td align="center"><a href="https://youtu.be/jVtekBhztdg?si=CganMIjin4ZqdcoS"><strong>Presentation</strong></a></td><td><a href="../../.gitbook/assets/yopaki2_yt.PNG">yopaki2_yt.PNG</a></td><td><a href="https://youtu.be/jVtekBhztdg?si=kS81SSx4KWg7EH6h">https://youtu.be/jVtekBhztdg?si=kS81SSx4KWg7EH6h</a></td></tr><tr><td align="center"><a href="https://x.com/BitcoinNewsCom/status/1838688514038280276"><strong>Elevator Pitch</strong></a></td><td><a href="../../.gitbook/assets/yopaki_pitch.PNG">yopaki_pitch.PNG</a></td><td><a href="https://x.com/BitcoinNewsCom/status/1838688514038280276">https://x.com/BitcoinNewsCom/status/1838688514038280276</a></td></tr></tbody></table>



## PlebLab Early Days Interview with Lightning Bounties&#x20;

The interview with Car was an engaging and insightful experience for our team, as we reflected on the journey of building Lightning Bounties and the lessons learned along the way. Car's thought-provoking questions, such as how hackathons shaped our team and why Lightning Network was chosen for rewards, gave us the opportunity to share our story in depth. We appreciated the chance to discuss how our team came together through hackathons, starting with a mix of skills and backgrounds, and how those connections evolved into a strong, collaborative unit. It was fun recounting moments like winning the MIT Bitcoin Hackathon and how those early experiences shaped our vision for Lightning Bounties.&#x20;

Car's curiosity about our platform's evolution and the challenges we’ve faced made the conversation dynamic and reflective. We enjoyed sharing insights about balancing development with operations, navigating centralization risks with GitHub, and ensuring seamless user experiences for both developers and organizations. The interview also highlighted the importance of fostering collaboration within the open-source community and onboarding more people to Bitcoin through meaningful use cases. It was a pleasure being part of this discussion, and we’re excited to tune into other Top Builder teams’ interviews to learn from their journeys as well!

{% embed url="https://youtu.be/9gMe6KlH3uk?si=y_b8ueofVAks0b5l" %}
PlebLab Early Days Interview with Lightning Bounties
{% endembed %}



## Bitcoin Design UX & UI with Sam Brewton

**Sam Brewton's Presentation on Bitcoin Interface and Experience Design: A Detailed Overview**

Sam Brewton recently delivered a presentation that we found to be incredibly insightful, especially concerning Bitcoin interface and experience design. His intense focus on crafting designs that cater to mass adoption really resonated with our team because we are actively working on developing a platform that is appealing and accessible to a wide variety of users.

Throughout the presentation, Sam emphasized several key points that we can explore further when building Lightning Bounties. First, he stressed the importance of user experience (UX) in reducing anxiety and friction around Bitcoin transactions. This involves carefully considering every touchpoint in the product journey, from initial interaction to final transaction. Sam's example of using animations to provide feedback during transactions highlighted how small design elements can significantly impact user confidence.

Secondly, Sam discussed the value of accessibility and universal design principles. He explained that by designing for edge cases, such as users with disabilities, we can create products that work better for everyone. This approach not only broadens the potential user base but also future-proofs designs as technology evolves. Sam's critique of overly complex designs, like the multi-functional eating utensil, drove home the point that simplicity often leads to better usability.

Lastly, Sam emphasized the importance of real-world testing with actual users. He recommended conducting in-person testing sessions with at least three people per session to identify usability issues that might otherwise be missed. This hands-on approach allows developers to observe user behaviors directly, which can differ significantly from what users say they do or want.

Sam's presentation has given us a lot to think about as we work on creating a user-friendly Bitcoin platform that can drive mass adoption and onboard new developers, many of which are using Bitcoin for the first time. His emphasis on simplicity, accessibility, and real-world testing will be crucial guideposts as we develop Lightning Bounties.

To see Sam's entire workshop click the video below :arrow\_down:

{% embed url="https://youtu.be/FwrYEIRXmHY?si=4FGjKJTa-Z-ctmYF" %}
Bitcoin Design UX & UI with Sam Brewton
{% endembed %}



## Wrapping it Up

Thank you for taking the time to engage with this content on creating a user-friendly Bitcoin platform. We are excited to continue developing Lightning Bounties, guided by the principles of simplicity, accessibility, and real-world testing emphasized in Sam's presentation.

For any questions or feedback, feel free to reach out through our community channels. Your insights are invaluable as we strive to enhance the user experience and attract more developers to the Bitcoin ecosystem. Stay tuned for updates and new features as we progress on this journey together!





