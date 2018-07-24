{% if site.github != true %}
- hostname: {% if site.url =='' %}`None`{% else %}`{{ site.url }}`{% endif %}
- timezone: `{{ site.timezone }}`
- build time: `{{ site.time }}`
- build environment: `{{ jekyll.environment }}`


{% else %}

## Meta Data for {{ site.repository }}
### Versions

- jekyll: `{{ site.github.versions.jekyll }}`
- kramdown: `{{ site.github.versions.kramdown }}`
- liquid: `{{ site.github.versions.liquid }}`
- maruku: `{{ site.github.versions.maruku }}`
- rdiscount: `{{ site.github.versions.rdiscount }}`
- redcarpet: `{{ site.github.versions.redcarpet }}`
- RedCloth: `{{ site.github.versions.RedCloth }}`
- jemoji: `{{ site.github.versions.jemoji }}`
- jekyll-mentions: `{{ site.github.versions.jekyll-mentions }}`
- jekyll-redirect-from: `{{ site.github.versions.jekyll-redirect-from }}`
- jekyll-sitemap: `{{ site.github.versions.jekyll-sitemap }}`
- github-pages: `{{ site.github.versions.github-pages }}`
- ruby: `{{ site.github.versions.ruby }}`

### Other stuff
- hostname: `{{ site.github.hostname }}`
- pages_hostname: `{{ site.github.pages_hostname }}`
- api_url: `{{ site.github.api_url }}`
- environment: `{{ site.github.environment }}`
- organization_members: `{{ site.github.organization_members }}`
- build_revision: `{{ site.github.build_revision }}`
- project_title: `{{ site.github.project_title }}`
- project_tagline: `{{ site.github.project_tagline }}`
- owner_name: `{{ site.github.owner_name }}`
- owner_url: `{{ site.github.owner_url }}`
- owner_gravatar_url: `{{ site.github.owner_gravatar_url }}`
- repository_url: `{{ site.github.repository_url }}`
- repository_nwo: `{{ site.github.repository_nwo }}`
- repository_name: `{{ site.github.repository_name }}`
- zip_url: `{{ site.github.zip_url }}`
- tar_url: `{{ site.github.tar_url }}`
- clone_url: `{{ site.github.clone_url }}`
- releases_url: `{{ site.github.releases_url }}`
- issues_url: `{{ site.github.issues_url }}`
- wiki_url: `{{ site.github.wiki_url }}`
- language: `{{ site.github.language }}`
- is_user_page: `{{ site.github.is_user_page }}`
- is_project_page: `{{ site.github.is_project_page }}`
- show_downloads: `{{ site.github.show_downloads }}`
- url: `{{ site.github.url }}`
- releases: `{{ site.github.releases }}`
{% endif %}
