# Kielipankki-newsdesk

News feed storage for The Language Bank of Finland.

- Feeds are kept in data/<feed>.yaml

- A feed is a list of entries with the properties `title`, `body`, `created`, and optionally `expires` and `tags`:

  ```
  - title:
    fin: Nyt tapahtuu
	eng: It's happening
	swe: Det händer nu
  - body:
    fin: Nyt se todellakin tapahtuu.
	eng: It's really happening now.
	swe: Det händer verkligen nu.
  - created: 2026-04-23
  - expires: 2026-04-30 # It's not going to be happening long
  tags:
    - happenings
  ```
