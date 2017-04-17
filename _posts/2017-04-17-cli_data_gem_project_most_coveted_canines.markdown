---
layout: post
title:  "CLI DATA GEM PROJECT: most_coveted_canines"
date:   2017-04-16 21:20:32 -0400
---

As an animal-lover and the proud owner of two rescue dogs, I decided to design an application that ranks the 50 most popular dog breeds in the United States and provides information about their key characteristics. After Westminster Dog Show 2017, the American Kennel Club (AKC) released a list of the most popular dog breeds in 2016. I retrieved data from the AKC ranking webpage, which is comprised of two main parts. The principal page contains the full ranking list of dogs, displayed by breed and popularity rank. Clicking on an individual dog's link directs the user to that particular dog's profile page. Anticipating that my project would contain a Dog class, I planned to scrape a dog instance's @url and @breed attributes from the main full ranking webpage and extract additional attributes, such as @group, @personality, @rank, @year_recognized, @exercise, @grooming, @fun_fact and @appearance, from each dog's profile page.
