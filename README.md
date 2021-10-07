# ❤️ Eleventy + Netlify CMS Starter ❤️

I got tired of re-rolling all the base stuff when setting up new static sites, so this is my opinionated (i.e. works for me) boilerplate for Netlify CMS/Eleventy/Tailwind.

Blade is based heavily on https://github.com/surjithctly/neat-starter but simplifies even further by removing Alpine, which I find isn't needed for most clients. It also simplifies the content and templates so there's less to remove to get started building. The Neat Starter project needs to have something nice to look at when first spun up as it might be the first thing someone sees that is new to this stack. Blade assumes familiarity and is ready to get straight to work.

I'm at https://treshenry.net and https://www.linkedin.com/in/treshenry/.

# Create New Site

1. Clone this repo ```git clone https://github.com/ohnoimdead/blade ./mynewsite```
2. Install deps ```npm install```
3. ```npm run build``` (first time only)
4. ```npm run start```
5. or ```netlify dev``` to run with the Netlify backend and use the CMS in local dev.