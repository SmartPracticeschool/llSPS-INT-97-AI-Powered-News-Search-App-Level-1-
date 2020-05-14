# llSPS-INT-97-AI-Powered-News-Search-App-Level-1-
AI Powered News Search App (Level-1)

The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help your application make dynamic connections across current events faster. In this exercise, you'll start with the basics and build your own news mining web application using JavaScript, Node.js, and the Watson Discovery service. In this exercise:

Code is written in Node.js, with the server-side using the Express framework and the client using ReactJS.
You'll use the pre-built Watson Discovery News collection
You'll access the Watson Discovery service through the Watson Discovery API
Optionally, you can choose to:

Use a Slack interface to query the data
Push news alerts out to an RSS reader
Host the app on the IBM Cloud
Description
This code pattern shows you how to tap into massive data sets to mine insight. You'll build a news mining web application with the Watson Discovery service using the Watson Node.js SDK. The app demonstrates two use cases using Watson Discovery News:

Search: Query for the most relevant new articles about a specific topic or subject. Because the news collection is pre-enriched with natural language processing, you can query not just on keywords or categories but also on concepts, sentiment, and relations to get richer search responses.

Trending topics in the news: Identify popular topics over the past 24 hours. Topics can be general, or specific to an industry or category.
Flow
The user interacts with the Watson Discovery News Server via the app UI.
User input is processed and routed to the Watson Discovery News Server.
The Watson Discovery News Server sends user requests to the Watson Discovery Service.
The Watson Discovery Service queries the Watson News Collection.
The Watson Discovery Service sends news articles to the RSS Reader.
The Watson Discovery Service responds to Slack search requests.
