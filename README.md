# EA Blog

A simple, elegant blog built with Jekyll and hosted on GitHub Pages.

## Features

- Clean, responsive design
- Easy to add new blog posts
- Fast loading and SEO friendly
- Hosted on GitHub Pages

## Adding New Posts

To add a new blog post:

1. Go to the `_posts` directory
2. Create a new file with the format: `YYYY-MM-DD-title.md`
3. Add the following header to your post:
   ```markdown
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +/-TTTT
   categories: [category1, category2]
   ---
   ```
4. Write your post content below the header using Markdown
5. Commit and push your changes

## Local Development

To run the site locally:

1. Install Ruby and Jekyll
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## License

This project is open source and available under the MIT License.
