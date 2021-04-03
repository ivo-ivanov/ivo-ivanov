<h1>👋 Hi, I’m Ivo Ivanov.</h1>
<h3>Dad.<br>WordPress Developer<br>&amp; UI Designer.</h3>

[![webzino](https://raw.githubusercontent.com/ivo-ivanov/stuff/82390cdc72c0c68c9d873aa014aabd5f6b8df8bd/facebook-page-cover.jpg)](https://www.webzino.com)

<p>Plain and simple - I love design.</p>

<p>I focus on user experience, simplicity and accessibility. I have been using Adobe Photoshop since version 5 and coding my own designs since the one pixel spacer gif era.</p>

<p>I have almost 13 years experience in WordPress development, UI design and branding.</p>

<p>I'm passionate about creating custom, responsive WordPress themes from scratch.</p>

<p><a href="https://www.linkedin.com/in/ivanovivo/"><img alt="LinkedIn @ivanovivo" align="center" src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square" /></a> <a href="https://dribbble.com/ivoivanov"><img alt="dribbble @ivoivanov" align="center" src="https://img.shields.io/badge/-Dribbble-%23ea4c89?style=flat-square" /></a></p>



## WordPress Development Workflow

I develop locally. When it comes to creating an offline WordPress environments I tend to use Local by @<a href="https://github.com/getflywheel">Flywheel</a>. It is one of the most intuitive and powerful tools for the job and allows me to spin fast WordPress installations in containers. Local offers root SSH access, WP-CLI, Database managment, mailcatcher, NGINX and the ability to hot-swap PHP versions. So you can tinker around if your heart desires!

When building a single website with many unique blocks, I use ACF PRO for the block-building process.

I use Gulp extensively to automate things like: 

- Sass to CSS conversion
- Merging media queries
- Error handling
- Auto-prefixing
- Minification
- Sourcemaps
- JS Concatenation / Minification/ Uglification
- Converting ES6 to ES5 with Babel
- Live reload browser with BrowserSync

I like everything to be version controled, so every WP theme is synchronized with GitHub repos though, which is nice for working with other people, tracking issues, using integrations, etc. 

My choise of CD/CI is <a href="https://buddy.works/">Buddy.works</a> When the master branch is pushed to on GitHub, Buddy picks up on that change and runs a pipeline of stuff.
That goes like:

- Running tests when necessary
- Deploying over SFTP/rsync only changed files hosting
- Clear the cache at Cloudflare
- Send a notification over Slack.



<!---
ivo-ivanov/ivo-ivanov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
