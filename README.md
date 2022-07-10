<p align="center">
   <h1> Titanic Disaster Survival Prediction </h1>
</p>

 <p>
  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/RD191295/Titanic_Survival_Prediction?color=purple">
</p>

  
This is a tutorial in an IPython Notebook for the Kaggle competition, Titanic Machine Learning From Disaster. The goal of this repository is to provide an example of a competitive analysis for those interested in getting into the field of Machine Learning. This IPython Notebook provide EDA, Visualization of Data , Data Cleaning ,Feature engineering and Model buliding with hyper parameter optimization

# Steps in Ipython Notebook

Ipython Notebook Cover following Steps:

- Data models managed visually or through CLI
- Auto-generated human-editable source code
- Node.js server built with Nest.js and Passport
- REST API and GraphQL for CRUD with relations, sorting, filtering, pagination
- Custom code generated app
- Admin UI built with React-Admin
- Role-based access control
- Docker and docker-compose integration
- Automatic push of the generated code to your GitHub repo

# Getting Started

You can get started with Amplication immediately on the Amplication Cloud. 

Alternatively you can set up a local development environment.



See [Amplication website](http://amplication.com/) or [Amplication docs](http://docs.amplication.com/) for more details.

[Watch this video](https://youtu.be/tKGeLXoPr94) for a quick recap of everything you get with Amplication.

## Amplication Cloud (SaaS)

Launch Amplication from [app.amplication.com](http://app.amplication.com/)

## Development Environment (Local)

### System Requirements

:bulb: Before you begin, make sure you have all the below installed:

- [Node.js v14 or above](https://nodejs.org/en/download/)
- [npm v7 or above](https://github.blog/2020-10-13-presenting-v7-0-0-of-the-npm-cli/)
- [Docker](https://docs.docker.com/desktop/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git/)


### Initializing all the packages

Amplication is using a mono-repo with multiple packages. To initialize all the packages on a local development environment, including running a docker image for the DB and seeding the DB.

1. Execute the following commands in the project root folder:

```jsx
npm install
npm run setup:dev
npm run start
```
This will install all the required dependencies, run the necessary scripts and init a Docker-based Postgres server.

2. Go to `.../packages/amplication-server` and execute the following command:

```jsx
npm run start
```

3. Go to `.../packages/amplication-client` and execute the following command:

```jsx
npm run start
```




### Setting Up Amplication Manually

You can use a manual step-by-step approach to set up Amplication in a local development environment. To do that, you should follow the following instructions for **Setting Up Amplication Server**, and **Setting Up Amplication Client**.

#### Setting up [Amplication Server](https://github.com/amplication/amplication/blob/master/packages/amplication-server/README.md)

Amplication Server is the main component of the platform that provides all the core functionality to design and create low-code applications.
The server exposes a GraphQL API for all actions. The server is built with the following awesome open-source technologies: Node.js, NestJS, Prisma over PostgreSQL, GraphQL API, and many more...

#### Setting Up [Amplication Client](https://github.com/amplication/amplication/blob/master/packages/amplication-client/README.md)

Amplication Client is the front end of the platform that provides you with an easy-to-drive UI for building your next low-code application.
The client is based on React, Apollo client, Primer components, React Material Web Components, Formik, and more.

# Beta version

Amplication is currently in Beta version. This means that we are still working on essential features like production-ready hosting, migrations, and stability to our console.

How does it affect you? Well... mostly it doesn't. Every app generated using Amplication platform contains popular, documented, secured, and supported production-ready open-source components & packages. Your app is stable, scalable, and production-ready you can deploy and rely on. You can read more about the generated app and its stack here https://docs.amplication.com/docs/getting-started

# Support

## Ask a question about Amplication

You can ask questions, and participate in discussions about Amplication-related topics in the Amplication Discord channel.

<a href="https://discord.gg/Z2CG3rUFnu"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

## Create a bug report

If you see an error message or run into an issue, please [create bug report](https://github.com/amplication/amplication/issues/new?assignees=&labels=type%3A%20bug&template=bug_report.md&title=). This effort is valued and it will help all Amplication users.


## Submit a feature request

If you have an idea, or you're missing a capability that would make development easier and more robust, please [Submit feature request](https://github.com/amplication/amplication/issues/new?assignees=&labels=type%3A%20feature%20request&template=feature_request.md&title=).

If a similar feature request already exists, don't forget to leave a "+1".
If you add some more information such as your thoughts and vision about the feature, your comments will be embraced warmly :)


# Contributing

Amplication is an open-source project. We are committed to a fully transparent development process and appreciate highly any contributions. Whether you are helping us fix bugs, proposing new features, improving our documentation or spreading the word - we would love to have you as part of the Amplication community.

Please refer to our [Contribution Guidelines](./CONTRIBUTING.md) and [Code of Conduct](./code_of_conduct.md).

# Contributors ✨
<table>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/43705455?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Raj Dalsaniya</b></sub></a><br /><a href="https://github.com/Rd191295/Titanic_Survival_Prediction/commits?author=RD191295" title="Code">💻</a></td>
   </tr>
</table>

