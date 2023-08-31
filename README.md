# DGHub Studio

<a href="https://t.me/dghub_founder" target="_blank"><img src="https://avatars.githubusercontent.com/u/112307287?v=4 | width=100" style="height: 170px !important;width: 170px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

### Buy Me a Coffee

<a href="https://www.paypal.me/dghubfounder" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 37px !important;width: 170px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

[![Pub](https://img.shields.io/pub/v/font_awesome_flutter.svg)](https://pub.dartlang.org/packages/dghub_web_scrapper)

## What is Web Scraping

- Content by Harkiran

Web scraping is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications. There are many different ways to perform web scraping to obtain data from websites. These include using online services, particular API’s or even creating your code for web scraping from scratch. Many large websites, like Google, Twitter, Facebook, StackOverflow, etc. have API’s that allow you to access their data in a structured format. This is the best option, but there are other sites that don’t allow users to access large amounts of data in a structured form or they are simply not that technologically advanced. In that situation, it’s best to use Web Scraping to scrape the website for data.

Web scraping requires two parts, namely the crawler and the scraper. The crawler is an artificial intelligence algorithm that browses the web to search for the particular data required by following the links across the internet. The scraper, on the other hand, is a specific tool created to extract data from the website. The design of the scraper can vary greatly according to the complexity and scope of the project so that it can quickly and accurately extract the data.

## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
dependencies:
  dghub_web_scrapper: <latest_version>
```

## Import package

```dart
import 'package:dghub_web_scrapper/dghub_web_scrapper.dart';
```

## Example - Normal

```dart
DGHubWebScrapper.get('https://cv.dghub.in/').then((html){

    }).onError((error, stackTrace) {

    });
```

## Example - Support JavaScript

```dart
DGHubWebScrapper.getFullLoaded('https://cv.dghub.in/').then((html){

    }).onError((error, stackTrace) {

    });
```

## Importants Methods and propriets

- Table by antonio-nicolau

| Methods                     | Mean                                                          |
| --------------------------- | ------------------------------------------------------------- |
| html.title                  | Return the page title                                         |
| html.getElementById         | Return a single element searching for ID on the page          |
| html.getElementsByClassName | Return a list of elements according class passed as parameter |
| html.getElementsByTagName   | Return a list of elements according tag passed as parameter   |
| html.querySelector          | Return single element passing a list of selector              |
| html.querySelectorAll       | Return a list of elements passing a list of selector          |
| text                        | Return text atribute from a tag returned                      |
| src                         | Return src atribute from a tag returned                       |
| href                        | Return href atribute from a tag returned                      |

- Package created by Min Thant Htet
