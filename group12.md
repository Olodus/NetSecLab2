# EDA491 Network Security Lab 2
# Peer review for Group 12 by Group 75

## Formatting
Generally good. Just remember to add "Group" in front of the group number on the cover page to show what the number is actually refering to. 

## General
The introduction and conclusion are in a lot of cases a bit unfocused.
In both chapters you start talking about subjects which are not supposed to be addressed in that chapter.
The sentences don't always fit that well together either. This would not be a problem if you didn't use that many connecting words like "In addition" or refering to the previous sentence with "this".
Besides that the presentation of the requirements and implementation are generally good. Comments acan be found under the appropriate chapter.

## Introduction
- Why do you use IPv4 in the first sentence? I think what you probably wanted to use instead was iptables maybe?
- We don't think it is appropriate to refer to the "Lab PM". We are supposed to view ourselves as consultants in this assignment. 
- Your description of a stateful firewall is strange. Any firewall distinguishes between different packets. Furthermore, the description of a firewall is not supposed to be presented in any detail at all in that part of the text.
- The last sentence starts with "In addition..." even though it doesn't have anything to do with the the description of a stateless firewall which the last sentence was about. It also seems more like a description of the requirements, which is not supposed to be talked about in the introduction. 

## Chapter 2
- Remove "mentioned earlier" from the first sentence. This is the start of a new chapter, it should be self-contained. 
- Poor description of OpenSSH. SSH is mainly used for remote control of a system. It can be used to forward traffic (or tunneling as you called it) but that is just one very specific use of it. 
- A more common description of Apache is a Web server. 

## Chapter 3
You are using two numbered lists (one in 3.1 and one in 3.2) in this Chapter but the numbers has nothing to do with eachother. 
Maybe use a simple point-list instead in 3.1 and keep the numbers in 3.2. 
We like how 3.2's numbers are refering to the numbers in the Firewall configuration listing, maybe just comment more clearly on that fact.

In 3.1 you once again make a reference to the lab pm.

## Chapter 4
- In 4.3, how did you test SSH with a browser? Think there are a couple of tests missing here. 

## Chapter 5
- Don't say that it is only "in some ways stateful" after you in previous chapters called it stateful. Either remove "in some ways" or remove the sentence completly.
- Why do you write snort after the NIDS? Snort is one implementation of a NIDS.
- In the last sentence, switch "possibly" for "possible". 

## Chapter 6
- Remove "not limit ... too much" from the second sentence. What does "not too much" mean? Is it a little or not at all? A better description would be that your goal was to "keep the applications running without interference" or something to that end.
- The last two sentences does not go together very well. Why did fullfulling the requirements fullfil this line? 
