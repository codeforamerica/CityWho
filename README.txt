# CityWho #

A public directory of communities in your city

## What is CityWho? ##
Cities are full of people joining groups to talk about 
making the city a better place to live.

We are creating a directory of community groups, with reviews, in the hopes of 
improving the quality of all active groups while also eliminating the noise of
searching through dead groups.

This tool is a directory pointing to groups that are publicly listed, as well
as groups that are obscure, that have been shared by community members.

The groups retain full control of privacy and determining who can or cannot
join the group.


### Kinds of groups that can be listed ###
* Web resources (with type, ownership, location, source, title, link)
* Mailing lists (email addresses)
* Facebook groups
* Yahoo groups
* Meetup groups
* Public hearings groups

### Search Groups ###
* Location (All groups can have a mapped service area if it is complicated)
* Neighborhood
* Topic

### Examples of what you can search for
* Find a block watch near your house
* See if your apartment building has a tenants group already
* Find community garden groups in your neighborhood
* See if there are networks of nearby parents who want to find neighbors to share childcare
* Quality contacts from city staff who have living knowledge of important community groups
* Public hearings
* People who are talking about fixing a dangerous intersection
* Parents working to improve schools
* Neighborhood leaders looking to clean up parks
* Volunteer committees for organizing street parades
* Groups of artists talking about painting street murals

### Additional Features
* Recommend
* Search
* Review
* Share
* See the name
* See a link to join the group
* See email list to join a mailing list
* Suggest changes to update information
* Be linked to tips on making good groups
* Quality metadata for group
** Source
** Date of last update
** Changes
* Upload CSV file with lists of web resources, mailing lists, organizations etc.
* An API for getting lists of groups by lat/lon, neighborhood, city, topic


################################# Get involved with the project ################


### Pitch in!
This is a Code for America civic software project. We would love it
if you wanted to help make this a reality.

The main organizer of this project is 
Chach Sikes: chacha (at) codeforamerica (dot) org
@chachasikes on Twitter.

### Background
Code for America is based in San Francisco, and we are partnering with
the Cities of Seattle and Philadelphia in the creation of this project.
The Cities have requested a similar tool, and Code for America fellows
interviewed at least 200 people (city staff, community organizers),
nearly all of whom all said that mailing lists and email are an integral 
part of getting word out. (And if not email, then Facebook & Yahoo groups.)


### Timeline
A video explanation of this project will be available May 26, 2011

We will be working with our cities to define important features,
and with folks at civic code-a-thons in Seattle. (June 3/4/5)


### Get the Code on GitHub

https://github.com/codeforamerica/CityWho

This tool is built with Drupal. It will be available as an installation
profile, and eventually it could use the Open Public features. 
Open Public is a special distribution of Drupal that has been especially designed
for governments. Ease of use and security were the most important features.

The goal is to make this tool as easy to get up and running
as possible, which means that we will probably make this an Open Public 'app.'

But first we will work on designing and building the tool
to be useful for community organizers in our cities.

Wiki for this project:
Features list for this project:


### What is DataWiki?
A front-end for aggregating and manageing structured civic data.

DataWiki makes it easier to import CSV from the Web, or to point to a URL
for small civic datasets. These could be anything from community resources
to farmer's markets to 

The DataWiki is a multipurpose front end for collecting data and converting it
into data that can be easily accessible for simple web applications, such as
those build with CouchApp or jQuery Mobile. 

In a pinch, the DataWiki itself can be modified to act as a simple web 
application interface by anyone who is comfortable with configuring Drupal sites. 
The goal of this front-end is to make it easier for non-developers to aggregate 
community data and resources to more easily create compelling data 
for building civic applications.

### Installation
*In Progress* (May 2011)

See INSTALL.txt


### Later Content Types ### 
* Community resource (a type of place or service where communities 
meet up, with a preferred format for accepting messages)
** Community Bulletin Board (address, person to ask, kinds of flyers, foot traffic)
* Organization (names of non-profits, city departments & contacts)  
(This should really be a different tool.)

### Fancy Features ### 
* Load group reviews & group data with MeetupAPI
* Load facebook discussion with FacebookAPI (maybe)
* Search for groups on Meetup, Yahoo, Facebook (facebook search tool doesn't seem to have API interface)
* Import groups from GroupsNearYou (many groups who have already been mapped)
* Import email addresses for mailing lists
** Formats: csv: name of list (optional), email, description, moderator_name, 
moderator_email, tags, type (based on description TBD)
** SuperEasy: just send us an email to chacha@codeforamerica.org with a list of names. We will add them.
** Probable (for cities): Import Microsoft Outlook (vCards?)  (??)
** Add using the web interface /node/add/mailing-list
* Send announcement to the group without needing to join the group
An email would be sent to the group that they could sign up for an announcement service, 
containing a digest of announcements from other groups.
Then, anyone who wanted to send that group a message could post a message to a public inbox.

