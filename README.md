# vite-tinybase-ts-react-crsqlite

This is a [Vite](https://vitejs.dev/) template for a simple app, using TypeScript and React, that
integrates [TinyBase](https://tinybase.org/) with [Vulcan](https://github.com/vlcn-io)'s cr-sqlite to provide persistence and synchronization
across clients.

It is a fork of the awesome [Vulcan
vite-starter](https://github.com/vlcn-io/vite-starter) app, with small changes
to introduce TinyBase into the view layer. All the credit for the magic goes to
the [cr-sqlite](https://github.com/vlcn-io/cr-sqlite) project!

When you're up and running, the app should look like this:

![A four-way sync between browsers](fourway.png)

## Instructions

1. Make a copy of this template into a new directory:

```sh
npx tiged tinyplex/vite-tinybase-ts-react-crsqlite my-tinybase-app
```

2. Go into the directory:

```sh
cd my-tinybase-app
```

3. Install the dependencies:

```sh
npm install
```

4. Run the application:

```sh
npm run dev
```

5. Go the URL shown and enjoy! Open up multiple windows to see the
   synchronization in all its glory.

## Other templates

There are nine templates for TinyBase, of which this is one:

|     | Template                                                                                       | Language   | React | Plus                |
| --- | ---------------------------------------------------------------------------------------------- | ---------- | ----- | ------------------- |
|     | [vite-tinybase](https://github.com/tinyplex/vite-tinybase)                                     | JavaScript | No    |                     |
|     | [vite-tinybase-ts](https://github.com/tinyplex/vite-tinybase-ts)                               | TypeScript | No    |                     |
|     | [vite-tinybase-react](https://github.com/tinyplex/vite-tinybase-react)                         | JavaScript | Yes   |                     |
|     | [vite-tinybase-ts-react](https://github.com/tinyplex/vite-tinybase-ts-react)                   | TypeScript | Yes   |                     |
|     | [vite-tinybase-ts-react-sync](https://github.com/tinyplex/vite-tinybase-ts-react-sync)         | TypeScript | Yes   | Synchronization     |
| 👉  | [vite-tinybase-ts-react-crsqlite](https://github.com/tinyplex/vite-tinybase-ts-react-crsqlite) | TypeScript | Yes   | CR-SQLite           |
|     | [tinybase-ts-react-partykit](https://github.com/tinyplex/tinybase-ts-react-partykit)           | TypeScript | Yes   | PartyKit            |
|     | [tinybase-ts-react-electricsql](https://github.com/tinyplex/tinybase-ts-react-electricsql)     | TypeScript | Yes   | ElectricSQL         |
|     | [expo/examples/with-tinybase](https://github.com/expo/examples/tree/master/with-tinybase)      | JavaScript | Yes   | React Native & Expo |

## License

This template has no license, and so you can use it however you want!
[TinyBase](https://github.com/tinyplex/tinybase/blob/main/LICENSE),
[cr-sqlite](https://github.com/vlcn-io/cr-sqlite/blob/main/LICENSE), and
[Vite](https://github.com/vitejs/vite/blob/main/LICENSE) themselves are each MIT
licensed.
