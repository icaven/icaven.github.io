# icaven.github.io

The landing page for Ian Cavén's GitHub Pages sites: https://icaven.github.io/

GitHub Pages builds it with Jekyll. `index.html` lists the projects in
[`_data/projects.yml`](_data/projects.yml), grouped by topic.

## Adding a project

1. Publish the project's own site: in its repository, enable GitHub Pages
   (Settings → Pages, deploy from a branch). It is then served at
   `https://icaven.github.io/<repo>/`.
2. Add an entry under its topic in `_data/projects.yml` (or add a new topic):

   ```yaml
   - title: Project title
     url: /<repo>/
     repo: https://github.com/icaven/<repo>
     date: 2026-11-07        # ISO date
     summary: One or two sentences on what it is.
   ```

3. Commit and push; the landing page rebuilds in a minute or two.
