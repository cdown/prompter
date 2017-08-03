A super simple/dumb prompter that I've been using for a few years. I find it
helps keep procrastination at bay.

This is fairly specific to my workload -- for example, if no entry with
"Trello" was entered today, an annoying message appears to do that, since
that's where I store my long-term TODO items.

A dialog pops up every 15 minutes and asks you what you're doing, with the
resulting input going to `~/.prompter/<date>` by default.

You can set `PROMPT_DELAY_SECS` in the environment to change the number of
seconds between prompts. You can also set `LOG_DIR` to log to some dir other
than `~/.prompter`.

`WORK_START_HOUR` and `WORK_END_HOURk mark when to actually show the prompt.

Also see [nota](https://github.com/cdown/nota), which is what I use to
aggregate these afterwards.
