


## color-coded highlighting notation

- green: (`repo.json` /a, `plugins.json` /a)
	- cyan: (`repo.json` /a, `plugins.json` /a) BUT automatic JSON detection blocked by [Anubis](https://github.com/TecharoHQ/anubis)
- yellow: (`repo.json` on IA /a, `plugins.json` /a)
- orange: (`repo.json` on IA /a, `plugins.json` on IA /a)
- red: (`repo.json` on IA /a, `plugins.json` on IA n/a)
- purple: (`repo.json` on IA n/a)

## scrape notes

* only `repo.json` scraped: cyan
* `repo.json` and `plugins.json` scraped: yellow, orange

## paste hosting recommendations

Android `CloudStream Beta` (`com.lagradost.cloudstream3.prerelease`) fetches updates from given `repo.json` URL's regularly; **avoid using ephemeral paste hosting services**.