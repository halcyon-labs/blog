---
layout:     post
title:      "Cornerstones of Modern App Development"
subtitle:   ""
date:       2015-11-08 17:30:00
author:     "Scott Swarthout"
header-img: "img/post-bg-02.jpg"
---

<p>
	Say you have a great new idea for a technology startup. Your app is going to be the next big thing, you can feel it. Now what? You gather a team, talk it through a little bit, and start building. This part can be difficult for many startups. At this stage, they have nothing more than an idea, and they have to find a way to build it. The first question is where is this application going to run? What platforms should we support? If you are building an app today, the best choice is mobile first.
  </p>

**Mobile First**
<p>
	We are entering the era of ubiquitous computing. Almost everyone owns at least one computational device. This means you can basically guarantee that your potential user has a smartphone or a tablet that they carry with them at all times. If you are making an application that you want users to interact with on a daily basis, your best bet is to target this platform. Your app should be optimized for this type of workflow. When people use their phone, they expect a simple and fast user interface that lets them use your service as quickly and easily as possible. Designing your app this way has many benefits.
</p>
* When you are designing your app to work on a small screen with limited resources, you think differently. Organization and user interface becomes paramount. Also, this will help you hone your product into exactly what your customers want, and nothing they don’t.

* Your application design becomes much easier. Everyone knows what a great iOS app looks like or what a great Android app looks like. You can simply use the UI design toolkits provided by the platform and guarantee that your users will know how to use your app and will think it looks great. There is no need to reinvent the wheel when it comes to design on mobile.

* Application deployment is a snap. When you want to push your new application to mobile users, it is as easy as uploading it to each platform's respective app store. Both iOS and Android have them, and they are a great way for your users to find your product and quickly use it.

* Also, when you are developing for mobile, your platform is pretty consistent. If you want to add social share via twitter, you can know that your user has a way to access twitter on their device if they so choose. If you want to add photo sharing, you can essentially guarantee that your user has a camera built in to their device that they can use. If you want location services, enable GPS in your app. It is that simple. This type of platform consistency simply isn’t available anywhere else, and makes adding advanced features to your app easy.

<p>
Great, you have decided to make a new mobile app! The next question is what programming language are you going to use to program your app, and what technologies should you use help you build it? If you are building a modern, multi-platform mobile application today, the best language to use is Javascript, and your best server framework is Node.js.
</p>
**Javascript**

Javascript has been on the rise lately. It is a language that started out as a simple language that was originally intended for running animations and other dynamic behavior in web browsers. Today it is the most popular language on github in terms of number of open source projects and is used for all types of projects, from building mobile web frameworks to embedded internet of things devices to large scale server clusters. This has placed Javascript in the unique position where it can be used at all layers in a modern software stack. A few key benefits of using javascript as the main programming language for your startup are:

* **Speed**: Javascript runtimes have been optimized heavily over the past decade by web browser providers like Google, Mozilla, and Apple. This intense competition for web browser market share has made Javascript the fastest high level scripting language.

* **Portability:** Javascript can run pretty much everywhere. Node.js is a server framework for writing javascript in the server environment, and javascript runs natively in all web browsers. Furthermore, Apple’s iOS include JavaScriptCore, which allows all mobile applications to run javascript code. Android also provides similar functionality through WebView. Long story short, if you can write it, you can run it. This has massive benefits for your development team. Instead of writing their code in Objective-C and Ruby and Javascript and Java, they can just write Javascript. This helps your developers from introducing bugs as a result of context switching and helps them become more productive.

* **Frameworks:** It has become the joke of the javascript world just how many frameworks are available to developers who are using javascript. While this can sometimes feel daunting as there are many frameworks to, it is ultimately a very good aspect of the ecosystem. This large number of javascript frameworks is an indication of innovation in the industry. People are actively trying to improve the development experience of working with javascript and it definitely shows. Most of the latest programming methodologies and techniques start out in javascript frameworks and work their way through the larger programming industry from there. This cannot be said as much for other languages. If you want to program iOS applications in Swift, you are going to use UIKit for your user interface. Period, end of story. In Javascript, since there are many frameworks to choose from, you can select the one that best conforms to your application functionality and your developers style. Some of my favorite Javascript frameworks are as follows:

    * Client-side:

        * Angular 2.0

        * React

        * React Native

        * Backbone

    * Server-side:

        * Meteor

        * Express

        * Sails

