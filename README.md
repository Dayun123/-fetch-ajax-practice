# Fetch/Ajax Practice

I've never fully understood how to use Fetch, XMLHttpRequests, or the JQuery $.ajax() method. I will work through a few examples of each in this project to get more familiar with how they work.

## Usage

Each example will have it's own route, and there may end up being multiple routes below each of these in order to separate the examples:

- /fetch
- /xmlHttpRequest
- /jQueryAjax

There will be buttons on each page that make HTTP calls to the server and retrieve various responses, which will be either logged to the console, downloaded, or displayed on the page. Some buttons will throw errors and demonstrate proper error-handling or improper error-handling.

## Installation

Clone into the repo and enter the directory:

```bash
$ git clone git@github.com:Dayun123/fetch-ajax-practice.git && cd fetch-ajax-practice
```

Install dependencies and run the app:

```bash
$ npm install && DEBUG=fetch-ajax-practice:* npm start
```