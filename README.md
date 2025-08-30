# fsd-remix

- [Remix Docs](https://remix.run/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/`
- `public/build/`

## Заметки

- генерация типов на основе бэкенд эндпоинтов `npm run generate-api-types`
- https://feature-sliced.github.io/documentation/ru/docs/get-started/tutorial#фильтрация-по-тегам
