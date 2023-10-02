# Stella framework

minimalist PHP framework

## backstory

in 2017 I started working on social network Kyselo. I didn't liked mainstream PHP frameworks so I used my own hodge-podge framework created of components which I liked. I also developed some of my own components.

Later in 2020 I created two little apps which I wanted to be less hodge-podge. So I created my own microframework but I didn't bother to document it. Now when I created third application I decided to document it properly and make code a little bit cleaner. I named it Stella because first application made with it was called Stela (with one L) and Stella (with two L) is great album by Swiss band Yello.

## features

as stated in [this comment from HN](https://news.ycombinator.com/item?id=16726370) there are several components common (and almost required) for all web frameworks regardless of technology used. For me these are:

- autoloading (and composer support)
- dependency injection
- routing with nice URLs (and http request and response objects and redirects)
- redirects and flash messages
- template rendering
- app configuration
- debugging component (and displaying error pages in production)

## optional modules

- Adminer for editing database
- forms component
- database component
- command line argument parser (cligen)

## possible demo applications

(nothing of these is yet implemented)

- pastebin clone but for CSV
- URL shortener
- self-hosted Bandcamp clone
- bug tracker / project managment software
- forum like it's still 2003
- wiki
- simple text-only Discord clone

