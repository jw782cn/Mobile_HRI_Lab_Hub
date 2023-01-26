## Deliverables


1. [Link](https://github.com/jw782cn/Mobile_HRI_Lab_Hub/tree/main/Lab0/mobilehri_ws) to the folder of a ROS package that contains a publisher and a subscriber 

2. List 5 questions you have about ROS following the tutorial, answers you have found and things you still don't get

- What's the relationship between nodes?

Basically, the nodes are like people. Some people are publishers and some people are subscribers. Publisher uses topic to publish messages to subscriber

- What's the relationship between publishers and subscribers?

The publishers and subscribers are actually the same relationship as client and server model. I've learned computer network before, and I found this concept familiar.

- What's timer_callback?

This function is a time based function and control robots in time period.

- Why do we need spin and destroy?

The spin function can keep the robots working and destroy is needed after working because not deleting unworking node is unsafe.

- What is listener_callback?

This function is called by listner / client / subscriber to receive messages sent from publishers.


3. Feedback on the bootcamp: What was easy and what was difficult to understand?

I've learned computer network and bash languages before, and I also have interned in TikTok to write bash and docker to setup environments. Thus I found the settings pretty easy for me.

The difficult part is to use the online environment. I'm still getting used to it and making changes to environments.

