# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact

Website: https://catfact.ninja/fact

JSON: 
{
  "fact": "Cat's urine glows under a black light.",
  "length": 38
}

2. A list of 150 random users in English.

Website: https://randomuser.me/api/ 

JSON: 
"results": [
{
  "gender": "male",
  "name": {
    "title": "mr",
    "first": "brad",
    "last": "gibson"
  },
  "location": {
    "street": "9278 new road",
    "city": "kilcoole",
    "state": "waterford",
    "postcode": "93027",
    "coordinates": {
      "latitude": "20.9267",
      "longitude": "-7.9310"
    }

3. All the repos on Github with Pursuit their name
Website: https://api.github.com/search/repositories?q=pursuit

JSON: 
"items": [
{
    "id": 22592439,
    "node_id": "MDEwOlJlcG9zaXRvcnkyMjU5MjQzOQ==",
    "name": "pursuit",
    "full_name": "purescript/pursuit",
    "private": false,
    "owner": {
        "login": "purescript",
        "id": 6556677,
        "node_id": "MDEyOk9yZ2FuaXphdGlvbjY1NTY2Nzc=",
        "avatar_url": "https://avatars2.githubusercontent.com/u/6556677?v=4",
        "gravatar_id": "",
        "url": "https://api.github.com/users/purescript",
        "html_url": "https://github.com/purescript",
        "followers_url": "https://api.github.com/users/purescript/followers",
        "following_url": "https://api.github.com/users/purescript/following{/other_user}",
        "gists_url": "https://api.github.com/users/purescript/gists{/gist_id}",
        "starred_url": "https://api.github.com/users/purescript/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/purescript/subscriptions",
        "organizations_url": "https://api.github.com/users/purescript/orgs",
        "repos_url": "https://api.github.com/users/purescript/repos",
        "events_url": "https://api.github.com/users/purescript/events{/privacy}",
        "received_events_url": "https://api.github.com/users/purescript/received_events",
        "type": "Organization",
        "site_admin": false

4. All the JavaScript repos on Github with Pursuit in their name

Website: https://api.github.com/search/repositories?q=pursuit+language:JavaScript

JSON: 
"items": [
{
    "id": 29826657,
    "node_id": "MDEwOlJlcG9zaXRvcnkyOTgyNjY1Nw==",
    "name": "argo",
    "full_name": "albertosantini/argo",
    "private": false,
    "owner": {
        "login": "albertosantini",
        "id": 328179,
        "node_id": "MDQ6VXNlcjMyODE3OQ==",
        "avatar_url": "https://avatars2.githubusercontent.com/u/328179?v=4",
        "gravatar_id": "",
        "url": "https://api.github.com/users/albertosantini",
        "html_url": "https://github.com/albertosantini",
        "followers_url": "https://api.github.com/users/albertosantini/followers",
        "following_url": "https://api.github.com/users/albertosantini/following{/other_user}",
        "gists_url": "https://api.github.com/users/albertosantini/gists{/gist_id}",
        "starred_url": "https://api.github.com/users/albertosantini/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/albertosantini/subscriptions",
        "organizations_url": "https://api.github.com/users/albertosantini/orgs",
        "repos_url": "https://api.github.com/users/albertosantini/repos",
        "events_url": "https://api.github.com/users/albertosantini/events{/privacy}",
        "received_events_url": "https://api.github.com/users/albertosantini/received_events",
        "type": "User",
        "site_admin": false
    }
    
5. All the Swift repos on Github with Pursuit in their name

Website: https://api.github.com/search/repositories?q=pursuit+language:Swift

JSON:
"items": [
{
    "id": 99703757,
    "node_id": "MDEwOlJlcG9zaXRvcnk5OTcwMzc1Nw==",
    "name": "Pursuit-Core-iOS",
    "full_name": "joinpursuit/Pursuit-Core-iOS",
    "private": false,
    "owner": {
        "login": "joinpursuit",
        "id": 5825944,
        "node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
        "avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
        "gravatar_id": "",
        "url": "https://api.github.com/users/joinpursuit",
        "html_url": "https://github.com/joinpursuit",
        "followers_url": "https://api.github.com/users/joinpursuit/followers",
        "following_url": "https://api.github.com/users/joinpursuit/following{/other_user}",
        "gists_url": "https://api.github.com/users/joinpursuit/gists{/gist_id}",
        "starred_url": "https://api.github.com/users/joinpursuit/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/joinpursuit/subscriptions",
        "organizations_url": "https://api.github.com/users/joinpursuit/orgs",
        "repos_url": "https://api.github.com/users/joinpursuit/repos",
        "events_url": "https://api.github.com/users/joinpursuit/events{/privacy}",
        "received_events_url": "https://api.github.com/users/joinpursuit/received_events",
        "type": "Organization",
        "site_admin": false
    }

6. A list of all Pokemon

Website: https://pokeapi.co/api/v2/pokemon/

JSON: 
{
    "name": "bulbasaur",
    "url": "https://pokeapi.co/api/v2/pokemon/1/"
},
{
    "name": "ivysaur",
    "url": "https://pokeapi.co/api/v2/pokemon/2/"
},
{
    "name": "venusaur",
    "url": "https://pokeapi.co/api/v2/pokemon/3/"
},

7. A list of all items in Fortnite
Website: https://fortnite-api.theapinetwork.com/store/get

JSON: 
{
"lastUpdate": 1574640000,
"lanuage": "en",
"data": [
    {
        "itemId": "76f99cb1-ada0-4c12-bbf3-4e34cece6a97",
        "lastUpdate": 1574640000,
        "store": {
            "isFeatured": true,
            "isRefundable": true,
            "cost": 1500,
            "occurrences": 0,
            "isNew": false
        },
        "item": {
            "name": "Sklaxis",
            "description": null,
            "type": "outfit",
            "rarity": "epic",
            "costmeticId": null,
            "images": {
                "icon": "https://fortnite-public-files.theapinetwork.com/outfit/ccc09f5f-7973-4f37-a543-9248af62bd38.png",
                "featured": "https://fortnite-public-files.theapinetwork.com/featured/76f99cb1-ada0-4c12-bbf3-4e34cece6a97.png",
                "background": "https://fortnite-public-files.theapinetwork.com/image/76f99cb1-ada0-4c12-bbf3-4e34cece6a97.png",
                "information": "https://fortnite-public-files.theapinetwork.com/image/76f99cb1-ada0-4c12-bbf3-4e34cece6a97/item.png"
            }
            
8. A list of all Game of Thrones Episodes.
Website: 

JSON: 


1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
1. 301
1. 400
1. 401
1. 403
1. 404
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



