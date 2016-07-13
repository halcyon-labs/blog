---
layout:     post
title:      "Forecast: Cloudy"
date:       2015-12-22 19:00:00
author:     "Scott Swarthout"
header-img: "img/post-bg-02.jpg"
---

Note: This is not a sponsored blog. All opinions expressed in this post are solely those of Halcyon Labs LLC. We hold no liability for the performance or reliability of products mentioned in this blog, and have no financial incentive for highlighting any specific company or product.

Most of the time when we are working with clients on an application, we find that they need some type of server or database to coordinate their app. When this arises, we tell customers that they should invest in a cloud platform, and we explain to them the different solutions that are available and help them sort through what type of cloud platform they should choose to build their application on. This blog is a summary of what we tell them in this situation. 

<a href="#">
    <img src="{{ site.baseurl }}/img/the-cloud.jpg" alt="Cloud">
</a>

**What is the Cloud?**

This is the first question many people ask. Essentially, the cloud is a collection of computers that you can run your code on and you can control over the internet. Instead of owning a physical computer, you pay a subscription to use some large companies computers as you wish. This has many advantages over maintaining on premises hardware. First, your cloud server is safe in a large datacenter where it is being monitored and protected from things like dropped internet connections and power outages. It is far less likely that your server will go down from these problems when your server is hosted in the cloud. Also, with the cloud, you pay as you go, so if your app doesn’t need a very powerful server, you have to pay only a few dollars a month instead of buying a full computer for hundreds of dollars that spends most of its time idling. Finally, scaling up your business is much easier with the cloud because in seconds you can scale your app from one small server to dozens of high performance servers with only a few mouse clicks.


**Types of Clouds**

In the current cloud ecosystem (bear with me with these strange analogies), there are 3 main types of clouds. With each type of cloud comes varying levels of flexibility, monitoring tools, and application management. The first type of cloud is Infrastructure as a Service (IaaS). With an IaaS, you are just given a raw server that you can set up exactly the way you would set up an on-premises computer. You have unlimited options for configuring your server, but very little help when it comes to setting up your application to run on it. It is up to you to figure out how to send your code over to the server, and configure everything needed for your code to run on the machine. Since IaaS is very much do it yourself, they often have a much lower price than other solutions, and are more configurable, in terms of computing power, memory, and hard drive space.
 Also, since an IaaS is merely a type of computer rental business, there is very little vendor lock-in, meaning that if you want to switch providers to a different company, it is very easy to do so. 

We recommend IaaS for startups that have some experience in DevOps and want to get the best price to performance ratio for their server hosting. Also, IaaS is recommended for larger companies that have exceeded the normal operating size of typical PaaS deployments.

The second type of cloud is the Platform as a Service (PaaS). When a company makes a PaaS, they basically take an IaaS and put a layer of software on top of it to automate much of the process of setting up a cloud application. a PaaS will have a single way of setting up an application, and it only takes a few clicks and a command in the terminal to get your code running on the cloud. Also, scaling up your server is very easy. You can simply select the number of instances of your application you need and what type of server they should run on, and the PaaS will set it all up for you. 

That being said, a PaaS doesn’t do everything for you. When working with a PaaS, you still need to manage your own database, set up your own authentication, manage your api, and integrate third-party services yourself. Some PaaS companies offer database integrations that manage your database deployment in a similar way as your code, but they usually only have one or two database options and not much flexibility. 

We recommend PaaS solutions for most people because you gain many helpful tools for deploying and scaling your application quickly and easily, but you still can program in whatever languages with whatever frameworks you want. Also, their is less vendor lock-in because none of your code is PaaS specific. Changing PaaS providers would only significantly change your deployment methods, and may require a database migration.

The third in final type of cloud computing environment is the Backend as a Service (BaaS). A BaaS abstracts away as much as possible when it comes to servers, and aims to be a one-stop shop for everything cloud related. a BaaS will bundle together your database, server api, authentication, user management, third-party services and more. a BaaS will provide a web dashboard for viewing your data, and a set of client side SDKs for interacting with the cloud server. This approach makes it easy to start building applications, since for the most part you only have to develop the front-end of your app, and use the BaaS SDK to make your server calls. Also, you don’t have to worry about security as much as with other platforms, since BaaS platforms have already made APIs that are robust from attack. Finally, scaling in a BaaS is as simple as it gets. You don’t have to think about scaling up your application at all. the platform will scale up resources to handle the load behind the scenes and change based on usage. 

However, there are a few major downsides to this approach. First, BaaS platforms are very expensive compared to PaaS or IaaS platforms, typically costing at least twice as much as a comparable PaaS solutions. Also, their is high vendor lock-in with BaaS type clouds. If you want to migrate from one BaaS to another, or from a BaaS to a PaaS or an IaaS, you will need to re-write much of your code, as the BaaS SDKs only work with that particular provider. Also, they often use proprietary databases, so performing a database migration is non-trivial. Finally, integrating with third-party services is difficult or impossible to do on your own. Want to integrate payments with Stripe? Better hope their is a pre-made package to do that in your platform. Want to sing-in with facebook? Pray that your integration is popular enough that the BaaS has set it up already. 

In general we find BaaS platforms very useful in the prototyping and MVP stage and many times we find they are a good fit for our customers, but for companies that are gaining traction and have significant server requirements, we recommend moving from a BaaS to a PaaS as soon as possible before you become so integrated into the platform that migration becomes almost impossible. 

Overall, for early stage startups like the ones we work with, we have two recommendations. For a startup that wants to have a simple solution with a clear roadmap for the future and great ability to scale, we recommend using a PaaS, and for startups that prioritize the ability to bootstrap quickly, and worry about scaling with a PaaS after they have found traction in the market, we recommend using a BaaS. Either of these two approaches work well for most startups that want to get their service online as quickly and seamlessly as possible.
