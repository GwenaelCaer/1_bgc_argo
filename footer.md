% This defines the footer of the site, and is not parsed as a regular "page"
% We point to it with the following in `myst.yml`:
% site:
% parts:
% footer: footer.md

% Here we use `grid` to add a basic grid structure to the HTML,
% but the formatting column sizes are defined manually in css/footer.css
% see the `grid-template-columns` line.
:::::{grid} 3 3 5 5
:class: outer-grid col-screen

<!-- Project description -->

::::{div}

<!-- # Landing Pages -->

```{image} https://gitlab.ifremer.fr/odatis-public/vre/config/raw/main/logos/logo_odatis-transparent.svg
<!-- :width: 50px -->
:width: 50px
:align: left
```

This is a description of our project. And a [link to its homepage](https://github.com/jupyter-book/example-landing-pages).
::::

<!-- Spacer between project description and links columns -->

::::{div}
::::

<!-- Link columns -->

% This a _second_ grid embedded within the first one, to create nicer
% responsive design experience. This grid will have a single column on narrow screens,
% and fan out into three columns on wide screens. However, it always remains within
% its parent grid column.

::::{div}

- [About](https://odatis-public.gitlab-pages.ifremer.fr/vre/portal/)
- [Documentation](https://odatis-public.gitlab-pages.ifremer.fr/vre/documentation/)
- [Gallery](https://odatis-public.gitlab-pages.ifremer.fr/vre/gallery/)
  ::::

<!-- ::::{grid} 1 1 3 3

:::{div}

- [About](https://odatis-public.gitlab-pages.ifremer.fr/vre/portal/)
- [Documentation](https://odatis-public.gitlab-pages.ifremer.fr/vre/documentation/)
- [Gallery](https://odatis-public.gitlab-pages.ifremer.fr/vre/gallery/)
  :::

:::{div}

- A second column!
- With multiple entries
  :::

:::{div}

- And what about a third
  :::

:::: -->

:::::
