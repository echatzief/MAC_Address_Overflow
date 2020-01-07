## Introduction

MAC address flooding attack is very common security attack. MAC address table in the switch has the MAC addresses available 
on a given physical port of a switch and the associated VLAN parameters for each.

This attacks are sometimes called MAC address table overflow attacks. To understand the mechanism of a MAC address table overflow attack we must recall how does a switch work in the first place.

## Enviroment Setup

Firstly, we open up a terminal and type the below command:

* sudo apt update && sudo apt upgrade

After that our system is already updated and set  in order to download the packages that we need for this lab.We will use a GitHub repository to retrieve the source code that we will use.So we clone the repository locally.
