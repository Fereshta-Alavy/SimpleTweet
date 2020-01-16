# SimpleTweet : is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

- User can **sign in to Twitter** using OAuth login
- User can **view tweets from their home timeline**
- User is displayed the username, name, and body for each tweet
- User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- User can refresh tweets timeline by pulling down to refresh
- User can view more tweets as they scroll with infinite pagination
- User can **compose and post a new tweet**
- User can click a “Compose” icon in the Action Bar on the top right
- User can then enter a new tweet and post this to twitter
- User is taken back to home timeline with **new tweet visible** in timeline
- Newly created tweet should be manually inserted into the timeline and not rely on a full refresh

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='walkthroughSimpleTweet2.gif' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
