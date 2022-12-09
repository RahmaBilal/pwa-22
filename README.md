# 19 Progressive Web Applications (PWA): Text Editor

## Summary 

For this challenge, I built a text editor that runs in the browser. This app will be a single-page application that meets the PWA criteria. It will feature a number of data persistence techniques that serve as replacement in case one of the options are not supported by the browser. This application will also function offline, making it easier for clients to use when they are not online. 


## Table of Contents
- [Summary](#summary)
- [Description](#description)
- [User Story](#user-story)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Links](#links)
- [Questions](#questions)


## Description 

To build this text editor, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. You will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Demo

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## Screenshots

<img width="1440" alt="Screenshot 2022-12-09 at 03 06 31" src="https://user-images.githubusercontent.com/108250116/206690110-7ee5c577-9bc8-40ec-ad15-6c47c656f5fa.png">

<img width="1440" alt="Screenshot 2022-12-09 at 03 18 23" src="https://user-images.githubusercontent.com/108250116/206690200-eb69e173-cf05-4c94-84bd-02b6cdf89e28.png">

<img width="1440" alt="Screenshot 2022-12-09 at 11 29 59" src="https://user-images.githubusercontent.com/108250116/206693300-a40471e9-d737-4783-88c4-180b468c6336.png">

<img width="1440" alt="Screenshot 2022-12-09 at 11 30 03" src="https://user-images.githubusercontent.com/108250116/206693323-b796d7e4-3b6f-4687-ab47-37b73b5eb8ee.png">

## Links

Deployed URL: https://pure-badlands-50243.herokuapp.com
<br>
GitHub URL: https://github.com/RahmaBilal/pwa-22

## Questions
If you have any queries about this task or would like to contribute to it, then don't hesitate to contact me on: rahma.bilal@gmail.com. My GitHub is: https://github.com/RahmaBilal
