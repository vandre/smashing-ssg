# Custom mini Static Site generator

This is from my [Smashing magazine article on creating your own SSG](https://smashingmag.com) For full details on creating this, read the article.

## Installation

To get the site up and running: 

```bash
cd site
npm install
npm run dev
```

To get the Studio up and running:

1. Install the Sanity CLI

```bash
npm install -g @sanity/cli
```

2. Connect `/studio/` to your Sanity account and project

```bash
cd studio
sanity init
```

3. Install and serve

```bash
npm install
sanity start
```

4. Connect your Sanity project to the site by opening `/site/utils/SanityClient.js` and replacing `projectId` and `dataset` with the correct information created by the Sanity CLI.

## Install from [sanity.io/create](https://www.sanity.io/create?template=brob/sanity-template-pure-html)

Want a 1-click installer? [This Starter link](https://www.sanity.io/create?template=brob/sanity-template-pure-html) will give you the code, initialize the Studio, and deploy both to Netlify.