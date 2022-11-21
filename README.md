# Kinsta - Hello World - Dockerfile - Node.js
An example of deploying an application using a Dockerfile on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

Get started for free, the first $20 is on us!

[Application Hosting](https://kinsta.com/application-hosting)

[Database Hosting](https://kinsta.com/database-hosting)

## Deployment Lifecycle
When first creating the app Kinsta will create a process from the `CMD` instruction. 
```
CMD ["npm", "run", "start"]
```

Note that if you change this command in the repository the process will **not** be changed by default so you will need to edit it in MyKinsta, in the processes section for your application.
