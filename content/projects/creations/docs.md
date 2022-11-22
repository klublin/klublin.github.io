{
  "title": "Google Docs Clone",
  "date": "2018-02-11T12:41:05-05:00",
  "image": "/img/docs.PNG",
  "link": "https://github.com/klublin/CSE356",
  "description": "Google docs offers real time collaborative editing. This program offers the same thing with a different synchronization method. Google Docs uses Operational Transform(OT) to synchronize users. This project uses a CRDT implementation called YJS to sync users. The app is deployed on the Cloud and offers authentication of users, an Edit UI and document search",
  "tags": ["JavaScript","NodeJS", "Express", "MongoDB", "elasticsearch", "UpCloud", "Linux", "Server Sent Events","REST APIs", "Redis", "YJS", "React", "Nginx"],
  "fact": "",
  "featured":true
}

Google docs offers real time collaborative editing. This program offers the same thing with a different synchronization method. Google Docs uses Operational Transform(OT) to synchronize users. This project uses a CRDT implementation called YJS to sync users. The app is deployed on the Cloud and offers authentication of users, an Edit UI and document search. User authentication is done using Redis and MongoDB, front-end was created using React and backend is an Express App with a reverse proxy of Nginx. The program can currently handle more than 900 requests per second on a 2 core system. 
