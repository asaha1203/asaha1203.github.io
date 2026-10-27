# Minimal Theme

[Demo the Theme](https://orderedlist.com/minimal/)

This is the raw HTML and styles that are used for the *minimal* theme on [GitHub Pages](http://pages.github.com/).

Syntax highlighting is provided on GitHub Pages by [Pygments](http://pygments.org).

## Site content

The homepage (`index.html`) places the complete paper list at `#papers` immediately below the research introduction, followed by current and previous research projects at `#currently`, then the remaining about-me content at `#beyond-research`. The top header provides `about // papers // currently // beyond research // contact` navigation across the site. The former `papers.html` and `current_work.html` pages have been removed.

Contact details (email, LinkedIn, and Twitter) are on the homepage at `#contact`. All contact links point there; the separate `contact.html` page has been removed.

The homepage uses a centered name with site navigation directly below it. The biography and research statement span the content width, with Google Scholar, email, LinkedIn, and Twitter below the text. Both link rows use `//` separators. The photo and caption are not displayed; the original `assets/me.jpeg` is retained. Papers are unnumbered, section headings are left-aligned, and organizations, academics, industry, and personal interests are grouped under “Beyond Research.” Homepage-specific styles are scoped to `.home` so secondary pages retain their layout.

The content area has a maximum width of 760px. Header navigation sits 4px below the name, with a 28px gap before the page content. Stylesheet references include a shared `?v=4` cache version; increment it across all HTML pages when publishing stylesheet changes.

The cream background and selective research-text colors are retained. Both unvisited and visited links explicitly use underlined medium-grey text (`#666`), darkening to `#444` on hover, keyboard focus, and activation. The research introduction summarizes the statement of purpose.

Publication titles, authors, and statuses were reconciled with the latest application CV and statement bibliography. Update the homepage directly when these change; keep submitted papers clearly labeled and link manuscripts only when a public URL is available.

Preview locally with `python3 -m http.server 8000`, then open `http://localhost:8000/`.

# License

This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).



