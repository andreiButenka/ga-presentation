Hi. My name is Andrei Butenka. I’m the rolling scopes school student. And today I’m giving a Google Analytics presentation. All website owners ask themselves same old questions. How many people visit my website? Where do my visitors live? Do I need a mobile-friendly website? How can I improve my website's speed?
As a developer, you can answer all these questions using Google Analytics.  


Today we’ll learn a little bit about Google Analytics’ history, its goals, working principles. I’ll tell about integration of this service, about event tracking and will say some words about Google Analytics dashboard and other features.


Let’s start with the basics. Google Analytics is the most widely used web analytics service offered by Google. Google launched the service in November 2005. It’s free, highly customizable, constantly changing and updating.
Google Analytics is a powerful tool that tracks and reports web traffic (for example, where visitors came from and how, how they navigating through your website, it analyses user behavior). Also it track conversions (like page views, downloads, registrations). It collects and processes E-commerce data (for example, volume and success of transactions). 


Google Analytics is the service that collects, processes and reports about an application’s use patterns and performance. Collected data is send to google analytics servers. The reports are available in google analytics web interface or through reporting api.


Integration of Google Analytics is simple. First, you must create an account. Each account can contain one or more properties. These are not Javascript properties. In Google Analytics, a property is a blog, website, mobile application, that is associated with a unique tracking ID. For an example, if an account represents a company, one property might represent this company’s website, while another property might represent this company’s mobile application. Than Google Analytics generates tracking snippet. This is a piece of Javascript you need to paste into your page. It sends data to google analytics back end. Also you can use google analytics library to create custom analytics. For example, tracking of specific user’s actions or tracking push notifications. 

This is a tracking snippet. The Google Analytics tracking code is made up of bunch of Javascript statements. Javascript statement is an instruction to be executed by a web browser. Javascript statements are executed in the order in which they ate written. By default, from top to bottom and from left to right. In this example first statement is the instruction to create a tracking object and associate it with our web property. Second statement is the instruction to send page view data to Google Analytics servers. Google Analytics has its own built-in function known as the ‘ga’. As you can see, this function does almost every Google Analytics’ task. The first argument of ‘ga’ function is a Google Analytics command (like ‘send’, ‘require’, ‘create’). Other arguments depend upon the Google Analytics command being used. For example, ga(‘require’, ‘ecommerce’) loads the ecommerce plugin.

An entire snippet needs to be pasted into every page you want to track. At a high level, when this script runs, it creates an async script tag, downloads analytics.js. it creates a tracker, that gathers user data and sends this data as the page view HIT via HTTP request to Google analytics beck end. For simple application, this is the only coding required. 


Also you can replace analytics.js with analytics_debug.js for console debugging. Using this version will you to log detailed messages to your console for every page view HIT. Also it will log errors and warnings for your tracking code.


There are two common ways to track user interactions: page views and events. According to Google Analytics, a pageview is an instance of a page being loaded (or reloaded) in a browser. Pageviews is a metric defined by total number of pages viewed. Page views are great and they are foundation of many Google Analytics’ reports. But if you want to measure and learn from what happens on your page, you want to use event tracking. A user can interact with our website via a mouse, touch screen, keyboard, frame and forms, and so on. That’s why we can have: mouse events, touch, keyboard, frame events, form events. There are two broad categories of events:
* One, which generate page views (like clicking on an internal link on a webpage).  
* One, which do not generate page views (for example, clicking on an external link, downloading a file, scrolling a page and so on).&nbsp; 


There are four Event Tracking parameters:
* Event Category (it is a group of similar events you want to track);
* Event Action (it’s a type of event you want to track for a specific element of website);
* Event Label (it’s an element name, whose users’ interactions you want to track);
* and optional Event Value. This is a numerical value that can be assigned to the event you want to track).&nbsp; 


Google Analytics supports custom events. Custom events allow more detailed analysis of user behavior. For example, we have 5 forms on our website. And we want to track submissions of these forms on our Contact page. Since we want to track submission of contact forms, we can set the Event’s Category value to “Contact”. We want to fire event when a user clicks “Submit”. And we can add Event Label’s value as “Contact Page Form”.
That’s it! All you need to set up new goal in Google Analytics’ dashboard. There are the same parameters we set in our JavaScript snippet. Now you can view your custom event as a goal and see more in depth data about your event in the Conversion reports. 


Now few words about Google Analytics’ dashboard. Here is the audience’s overview interface. You can see general information such as page view records, ratio of new and returning visitors and other statistics. Also see you can specific information about user’s language, country, city, device, operating system, screen resolution and so on.
Google Analytics’ dashboard is highly customizable.   


It is also possible to view the analytics information in real time. This interface will allow to see page view HITS as they occur on our website.


These are just basic Google Analytics’ features. Also you can track push notifications, use service-workers, calculated metrics, offline analytics, you can store your analytics in data bases and take advantages from machine learning. And don’t forget about integrating your Google Analytics with other Google services such as AdSense, AdWords, YouTube and so on.


Knowing how to integrate and use google analytics to improve your business and increase your revenue is the skill within itself.  You can learn more about Google Analytics from a combination of the sources below.


Thank you for your attention.

