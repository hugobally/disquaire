# disquaire

This is a Work in progress -- An incomplete test version of the result can be seen at https://ajna.netlify.app/

disquaire is a responsive static site builder for small record labels or record stores. 

The site's data comes from two sources :
1. The Discogs API -> For the record shop section of the site, data is grabbed from a Discogs user's inventory (see [Discogs Marketplace](https://www.discogs.com/sell/list)) and is displayed in a pretty and convenient manner.
2. The CMS -> For customizing the Discogs inventory with notes and categories and for all the site's content (intro, bands, ..)  

The frontend is built with Gatsby.js and TailwindCSS and can be hosted on Netlify or other similar platforms.
The CMS backend is built with Strapi and can be self-hosted.
