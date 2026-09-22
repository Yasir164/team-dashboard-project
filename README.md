# Team Dashboard — Git Practice Project #2

A second practice project, this time with **four** feature branches instead
of two, so you can run the same workflow (push, compare, pull request,
resolve conflicts, merge) more times and with more moving parts.

## Branches in this repo

- `main` — base page (title, placeholder comments for four sections)
- `feature/header` — "Alice" adds a header with a logo and title
- `feature/sidebar` — "Bob" adds a sidebar navigation menu
- `feature/cards` — "Carol" adds stat cards to the main content area
- `feature/footer` — "Dave" adds a footer

Every branch adds its own HTML section AND appends its own rules to the end
of `style.css`. That means: the first branch you merge into `main` will go
in cleanly, but every branch after that has a good chance of conflicting
with `style.css`, since they all edited the same region of the same file.
That's intentional — it gives you several rounds of real conflict-resolution
practice instead of just one.

Try merging them in a different order than last time, and see how many of
the four produce a conflict versus merge cleanly.
