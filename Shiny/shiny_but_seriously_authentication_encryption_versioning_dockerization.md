# Shiny, but seriously: authentication, encryption, versioning, dockerization.

Author: Kamil Sijko (Transition Technologies)

# Descripition

R and Shiny are great – they enable you to prototype quickly. After you prototype you pass your idea to “adult programming languages” like Python-Django to build it again, but this time with authentication, encryption, versioning and possibly in cloud-friendly docker containers. On this presentation I won’t tell you that you can build commercial-grade webapps with Shiny, but during my work with MedStream Designer team (http://mi.tt.com.pl/en/home/) we have set-up stack that satisfies our standards and customers needs in 90% of cases. And is free.
I will tell you about authentication and encryption with proxies: things like ShinyProxy, ShinyStudio, but also other solutions for other stacks (we have used Tomcat). I will explain why we have used Microsoft R Open instead of regular R interpreter. I will talk about versioning (of code and dependencies). I will describe our experiences and caveats we encountered while working with databases (credentials, pooling connections). And lastly: why have we dockerized the whole app and how to easily achieve it (I will share the code).