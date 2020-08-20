# Basic NPM scripts starter template

Starter template I use for building simple static sites. Uses npm scripts to start watch files files and build. Requires Node and NPM (or yarn).

✓ Compresses images

✓ Compiles sass

✓ Compresses JS

✓ Autoprefixes CSS

✓ Live browser refreshing

✓ Includes Normalize CSS

## Usage

__1) Install dependencies__

```

npm i

```

__2) Start server and start building__

```

npm start

```

Defaults to using a development build. When going into production, change `"build:css"` script from "npm run dev:scss && npm run autoprefixer"` to `"npm run prod:scss && npm run autoprefixer"`.

## Credits

Based on foundation referenced in [this article](https://css-irl.info/a-modern-front-end-workflow-part-1/)