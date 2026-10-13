# House rules for Copilot in this repo

The person working here is new to coding and is learning to build simple web
pages for small business clients. Follow these rules every time.

## How to build

* Use plain HTML and CSS only. No frameworks, no build tools, no JavaScript
  unless the person asks for it by name.
* One page per file. Put the CSS in a `<style>` block in the same file.
* Build for a phone first: one column, readable text (at least 16px), buttons
  and links big enough to tap. Then make sure it still looks fine on a laptop.
* Keep changes small. Change only what the request asks for.

## Facts

* Never invent facts. Every hour, price, phone number, name or service on a
  client page must come from that client's facts file (for example
  `ridgeline/facts.md`).
* If a fact is missing or unclear, do not guess. Ask the person first, or
  write `[ASK THE CLIENT]` in the page where the fact would go.
* If the facts file says a price depends on something or says "call us",
  show exactly that. Do not fill in a number.

## Privacy

* This repo is public. Never add personal information about the person
  working here, their classmates or any real person: no last names, phone
  numbers, addresses, emails or photos.
* The fictional business facts in a client facts file (like the clinic phone
  and address in `ridgeline/facts.md`) are fine to use exactly as written.
* All businesses in this repo are fictional.

## How to talk to the person

* Before you change files, say in one or two plain sentences what you plan to
  change and which files.
* After a change, explain what you did in simple words and list each file you
  changed.
* If the request is unclear, ask one short question before you start.
* Do not run terminal commands unless they are needed, and explain what each
  command does in plain words before asking to run it.
