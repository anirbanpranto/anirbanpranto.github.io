+++
title = 'The buttefly effect'
date = 2023-11-17T16:55:50+08:00
+++
# In a perfect world

When I was first learning Computer Science, I had a clear roadmap in my mind. I would learn a language end to end, I will learn how to implement data structures and algorithms in
the language, participate in competitive programming, read a tons of books and learn about theoretical computer science, learn hard math, learn machine learning theory, and I will
become an ML Engineer. Although, I am currently working as an AI/Machine Learning Engineer at a [startup](https://blogs.nvidia.com/blog/2022/05/09/ai-malaysia-highways/), and wish to continue being a MLE for the forseeable future, the path I took was not the one I planned initially, I reached the milestone regardless.
This is not gonna be the experience for other people, since a lot of people I know are really good at sticking to a plan, its just
my own experience, and I hope new programmers can learn a thing or two from it.

# Real world is not perfect

Its hard to focus. Computer Science is a moving field. There are so many things to learn, so many things to explore. When I was younger, ML/AI sounded exciting to me,
blockchain sounded like science fiction, compilers, interpreters, competitive programming, OS kernels, there are so many things to learn. I learned programming by solving
algorithm problems on codeforces with C (Yes, with C, not C++), by grinding out my own implementations of data structures. Then I learned C++, did competitve programming for a few more months, and quickly got bored of it. I learned OOP, how to
design databases. But that is it. I got bored of it. Playing around with ML algorithms in Kaggle was fun for a while, then it got boring too. Learning how NodeJS works to make todolists was fun too, but it quickly lost my interest. I learned how [Merkle Tree](https://en.wikipedia.org/wiki/Merkle_tree) works in blockchain and tried to implement my own cryptocoin as well, but I got bored of it too. You can see a pattern here,
I get bored of things really quick, I change my mind really quick. (This only applies to software, I'm a very calm and decisive person when it comes to other matters) But good thing about this is, I got exposed to a lot of things, and anything I found interesting, **I gave it a shot**. You'll see how this is useful in a bit.

All of these, were my first year of Computer Science school. I never could finish a project, the number of my unfinished projects kept getting bigger and bigger. Because, although learning something new always made me feel happy, I never felt the drive to
build something without purpose. I built only the part that felt interesting to me, but never finished any project, because I had no idea what's the point of it all.

Tldr - Real life is weird, things don't go as planned.

# Things got real

I somehow landed a job at a startup by the end of my first year. Maybe it was luck, maybe it was something else, but I was hired. I got my first task to build an API to match postcodes to states and integrate the API with a VueJS frontend.
It was my first experience building any API, or using VueJS, but I did it, I learned how backend APIs worked, and how VueJS works and manages states. It was exciting for me, because I was learning something new, and it had a purpose. From that point onwards,
I kept learning new concepts, with each new feature I had to develop, I learned something new. In the span of 4 months, I learned ReactJS, ExpressJS, Typescript, VueJS and how to make applications for production environment.

# Basics

I read online that Backend Engineers need to know about web security, networks, OS, threads, processes and a 100 other things. But I never felt like learning them without a purpose. As I kept working on the startup,
I got exposed to all the different aspects of backend development. I learned how to deploy applications in the cloud, how to expose ports to the internet securely, how to use concurrency at production applications to make things more performant,
how to use system calls in the OS, how to run scheduled jobs, how DNS works, domain works, Amazon Web Services and how to piece together the different parts of the cloud ecosystem to build applications, how to write well designed software to interface with the cloud. As I worked on more and more complex applications, I learned more about backend engineering concepts, getting exposed to a real scenario when you have to use
a concept, made it more clear to me why I had to learn something. Reading documentation is one of the most important skills I gained from this time-frame, and quickly grasping how to integrate any third party API became a second nature. When I know that an end user is going to use the application, it was easier for me research on the problem and coming up with solutions for the specific problems.
But, again, soon some of the things got very repetitive over the next year and I got bored of the engineering, as I had a firm grasp on the concepts and I didn't have a reason to learn more.

# Stepping up

I was bored, as my work was not challenging enough, but as time went by, we realized that the current application architecture is not sustainable for larger amount of users. Its slow, sluggish, and
hard to maintain. Its full of performance issues. To fix it, first I had to learn how to profile an application, and optimize certain functions, I was excited again. I tried out different things, learned how to do caching using redis,
how to use load balancers to horizontally scale applications, how to replicate databases, how can we use different network protocols to transfer data (i.e. - gRPC instead of http), in order to solve problems I had in the production applications. This also taught me how to be proactive about development, and actively pitch solutions to
the HR. Not all of the ideas were accepted, some were. But I still ended up learning different approaches of designing scalable systems. Around the 1.5 year mark, I ended up being responsible for entire architecture of the [startup](https://parceldaily.com) I was working for. The turning point was when I had to redesign our monolith into a microservice based architecure.
A lot goes into researching about a suitable approach, in real world startups (or even big companies) are bounded by budget and engineering hours they can spare. So I had to actively research on how to scale a system with minimal rewrites and making sure that AWS doesn't cost us $100k to run the infrastructure. The final design was simple (using message queues and lambdas to separate some heavy services),
and I learned a lot.

At this stage, I knew what to look up when it's needed, because I had taken a lot of time in my earlier days to explore a lot of topics, breadth was more important to me. But when I needed it, I could also go
into depth in those topics later, because of the exposure I had.

# But what about Machine Learning?

Same applies to ML, I tried a lot to learn it by myself, but I always lost motivation within a week, because I had no idea what to apply ML to. Around year 2 of my undergrads, I took up a position at my university as a Research Assistant. I was working on something really unique and intriguing. I had a purpose again.
I read hundreds of papers on the topics, learned history of approaches to solve the problems, and I ended up learning classical machine learning until the state of the art approaches in ML. Some might ask, **But what about the math?**, I might have been lucky, but my dad is a Mathematician, and I had a lot of help from him
in understanding the math, and I grew up in a very good highschool where I had built up a lot of mathematical intuition, my previous endeavors in competitive programming taught me how to approach unknown problems with known tools, and all of that indirectly translated to my research. During my research I got a firm grasp on both theory and practice
in machine learning. My research background in computer vision is closely related to what I work on now, Object Detection -
![Work](https://gotapway.com/wp-content/uploads/2023/01/VehicleTrack.gif 'What I work on nowadays.')

# So how did you become an MLE?

Because of working a lot on operational side of backend engineering, and being active in ML research, I had just about enough knowledge to work as an MLE, the main function of
MLE's in almost any company is to operationalize ML models, which simultaniously requires knowledge of ML theory and knowledge of engineering. Which I had built some depth on in prior years.

# The butterfly effect

The main thing is, you should get exposure to things that interest you. Going down the rabbit hole is very useful. Whatever interests you, try it out. You don't need to be perfect in it,
you don't even have to go in depth if its not necessary, don't stop if you want to explore in depth either, but trying out different things is important. In my engineering journey, I have become language, stack or domain agnostic, because I tried
out anything that seemed interesting. Even if I didn't have prerequisite knowledge, I tried things. Don't stop yourself from trying something. You like web development and you wanna try Svelte? Go ahead. Don't stop
because other's said React is the best thing to learn for a job. You want to learn [Max flow Min cut](https://en.wikipedia.org/wiki/Max-flow_min-cut_theorem) algorithms? Do it.
No technology is too new to learn, no technology is too old either. Don't learn Node and Express because everyone does it, it does not matter what framework you know. They all boil down to the same fundamentals.
Learn to be agnostic about languages and frameworks, jobs don't care usually which framework you are good at, they only focus on your fundamental knowledge, frameworks and languages vary in every company, so don't spend too much time into thinking which one to learn.
Research about things by yourself, don't let anyone choose what you find interesting and convenient. I never really optimized my learnings for a job, I learned things that I felt were interesting to me. Years later, the skills I gained from my explorations were useful to me
in the most unpredictable situations. My career is a result of [butterfly effect](https://en.wikipedia.org/wiki/Butterfly_effect), random unrelated actions set much bigger things into motion. A lot of it is luck too, I just had really good initial
conditions.

Maybe these all are bad advices and I have survivorship bias, maybe I am truly just extreamly lucky. But whatever it is, it helped me in my life and career.

Happy coding!
