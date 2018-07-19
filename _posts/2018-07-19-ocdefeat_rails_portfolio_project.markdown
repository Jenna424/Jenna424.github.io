---
layout: post
title:      "OCDefeat Rails Portfolio Project"
date:       2018-07-19 20:09:26 +0000
permalink:  ocdefeat_rails_portfolio_project
---

Pursuing my interest in psychology and programming, I designed a Rails application that allows patients and mental health professionals to collaborate in the development of Exposure and Response Prevention (ERP) plans, a therapy technique that is commonly used in the treatment of Obsessive Compulsive Disorder (OCD).

One of the challenges that I encountered while coding was figuring out the best approach to slim down "fat" controllers, namely, cluttered `#index` actions that contained repetitive, branching conditional logic to handle filtering. The Query Object Design Pattern was an effective strategy to refactor my code. In Rails, a query object is a "Plain Old Ruby Object (PORO)," typically a class that enables you to write a large, complex, composite SQL query with ActiveRecord.
