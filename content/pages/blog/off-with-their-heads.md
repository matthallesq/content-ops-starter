---
title: Off with their heads!
slug: off-with-their-heads
date: '2023-10-10'
excerpt: >-
  Over the past few years, I’ve been observing and experimenting with the
  nascent wave of front-end web technologies referred to as headless
  (specifically the JAMstack) and considering their potential adoption for
  startups, SMEs, and even large enterprises.
featuredImage:
  url: /images/pic07.webp
  altText: Thumbnail
  type: ImageBlock
  styles:
    self:
      borderRadius: medium
isFeatured: true
seo:
  metaTitle: The Top Ten Lessons We’ve Learned Since Our Initial Launch
  metaDescription: You can add the excerpt and main keywords of your blog post here.
  socialImage: /images/abstract-feature2.svg
  type: Seo
colors: bg-light-fg-dark
styles:
  self:
    flexDirection: row
type: PostLayout
author: content/data/person1.json
---
![](/images/pic07.webp)

## Making a Case for Going Headless

Over the past few years, I’ve been observing and experimenting with the nascent wave of front-end web technologies referred to as headless (specifically the JAMstack) and considering their potential adoption for startups, SMEs, and even large enterprises.

The architectural concept of headless technologies is to have a separate layer in your web stack for the front-end user interface, improving performance and security, which translates into a better user experience. Much like microservices architecture facilitates the movement of data in and out of systems, headless technologies decouple content from the user interface.

JAMstack (short for JavaScript, APIs, and Markdown) achieves this by pre-rendering the website at build time instead of dynamically generating pages on demand. These pre-rendered pages are then served from an edge network or CDN (such as Amazon S3 or Netlify) instead of a traditional web server. The front end relies on JavaScript and APIs to interact with backend services (CMSs, CRMs, payment gateways, etc.), allowing for enhanced personalization and interactivity.

## Why Go Headless?

### **1. Performance**

With advancements in digital technologies, dynamically generated web pages became the norm. While this enabled feature-rich experiences, it also introduced performance bottlenecks, particularly for CMS/eCommerce/CRM platforms that rely on web or application servers to serve functions and user interfaces on request. When hundreds or thousands of requests run in parallel, performance takes a hit.

Page load speed directly impacts the user experience and conversions. Research from Pingdom (How Does Page Load Time Affect Your Conversion Rate?) highlights the importance of fast load times. While the Nielsen Norman Group’s golden rule used to be 3 seconds, my own usability tests suggest users now expect load times closer to 2 seconds.

I recently tested a major Australian grocery retailer’s website, and their Google Lighthouse performance score was 15/100. Imagine the revenue lost due to slow page speeds!

With JAMstack, sites eliminate the need to generate pages dynamically at request time. Instead, pages are built in advance and served from a CDN close to the user, ensuring lightning-fast performance without complex infrastructure.

### **2. Security**

By eliminating the need for web servers, JAMstack sites significantly reduce attack surfaces. Traditional CMS platforms like WordPress rely on databases and server-side logic, making them susceptible to vulnerabilities like SQL injection and DDoS attacks. A headless approach removes these risks by serving static files and shifting dynamic functionality to secure APIs and third-party services.

### **3. Scalability**

For large organizations, enterprise software investments often become a burden, requiring costly upgrades with little added value beyond maintaining vendor support. Headless technologies provide an escape route from these constraints. Instead of being locked into monolithic systems, companies can modernize incrementally—retaining legacy CMS or eCommerce platforms for core functions while leveraging APIs to integrate new front-end technologies.

The benefits include:

*   A vibrant and maturing ecosystem of front-end frameworks, CMS, and eCommerce solutions.

*   The ability to replace or upgrade front-end experiences without disrupting backend systems.

*   Improved agility, allowing businesses to adapt to changing market needs faster.

### **4. Cost Savings & Environmental Benefits**

Static sites require fewer server resources, leading to lower hosting costs and reduced energy consumption. By leveraging CDNs and edge computing, companies can deliver fast, secure experiences while minimizing their carbon footprint.

### **5. Developer Efficiency & Workflow Improvements**

Good development practices are inherent to JAMstack. Since static sites require proper build processes and version control, the result is:

Higher code quality.

A clear separation of concerns between designers, developers, and content creators.

The ability for digital agencies to own and manage the front-end layer independently.

## The Downsides of Going Headless

While the benefits are clear, headless architectures aren’t without challenges:

### **Browser Support & Compatibility**

Some modern frameworks require polyfills or workarounds to ensure compatibility across all browsers.

### **Scalability at Extreme Levels**

While JAMstack scales well for most use cases, some enterprises with complex personalization needs may require additional infrastructure.

### **Developer-Centric Approach**

Headless CMSs require technical expertise to configure and maintain, which can be a hurdle for non-technical teams.

### **Accessibility & Feature Gaps**

Some headless CMS platforms fall short in managing complex product catalogues (e.g., multiple variants like colors and sizes), but you probably should be using an e-commerce solution for catalogue management.

## Final Thoughts: A Path to the Future

Headless CMS and JAMstack architectures offer a compelling future-proof solution for web development. By decoupling content from presentation, businesses gain flexibility, security, and performance benefits that traditional monolithic systems can’t match.

Whether you’re looking to modernize an existing platform, escape vendor lock-in, or improve your website’s speed and security, going headless could be the answer.

