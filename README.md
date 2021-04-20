# Nutshell

Single page social site that features an article news list, public message board, local events, and task lists. 

## Project Goals

Built using React; this app focused on state changes, useEffect as well as continuing to reenforce knowledge about apis. MVP was to have CRUD achieved for all of the above links.

### Getting Started

Start by logging into the page with your email address if you are an existing user. You may register for the site as well an store data on your local JSON server. As you navigate the site feel free to add intersting articles, tasks to be completed, local events, or send messages on the public message board. Users may add friends by searching the directory or adding a new friend from the 

### Getting started with the project

To start, clone or copy the repository and place it in the root of your web directory. Aftering cloning The project requires json-server to be running in order to interact with the local API. 'json-server --watch db.json --port 8088'.


### How to help with the project

As of now outside commits to this repository are not allowed

### This project is maintained by

3HTTPs in a pod: @pour-theoil, @EthanMathis and @HPreast 

### Sample JSON data
`{
  "users": [
    {
      "id": 0,
      "name": "null",
      "email": "null"
    },
    {
      "id": 1,
      "name": "Steve Brownlee",
      "email": "me@me.com"
    }
  ],
  "articles": [
    {
      "id": 1,
      "userId": 3,
      "url": "https://www.quantamagazine.org/newfound-wormhole-allows-information-to-escape-black-holes-20171023/",
      "title": "Wormholes Allow Information to Escape Black Holes",
      "synopsis": "Check out this recent discovery about workholes",
      "timestamp": 1618411096199
    }
  ],
  "messages": [
    {
      "userId": 2,
      "friendId": 0,
      "message": "from me",
      "id": 83
    }
  ],
  "events": [
    {
      "userId": 3,
      "message": "Party like its 1993",
      "eventdate": "2021-04-14T10:49",
      "location": "Nashville, TN",
      "title": "Time Testing",
      "id": 14
    }
  ],
  "tasks": [
    {
      "id": 0,
      "userId": 1,
      "title": "Random Task",
      "task": "Loads of work to be done",
      "completedby": "2021-02-11T15:24",
      "isComplete": true
    }
  ],
  "friends": [
    {
      "id": 1,
      "userId": 1,
      "currentUserId": 3
    }
    {
      "id": 0,
      "userId": 1,
      "currentUserId": 3
    }
  ]
}
`
