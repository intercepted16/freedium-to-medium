This userscript automates the redirection of Medium articles to `freedium.cfd`, a site that allows you to read Medium Premium articles for free! The reason you cannot use a simple redirection pattern is due to the following reasons:

Medium is an SPA; therefore browsing articles and clicking on one wouldn't rerun the script
Some Medium articles are on nested subdomains, not on the domain `medium.com`
This userscript solves those issues. It runs on the first navigation of a two nested subdomain site & checks if it's a Medium article using some `meta` tag properties. It exits if we're not. It also checks whether we're on an article on `medium.com`.
