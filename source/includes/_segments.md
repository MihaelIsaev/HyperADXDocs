# Segments

With sending in-app events triggered by your users you can improve your monetization and get higher earnings.

Our platform automatically build audiences using your in-app data (provided by your events) and assigns high performing campaigns individually to each segment.

Also our advertisers and mediabuying department make higher bids for more engaged users.

## Android

You can send the events very easy. Just call the method `sendEvent(Context, event_code)` from HADEvent class.

Example: `HADEvent.sendEvent(this, Event.GAMING_ACHIEVEMENT_UNLOCKED);`

## iOS

You can send the events very easy. Just call the method `sendEvent(type: HADEventType)` from HADEvent class.

Swift example: `HADEvent.sendEvent(.AchievementUnlocked)`

Objective-C example: `[HADEvent sendEvent:HADEventTypeAchievementUnlocked];`

## Event codes

**Authenticate events**

* 101 Registration
* 102 Login
* 103 Open

**eCommerce events**

* 201 Add to Wishlist
* 202 Add to Cart
* 203 Added Payment Info
* 204 Reservation
* 205 Checkout Initiated
* 206 Purchase

**Content events**

* 301 Search
* 302 Content View

**Gaming events**

* 401 Tutorial Completed
* 402 Level Achieved
* 403 Achievement Unlocked
* 404 Spent Credit

**Social events**

* 501 Invite
* 502 Rated
* 504 Share
