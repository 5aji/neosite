The web hacker's blog.

Neosite (name pending) is a collection of frameworks and configuration to make writing custom
static sites a breeze. No need for complex Go templates, or strange Wordpress-but-we-made-it-static
SaaS products. Out of the box, Neosite provides a lean, refined take on the blogs of yesteryear. But 
when the situation calls for it, the author can instantly bail out into powerful React, embedded into the post.

Goals:
- Entirely static, whenever possible. Only pages that have interactive widgets need javascript.
- Markdown with all the fixings. LaTeX math, syntax highlighted code, and sidenotes.
- Consistent and minimal presentation that is stylized but approachable.
- A delightful blogging experience with hot-reload and front matter.

Neosite aims to use only the essential web frameworks and technologies to make the user experience
easier. This includes Next.js, React, and Sass, as well as `@next/mdx` for markdown with react components.

These libraries obviously have many sub-packages and dependencies, but that's just the life of modern
web stacks. The ethos of this project runs contrary to other "Next.js blogs" in that I do not care about SEO
at all. 
