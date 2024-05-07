# PhoenixCms

Headless CMS fun with Phoenix LiveView and Airtable.

## Tutorial

### Contents 

- id: the ID of the section.
- position: An auto-increment number that specifies the order of the section within the page.
- type: the type of the section, which can have three different values:
- hero: for a hero section containing a big title and subtitle.
- text_and_image: for sections that have some text and an image.
- feature: for a section that has a list of items with some text and an icon.
- title: the title of the section.
- content: the main content of the section. It can store HTML.
- image: the main image of the section. Stored as an attachment.
- styles: any additional styles that we want to add to the section.

### Stores
- slug: the SEO friendly slug for the article.
- title: the main title of the article.
- description: the article's excerpt.
- image: the main image of the article. Stored as an attachment.
- content: the main content of the article. It can store HTML.
- author: the email of the article's author.
- published_at: the publication date of the article.

## Dev

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.
