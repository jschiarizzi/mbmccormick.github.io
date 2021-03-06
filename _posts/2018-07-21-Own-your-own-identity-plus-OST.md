---
layout: post
title: "Own your own identity + simple branded tokens to make blockchain projects whole"
---

[Simple Token (OST) is a project](https://ost.com/) to make it easy for people to simply create their own branded blockchain tokens.  I really like the idea of making utility tokens easier to use, having trackable analytics dashboards built in, and spreading useful applications of this tech.  There are lots of chances to experiment with what this project could be used for today.  That's why I'm building an integration with [uPort](https://www.uport.me/) and OST.

## Own your own identity
When you use google or facebook to log into an app you are using google and facebook be the ones to verify exactly who you are, what you like, what your habits are, and who you know.  You let these tech giants own your identity.

[uPort](https://www.uport.me/) is a decentralized alternative, where users own their own identity.  You can log in with uPort instead of google, and are given the choice to approve what data is shared, who you are, and how it is passed between applications.  uPort also opens the possibility for combining different parts of a users online persona; connect reddit, a crypto-wallet, and your birthday to create an identity based on those things.

The connection to OST is that users in each project will have some persona (wallet, soft of) for interacting with that project / community.  Users may find it extremely useful to be able to log into many apps built on OST with 1 identity that they own.  That integration is my contribution.

## Goal
*Allow users to use uPort to log into multiple OST token apps with 1 whole (non-fragmented) identity.*

## Tech stack

### OST API - currently in Alpha v3.
OST is in Alpha III, and not yet public. There are already dozens and dozens of projects being built on it. More info in their post [here](https://medium.com/ostdotcom/announcing-ost-kit-alpha-phase-iii-embedded-wallet-lite-challenge-4a67ea214971)

### uPort js libraries
Uport has great [developer tools and documentation](https://developer.uport.me/).  There are several libraries devs can use, including node and local js libraries.

### Glitch.com - instant node servers
This project is being hosted and built on [glitch](https://glitch.com/), allowing it to be remixed so anyone can instantly use the app however they want.

## Project status
We are now 25% into the timeline for tis project. Where are we?
Glitch server has been setup here: https://uport-tester.glitch.me/

The majority of this project is backend API integration so there is not a lot to show in the front right now. However, we are well on the way to a uport js client that anyone can clone. More info in docs [here](https://developer.uport.me/clients#u-port-js-client).

## What's next
The next step is to integrate OST branded tokens ownership with our decentralized identity that users can log in with.

At the end of this challenge I would like to also make a more clear guide on creating uPort integrations using Glitch.

## Challenges
Challenges so far are connecting the front end JS library to back end APIs.  The identity flow of the application involves using several QR codes that must be passed between front and back-ends.  Keeping this organized has been the challenge of the week.
