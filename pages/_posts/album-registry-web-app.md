---
layout: post
category: projects
date: 2017-08-12
title: Album Registry
lede: Design and development of a crowd-funding platform to help pro photographers grow their business.
link: https://albumregistry.com/
assets:
  cover: /images/album-registry-card.jpg
heroShowCover: false
card:
  externalLink: false
tags:
  - design
  - frontend
---

Album Registry is a crowd-funding website for photographers. After technical setbacks and investor problems, I was asked to help rethink what Album Registry could be, and rebuild the platform for a community of photographers around the world.

> Our gift-giving model is innovative, and allows people to focus on the joy of giving and remembering by sharing the cost of great photography. **Jannah Dryden, Founder**

<Media frame ratio="1/1" image="/images/albumregistry-new-profile-2500.jpg"/>

Album Registry bridges the gap between people celebrating the big moments of their lives, and artisanal photographers who do justice to those moments. We needed a way to showcase what great photographers do while giving gifters a first-class e-commerce experience.

<MediaVideo frame src="287000708" ratio="1/1"/>

## Built for future iteration

The resulting website is fully responsive, provides multiple levels of user access, with a flexible backend content management system to record registry payments and an email notification system for admin, customers and gifters.

The codebase uses the Node.js ecosystem, allowing us to take advantage of the rapid developments in open-source web development.

We're able to design and adjust new features in the browser using the brand design system we designed and built.

<Media ratio="1288/2880" image="/images/albumregistry-mobile-screens-lg-dark.png" />

We aim to offer the Album Registry photographers three ways to do what they love: an ecommerce platform, a website marketing toolkit, and a community to share with.

> I begin every wedding I do with an event page, which I can setup in a minute. My clients are impressed when they get such a great web page done so fast, not to mention the huge burden the gift-giving model lifts from their shoulders! **Benn, Bluesky Photography**

<!-- <Media image="/images/albumregistry-moment.jpg" /> -->

Album Registry grows slowly but surely, and since joining as co-founder in mid 2017, I'm excited to focus on building tools that help photographers grow their business, and help people give the gift of memories.

Frontend development done in collaboration with [Barry Phillip Hall](https://github.com/BarryPH). Please note that as of June 2018, I'm no longer part of Album Registry. {.Note}

<PostButton link="https://albumregistry.com" label="Visit Album Registry" />

<script>
import Media from "../../src/components/Media";
import MediaVideo from "../../src/components/MediaVideo";
import PostButton from "../../src/components/PostButton";
export default {
  components: {
    Media,
    MediaVideo,
    PostButton
  }
}
</script>
