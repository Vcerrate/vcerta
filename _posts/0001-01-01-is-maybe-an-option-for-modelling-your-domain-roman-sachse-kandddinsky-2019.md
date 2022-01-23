---
title: "Is Maybe an Option (for modelling your domain)? - Roman Sachse - KanDDDinsky 2019"
image: "https:\/\/i.ytimg.com\/vi\/2Dwnv3vdZl8\/hqdefault.jpg"
vid_id: "2Dwnv3vdZl8"
categories: "Education"
tags: ["KanDDDinsky","DDD","KDDDconf"]
date: "2022-01-23T07:01:11+03:00"
vid_date: "2019-12-09T08:45:00Z"
duration: "PT42M35S"
viewcount: "1651"
likeCount: "42"
dislikeCount: ""
channel: "KanDDDinsky"
---
{% raw %}Null is used to model a variety of states within an application. Be it to model the absence of a field in a database table, the return value when parsing something unparsable, an unsuccessful API call or to initialize some fields empty because the “ORM expects it that way”. The problem with null is that it is never completely clear to the developer whether something can or should be null at some point of the application and what null means in a specific case. Most statically typed functional programming languages avoid the problem completely by not allowing null at all. They introduce a new data type called Option or Maybe which allows us to lean on the compiler to check whether we forgot to handle the unexpected absence of a value. This leads to a greater trust in our applications and reduces runtime errors tremendously. Options can also be used to help modelling our domain but often they lack clear semantics of why a value is absent in a specific situation. Luckily options are just a small subset of the beautiful concept of sum types. Those sum types allow us to model different states of our application with ease and great expressiveness. Furthermore they allow us to get rid of many errors that are usually modelled with exceptions by taking care of them in our domain model. This talk will give you the ability to get rid of nulls with options and abstract over this concept with the help of sum types to make your code more expressive and your domain model easier to comprehend for your team and for the business.{% endraw %}
