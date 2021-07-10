---
layout: post
title: "Things That They Don't Teach (Episode 1)"
date: 2021-07-11 00:02:57 +0800
categories: series
---

There are a lot of things that we learn at university as a Computer Science major. Some of them always come in handy at all types of situations, some of them we rarely ever use in a real life job. Often these things that we learn at university are extremely hard compared to what we do in day to day jobs (For example : Ever used Dijkstra's algorithm in your Software Engineering job? Apart from a very small set of people, the answer is probably "NO"). Most people solely focus on class materials during their university days, but when they finally graduate and get their first engineering job, its a whole another world. Most things that are used or applied in a job are not taught in classroom, which makes it really hard for a lot of people to efficiently perform on a job. They have to learn a lot of new concepts and technologies that were simply out of focus during their undergrads.

Undergrad education is very much focused on research and that requires really hard and strong fundamentals, which is why undergrad curriculum focuses on hard and rarely used concepts. When I first started my startup job as a Software Engineer, I also felt very lost, but I eventually managed to learn a lot of technologies and concepts that I know are not included in my university curriculum. So this series is how I'm going to help out fellow students learn things that they find really intimidating as a CS Student. This is Things that they don't teach in class.

On today's episode we're gonna learn basics of Restful APIs. What are Restful APIs, how are they used and how to use one. On next few episodes we will also learn how to build one. So let's get started.

API means Application Programming Interface, this explains absolutely nothing. In my early days of programming I tried to learn about this a lot but failed to find good explanations online. The main idea is, suppose I have a program that does some job A. Now I create a way for other people to use my program to do job A in their own program. So what happens is, their program calls my program and do A, without them needing to program the same thing again. In short API is a way of using prewritten functionalily in a program.

Now what is Rest API? Rest means, Representational state transfer. Its basically an API that talks using HTTP requests, or in short, API that talks over the internet. This is the most commonly used API architecture in software engineering applications nowadays.

So basically a Restful API takes in HTTP requests from a remote location, and sends in responses. Responses have a HTTP Status code with them as well which indicate what type of response we are receiving. A successful response will usually have 200, 201 or similar 2xx responses. 404, 402, 403 are error that indicate different types of errors like "Not Found", "Forbidden" etc. But I think the best way of explaining this concept is to use a random api.

Basically we have a client that sends request to a server, the server serves the client with a response.

A rest api usually has a endpoint or simply a url which takes in a request. Easily explained, when you enter `https://google.com` on your web browser, your browser sends a `GET` request to the `https://google.com` endpoint or url. Similarly other restful apis also have some type of endpoint that takes in `GET`, `POST`, `PUT`, `PATCH`, `DELETE` or other types of requests. By typing into a browser, we can only make `GET` requests, for other types of requests we need to use programming.

Now lets, send a get request to this endpoint through our browser. Usually get requests are used for getting data, while post requests are used to send data to the API/Server.

```
https://random-data-api.com/api/address/random_address
```

Entering this in our web browser will show this (Try it!)

```json
{
  "id": 1479,
  "uid": "727d2e38-b4d8-413a-b1e4-c4534f409e2c",
  "city": "New Lucretiaside",
  "street_name": "Heath Locks",
  "street_address": "849 Danica Valley",
  "secondary_address": "Suite 556",
  "building_number": "22133",
  "mail_box": "PO Box 358",
  "community": "Paradise Village",
  "zip_code": "00486",
  "zip": "66747",
  "postcode": "55734-0770",
  "time_zone": "Asia/Baku",
  "street_suffix": "Corner",
  "city_suffix": "ville",
  "city_prefix": "North",
  "state": "Illinois",
  "state_abbr": "IL",
  "country": "Mozambique",
  "country_code": "TG",
  "latitude": -84.4418358405454,
  "longitude": 135.16534579206473,
  "full_address": "538 Lindsay Springs, West Abrahamberg, UT 94252"
}
```
This is a response that we received from the `https://random-data-api.com` server and the endpoint that we used to get the data was `/api/address/random_address/`. Here `https://random-data-api.com` is called the base url.

This video is getting too long, so lets end it here today. On next episode we'll make our own api and send other types of requests and see how they work! :) Thanks for reading.