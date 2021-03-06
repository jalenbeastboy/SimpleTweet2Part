# Project 2 - *SimpleTweet2Part*

**SimpleTweet2Part** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **X** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x ] User can **compose and post a new tweet**
  - [ x] User can click a “Compose” icon in the Action Bar on the top right
  - [ x] User can then enter a new tweet and post this to twitter
  - [ x] User is taken back to home timeline with **new tweet visible** in timeline
  - [ x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [ x] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [ ] User is using **"Twitter branded" colors and styles**
- [x ] User can click links in tweets launch the web browser 
- [ x] User can **select "reply" from detail view to respond to a tweet**
- [ x] The "Compose" action is moved to a FloatingActionButton instead of on the AppBar
- [ ] Compose tweet functionality is build using modal overlay
- [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [ x] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ x] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet. 
