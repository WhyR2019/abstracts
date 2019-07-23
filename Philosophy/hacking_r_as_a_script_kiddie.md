# Hacking R as a script kiddie

Author: Colin Gillespie (Jumping Rivers)

# Description

Data science is increasing moving away from a users laptop to the cloud. But how secure is this process? When we consider the value of the data that is often being analysed, security should be at the forefront. In this talk, we won't look at complex hacking but instead, focus on the relatively easy hacks that can be performed to access systems. Instead of talking about potential hacks, we'll discuss actual issues that we've discovered (and since fixed). We'll use three R related examples of how it is possible to access a users system. In the first example, we'll investigate domain squatting on the Bioconductor website. This website deals with genomics research, and so the typical users are Government agencies, Universities and large pharmaceutical companies. By registering only thirteen domains (for a total cost of £130), we had the potential to run arbitrary R code on hundreds of unique users. These users included the majority of the top ten Universities in the world, large government organisations and many companies. With a few additional modifications, we could make this almost impossible to detect.
In the second example, we'll look at techniques for guessing passwords on RStudio server instances that are hosted on the internet. Lastly, we'll highlight how users can be a little too trusting when running R code from blogs. The talk will conclude with practical advice on how to avoid these issues both as an individual and as an organisation.
 

