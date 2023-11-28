---
description: >-
  Deep-dive into design processes and collaborative decision making in the
  product team
---

# 💳 Virtual Cards on Finance Apps

### Context

One of the first projects I worked on was the budgets feature in companies' expense management retinue. We had just launched budgets to a circle of beta users, and the feature needed to be supported by all other aspects of the product, including the cards page. While designing for all the edge cases for the complex feature inclusion, I also made note of several general usability issues on the cards page. At the time, the virtual cards page was the favorite of the entire management team. Everybody was proud of it because it was one of the most well-received features that can be credited for the product's success. Suggestions to redesign or review it were not going to be easily accepted, and I had to build a strong case for it.&#x20;

![](<../../.gitbook/assets/image (175).png>)&#x20;

A few issues with this card layout:&#x20;

#### Usability issues: revealing card number

In a tangible card, some confidential details are mentioned on the back side of the card. We tried animations to show the card flipping, etc., but they felt superficial in a virtual space. The card design currently shows all details in a small designated space for the card. The function to 'view card number' had been changed several times, and we still received complaints that users did not know how to access their own card numbers. I see this as an issue where **the physical does not translate to digital directly and must be addressed with the affordances of a digital product.**&#x20;

**Card type organization**

In this setup, it was confusing for users where to find the card they were looking for. Depending on whether they were employees, budget owners (team leads), administrators, or founders (directors) the number of cards they had access to would vary, as well as the nature of access. When we started out, a simple direct solution was to list them all in the same space, but increasingly we needed to design a more elegant way to access cards.&#x20;

#### Poor Data Structure or Information Architecture

There was no understandable grouping of information or hierarchy of data displayed. It made it hard for users to find what they were looking for. Multiple menu items also got in the way of efficient usage of the card page.

### Redesign brief

The following questions were analyzed to arrive at the critical functions of the card page:

<figure><img src="../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

I then presented the issues to all relevant team members to align on some basic functional expectations.

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

We aligned on the fact that the way a user looks at a card would have several functional needs, and that they can be hierarchically positioned. This would also inform us what the page's visual hierarchy should be.

We also evaluated this for employees, the finance team, and administrator roles.

### Stakeholders

The people involved in any modifications to the card page:

1. Business team
2. Leadership, including CEO and product leadership
3. Compliance team
4. People-facing teams: sales, customer success
5. External partners:
   1. Card provider -NIUM
   2. Payments partner: Visa

All these teams had to be consulted at every stage, as any change to the card display had to be signed off on by all these stakeholders.&#x20;

### Design elements



Variations to balance utility, functionality, and appearance:

<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

Explorations to display budget labels

<figure><img src="../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

Around the same time, we were also introducing physical cards. To accommodate those alongside virtual cards, I also designed the virtual representations of this family of cards:

<figure><img src="../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://file.notion.so/f/f/92a42d9c-ee27-46c4-9d11-b3b00d5e90bd/e1d1e982-bf89-4b1f-b744-e1049296e36e/Card_number_reveal.gif?downloadName=Card+number+reveal.gif&expirationTimestamp=1696514400000&id=64f58f5d-db7a-4f36-8de3-c59e50f1336a&signature=FW8_F0oqmv98VPPbTgSquk77H0mK3GDvi21Q4y71EoE&spaceId=92a42d9c-ee27-46c4-9d11-b3b00d5e90bd&table=block" %}

### Launching new design

We launched the new card page after many iterations, discussions, and appeals to stakeholders to work out common ground for the future of the virtual (and physical) card. In the refurbished page, we have:

* clear navigation between different cards that a user has primary access to
* a separate list view for cards that a manager has supervisory access only
* dynamic animations and transitions to help make the page feel like a 3-dimensional space that's holding all their cards safe
* sharper attention to users' needs and hierarchically organized card functions

{% embed url="https://file.notion.so/f/f/92a42d9c-ee27-46c4-9d11-b3b00d5e90bd/4458a84f-feca-4b76-ab68-4e2f86ce3836/new_cards_side_by_side.gif?downloadName=new+cards+side+by+side.gif&expirationTimestamp=1696514400000&id=46136fec-b9b3-4697-820c-965a4a9d0f8b&signature=FLfBv2ETrZ2E2rsiDWdBqwwzsiXPo71BCEQBkt5zxH0&spaceId=92a42d9c-ee27-46c4-9d11-b3b00d5e90bd&table=block" %}

***

