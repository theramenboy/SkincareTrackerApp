# Skincare Tracker
> Track your favorite skincare products from various retailers.

- Updated price every 24-48h
- Custom notifications
- Dark/Light theme
- ...and more!

Skincare Tracker is a mobile app that lets you track easily skincare products. 

## Purpose

*This app was mainly made for my girlfriend who was going crazy keeping track of hundreds of  products with huge fluctuations in prices. Because of that this project came alive.*

## Retailers

These are the major retailers we track at the moment, more might be added at a later time if there is strong demand and some support for it.
<details>
  <summary>Show</summary>

  ### Retailers
  - Jolse
  - StyleKorean
  - Stylevana (IT/EN)
  - YesStyle (IT/EN)
</details>


## Installation

1) Navigate to this page with your android smartphone
1) Download the APK file
1) Install the APK (it is possibile that you need to grant permission to install an app outside the playstore) 

That's it.

For any problem open an issue in this repository.

## Features

- Find your product and add it to your favorites.
- Missing product? Add it from the "Add" page.
- Enable notifications for your favorites products.
- Same product from different stores? Group them!
- Choose between Light/Dark theme.

  For more details read the Release notes!

## Limitations

The API that retrieves prices is published in a paid online space (5 to 6 $/month). The tier of this space is small and consequently the capabilities are limited. In fact, price recovery always occurs one at a time and never in parallel: which means that with many products to verify there is certainly a drop in performance.

It will certainly be possible to improve the service which, in fact, means changing the host tier to have higher capabilities and therefore pay more.

## Tech

| Project | Purpose |
| ------ | ------ |
| [Ionic](https://ionicframework.com/) | Mobile UI Toolkit |
| [Vue](https://vuejs.org/) | Frontend development |
| [Vite](https://vitejs.dev/) | Frontend bundler and dev |
| [C#](https://dotnet.microsoft.com/en-us/) | API backend |
| [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging) | Push Notifications |
| [MonbgoDb](https://dotnet.microsoft.com/en-us/) | API Backend database |
| [Docker](https://www.docker.com/) | API Backend deployment |

## FAQ

**1 - Why the app is not downloadable from GooglePlayStore?**
> All data used in this app come from a WebScraping site. 
> WebScraping is the process of using bots to extract content and data from a website. This practice is bordering on legality. 
> Before I can put this app in an official store I first have to make sure I won't have any consequences even if I am doing it with ethical principles.

**2 - Why the app is only for Android smartphone?**
> This app is also ready to be an iOS App. The problem with iOS is that you cannot install third-party App without Jailbreaking the phone. So because of point (1) for now I am only supporting Android.

**3 - Is this app tracking my personal information?**
> No personal information are tracked or saved.
> The only information this app needs are:
>  
> **Notification FCM Token**: this token is needed to reach your smartphone via Push Notifications.
> 
> **Smartphone ID**: because the FCM token could change I associate it with your smartphone ID so I can assure that your notifications can be delivered. (Smartphone ID is a string code like this 'f2g7o1bc9e123ah0')
> 
> In order to use the app I don't ask for any username and password. So these are the strictly two information I need to save in order to enable Push Notifications to your smartphone.

**4 - Why I can only set 15 notifications?**
> I am a single developer and not a company. 
> To function, this mobile app requires information obtained via an API published on an online server. This API has monthly costs to bear.
For the moment I have blocked notifications for up to 15 products but if the application goes well and is supported in some way, it is possible that this limitation will increase.

## WebScraping Ethics

Is WebScraping legal?
> It's all a matter of what you scrape and how you scrape it. It's quite similar to taking pictures with your phone. In most cases, it is perfectly legal, but taking pictures of an army base or confidential documents might get you in trouble. Web scraping is the same. There is no law or rule banning web scraping. But that does not mean you can scrape everything.

With my WebScraper backend I assure that:
1) I am not seeking to overburden the targeted website.
2) All the information copied are publicly available and not behind a password or authentication barrier.
3) All the information copied are primarily factual in nature, and the taking did not infringe any rights, including copyrights.
4) All information are used to create a transformative service and are not used to steal market share from the target website by luring away users or creating a substantially similar product.

Part of this section is taken from [Is Webscraping legal?](https://blog.apify.com/is-web-scraping-legal/)

## Support my work!

If you find this mobile application useful, please consider helping me maintain it with a donation or sponsorship :) Thanks
(WIP)
