# ts-express-microservice-boilerplate

An example Node microservice using Express, TypeScript, and Jest.

Includes examples for Jenkins, CircleCI, GCP Cloudbuild, and Kubernetes.

Also includes an example of static file serving. I recommend serving files in
production out of a CDN rather than from a Node server, or using Node only to
handle requests for those files.

To run in dev, `npm ci && npm start`

To run without docker, `npm run dev` instead

To build, `npm version [major|minor|patch]`

[LICENSE](./LICENSE.md)
