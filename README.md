# JSON Server Vercel

- https://json-server-vercel-sage.vercel.app/articles
- https://json-server-vercel-sage.vercel.app/events
- https://json-server-vercel-sage.vercel.app/taken
- https://json-server-vercel-sage.vercel.app/todos

- https://json-server-vercel-sage.vercel.app/posts
- https://json-server-vercel-sage.vercel.app/comments
- https://json-server-vercel-sage.vercel.app/profile
- https://json-server-vercel-sage.vercel.app/sport
- https://json-server-vercel-sage.vercel.app/url
- https://json-server-vercel-sage.vercel.app/people

# Wijziging db.json

- https://json-server-vercel-sage.vercel.app/db.json
- De gekopieerde inhoud van deze url eerst in db.json zetten
- db.json uitbreiden/aanpassen
- commit db.json
- Vercel is read-only dus wijzigingen worden op de server niet in db.json weggeschreven. Bij herstart van server wordt de inhoud van deze db.json als uitgangspunt genomen (en raak je de wijzigingen die niet zijn weggeschreven kwijt).

## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository:

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

![Powered by Vercel](https://images.ctfassets.net/e5382hct74si/78Olo8EZRdUlcDUFQvnzG7/fa4cdb6dc04c40fceac194134788a0e2/1618983297-powered-by-vercel.svg)

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
  "posts": [{ "id": 1, "title": "json-server", "author": "typicode" }],
  "comments": [{ "id": 1, "body": "some comment", "postId": 1 }],
  "profile": { "name": "typicode" }
}
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
