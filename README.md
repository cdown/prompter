A super simple/dumb prompter that I've been using for a few years. I find it
helps keep procrastination at bay. In general I like to keep these.

A dialog pops up every 5 minutes and asks you what you're doing, with the
resulting input going to `~/.prompter/<date>` by default.

You can set `PROMPT_DELAY_SECS` in the environment to change the number of
seconds between prompts. You can also set `LOG_DIR` to log to some dir other
than `~/.prompter`.

Also see [daily](https://github.com/cdown/daily), which is what I use to
aggregate these afterwards.
