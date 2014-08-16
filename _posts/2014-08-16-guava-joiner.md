---
layout: post
title: "Guava Joiner"
tagline: "Playing around with MapJoiner from guava"
category: Programming
tags: [guava]
---

{% include JB/setup %}

###The Guava Joiner
The Guava Joiner class is a very convenient that can be used to map Collections elements into one single String. Also well known as joining elements.

##### Join List elements to a String
You can simply transform a List to Strings:

{% gist kanuku/91ef22592cd66c02be5f %}

`Names =>  Ralph  and  Jaymee and  Sem and  Boris`


##### Join List elements with null values

{% gist kanuku/2c4e8b00f949867354ae %}

`Names => Ralph and Jaymee and Sem and Boris`

##### Join List elements but replace the null values

{% gist kanuku/4b34bab799e7a726d7da %}

`Names => Catharine and Ralph and Jaymee and Sem and Boris`


Joiner class helps you whe from List to String