* **Common Knowledge:** Javascript is a high level scripting language that is highly influenced by Python and Java. It has simple, expressive syntax and is easy to learn, especially for people coming from other scripting languages or from object oriented languages like Java, Swift, or C#. Also, for the same reasons presented above, many people already know Javascript from past work in web development or in using various Javascript application frameworks. This will help your company hire new developers and onboard them quickly.

Now that you have chosen a platform, a language, and a framework, it is time to start working. In the beginning, you are moving quickly and implementing tons of new features faster than you ever thought possible. To help you keep this development velocity and ensure stability of your platform as it inevitably evolves, we have found that organizing your development method using the agile method works well to avoid your software from falling apart into a pile of spaghetti.

**Agile Method**

The agile method is a famous development strategy that helps programming teams maintain a high development velocity. At its core are the principles of testing, continuous delivery, and rapid, iterative design. Here is what that means for your company:

* **Testing:** Writing automated tests for your code will radically improve the stability of your code base. Every time you make a change to your code, you can test to make sure no other parts of your application were negatively affected by the change. This gives you confidence that your change will not introduce bugs. In addition, writing tests will help you debug your application. If something is not working as intended, you can simply follow the path of tests to find out where it went wrong. I recommend integrating testing into the development workflow as soon as possible, because although writing tests along with your code increases the amount of code needed for each feature, It prevents crippling bugs from killing your productivity further down the line. Also, it is easier to write tests for your features while they are being written as opposed to much later.

* **Continuous Delivery:** If you set up a strong testing platform for your application, this second step is relatively easy. The basic idea is you have your build tool watch your code base for any changes. When a change occurs, it will attempt to build your software and run all of your tests on it. If everything passes, it will automatically deploy your latest code to your users. With continuous delivery, there are no large software releases, just a constant stream of improvement. With this method, you can innovate faster, because you know that as soon as your feature works as intended, it can be pushed out to your users. In other, older approaches, there would be large quarterly or even yearly releases. If your code didn’t make the cut at that deadline, it had to sit for up to a year. Also, deploying often allows you to more closely monitor feedback for your application. You can immediately tell if a change you made to the functionality of your code had an influence in core metrics like time spent on the application, and review ratings.

* **Iterative Design:** This thought pervades all of agile. We believe that the best way to guarantee quality and efficiency is to iterate quickly, test your current version to see what should be changed, make those changes, and repeat. The fundamental assumption is that your users know what is the best way to improve much better than you do, so you should add them to the development process as much as possible. Also, it is much easier to build something small and add more functionality to it later than to build a massive application all at once.

Imagine you have just finished a few months of developing your app. You have been making great progress, and now it is time to launch it for the world to see. More than likely your application relies on some type of server to coordinate user events, manage a database, or serve content to users. When your app gets large, you are going to need a strong IT network to support this traffic. How are you going to manage this? In today’s world of app development, the best way to scale your services is the cloud.

**Cloud Services**

Not long ago, the only way for a technology company like yours to scale up its IT infrastructure would be to talk to a company like HP, IBM, or Dell, spend thousands of dollars, and build a server system that would live in your own data center. From there, you probably had to hire an IT and DevOps team to set up all your servers and applications, and monitor your system to make sure everything worked as intended. In the last few years, there has been huge growth in the cloud computing sector. Companies like Amazon, Google, and Microsoft have offered other companies the ability to use their data centers on a pay-as-you go model. This offers many benefits to startups trying to scale up their businesses.

* **Low Initial Cost:** When you use cloud services, you can opt for on-demand resources, which means you don’t have to pay any money for compute resources you don’t use.

* **Easier to Scale:** If your app takes off, you might be faced with the challenging situation of scaling your infrastructure up quickly. If you are managing your own hardware, this would mean frantically buying and building servers to manage this traffic, which would be slow, stressful, and expensive. With a cloud solution, your infrastructure can be scaled in minutes with a few mouse clicks. Plus, if you need to scale back down at a later date, you aren’t left with a bunch of useless servers to get rid of.

With these strategies, your company will able to begin development, work quickly to get your product to market, and deploy to your audience. The tools and methodologies mentioned above alleviate many of the painful parts of creating a application, from challenging bug fixes to expensive deployment. With this approach, you will be able to lower your cost of development, work quickly, and still maintaining high reliability. Furthermore, you will be able to deploy to multiple platforms scale up easily once your idea gains traction.
