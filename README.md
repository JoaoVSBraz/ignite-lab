# Ignite Lab RectJS

Ignite Lab is an application where you can watch video lessons.

![](/src/assets/ingite-lab.gif)

## Contents

- [Overview](#overview)
- [My process](#my-process)
- [References](#references)

## Overview

Ignite Lab is a web application built during the ignite lab event by the rocketseat platform. It is a platform that allows you to watch youtube videos and recover its content from the graphcms content management system through graphql requisitions.

## My process

This ReactJS project is the first one I've implemented online through the Vercel platform.

Good learning during the event was using the graphql query language to retrieve data from an API provided by graphcms - a content management system. Furthermore, other tools, like apollo client and graphql code generator, were used to facilitate the development.

You can see one graphql query in action just below

```graphql
query GetLessons {
  lessons(orderBy: availableAt_ASC, stage: PUBLISHED) {
    availableAt
    id
    lessonType
    slug
    title
    }
  }
```

You can view the project online [here!](https://pretty-yogurt-08d.notion.site/Maratona-Explorer-d876326a9ece4faa909bb71259c047c0)

## References

- [GraphQL](https://graphql.org/)
- [GraphQL Code Generator](https://www.graphql-code-generator.com/)
- [Apolo client](https://www.apollographql.com/docs/react/)
- [Hire me on Linkedin](https://www.linkedin.com/in/joaovsbraz/)