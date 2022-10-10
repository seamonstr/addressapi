# Backend Engineer - Technical Challenge

## Introduction
Welcome and congratulations on reaching the technical assessment stage of the interview
process at Xxxxx.
We are excited to potentially have you join the Engineering team, where you will work alongside
amazing people to build a xxxx.

## Background
The purpose of this task is to gauge your familiarity with Python and Django, with the way you
write code and design APIs, and to provide a basis on which to discuss in a subsequent
interview stage.
You are expected to use the tools and techniques you are comfortable with to produce good
quality code that can be understood and extended by engineers with a variety of backgrounds
and experience.
You are expected to address the functional requirements listed below, and any
non-functional requirements you see fit.

## Task - Address Book API
Your task is to design a REST-ful API and create a server for it in Python, using the Django Rest
Framework, which provides functionality to authenticate a user and to manage the addresses
associated with their account. Only authenticated users should be able to view and manipulate
addresses.
Assume this API will be used by a variety of clients, like public and internal websites, or native
mobile apps.

You should document the API so it is clear what endpoints are available, how they can be
queried and what response can be expected in return.
You should commit this code to a code repository of your choice and share this with us.

## Requirements
1. User is able to create a new address
    * \* User will not be able to add a duplicated address to their account
1. User is able to retrieve all their postal addresses
    * \* User is able to retrieve a large number of address entries in a practical way
    * \* User is able to filter retrieved addresses using request parameters
1. User is able to update existing addresses
1. User is able to delete one
    * \* User is able to delete multiple addresses
    * \* User is able to authenticate with a username and a password
1. \* User can log out

\* Bonus requirements - feel free to give any of these a go if you have any spare time, but we
don’t expect you to complete them all.

Additional Notes
* A user can have a large number of addresses;
* A user can have addresses from any country;
* A user's client can hold state (if necessary for certain endpoints);
* You must ensure the application can be run by another engineer with access to the
repository;
* You do not need to deploy this code to a server;
* You should document any assumptions you make about the product, especially where
you would have a question about it.
