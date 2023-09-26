# Epic Stack with Fastify

This example repo shows how to use [Fastify](https://fastify.dev/) in place of [Express](https://expressjs.com/) in [The Epic Stack](https://www.epicweb.dev/epic-stack).

Remix itself is loaded as a fastify plugin using [remix-fastify](https://github.com/mcansh/remix-fastify). To add more plugins from [the fastify ecosystem](https://fastify.dev/ecosystem), you can drop them in the `server/plugins` directory and [fastify-autoload](https://github.com/fastify/fastify-autoload) will pick them up.

See [The Epic Stack Getting Started README](https://github.com/epicweb-dev/epic-stack/blob/main/docs/getting-started.md#development) for how to setup and run the project.
