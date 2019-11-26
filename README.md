# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact

```swift
Website: https://catfact.ninja/fact

JSON: 
{
  "fact": "Cat's urine glows under a black light.",
  "length": 38
}
```
2. A list of 150 random users in English.
```swift
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
```
3. All the repos on Github with Pursuit their name
```swift 

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
```
4. All the JavaScript repos on Github with Pursuit in their name
```swift 
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
```    
5. All the Swift repos on Github with Pursuit in their name
```swift 
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
```
6. A list of all Pokemon
```swift
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
```
7. A list of all items in Fortnite
```swift
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
```            
8. A list of all Game of Thrones Episodes.
```swift

Website: https://api.got.show/api/show/episodes

JSON: "_id": "5cc074bf04e71a0010b85a1c",
    "title": "Lord Snow",
    "season": 1,
    "episode": 3,
    "runtime": 58,
    "directed_by": "Brian Kirk",
    "createdAt": "2019-04-24T14:37:51.760Z",
    "updatedAt": "2019-04-24T14:37:51.760Z",
    "__v": 0
}
```
9. A list of all songs with "Love" in the title.
```swift

```
10. All information about Petyr Baelish from the Game of Thrones books
```swift
Website: https://www.anapioficeandfire.com/api/characters/823

JSON: 
"name": "Petyr Baelish",
"gender": "Male",
"culture": "Valemen",
"born": "In 268 AC, at the Fingers",
"died": "",
"titles": [
    "Master of coin (formerly)",
    "Lord Paramount of the Trident",
    "Lord of Harrenhal",
    "Lord Protector of the Vale"
],
"aliases": [
    "Littlefinger"
],
```
11. All the movies Leonardo Dicaprio has acted in 

```swift

```

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat

1. 200:
```swift
Website: https://randomuser.me/api/
Descitpion: OK,indicates that the request has succeeded 

```
1. 301
```swift
Website: ??
Descitpion: Moved Permanently, is used for permanent URL redirection, which means the links should be updated.
```
1. 400:
```swift
Website: https://api.themoviedb.org/3/person/{person_id}?api_key=<<api_key>>&language=en-US
Descitpion: Bad request, indicates a client error 
```
1. 401
```swift
Website: 
Descitpion: Unauthorized, indicates lack of valid authentication credentials by client
```
1. 403
```swift
Website: 
Descitpion: Forbidden, indicates that access to the valid URL requested in forbidden for a reason 
```
1. 404
```swift
Website: 
Descitpion: Not found, indeicates that server could not find what was requested  
```
1. 418
```swift
Website:
Descitpion: Im a teapot, although not explicitly defined it indicates request cant be handled by server 
```
1. 500
```swift
Website:
Descitpion: Internal Server error, indicates server encountered an unexpected error
```




