# OpenLearn

**Learn. Grow. Together.**

OpenLearn is a free website that helps beginners learn software development. It links to open courses from MIT, Harvard and others, explains what each skill involves, and includes a guide that plans four years of study.

**Live site:** https://rishi-dev67.github.io/Openlearn/

## Features

- **Four-year plan guide:** a chat on the front page where a student picks a career path (Web Developer, Data and AI, Software Engineer or Full-Stack Engineer) and sees a plan for Year 1, Year 2, Year 3 and Year 4.
- **Course pages:** Web Development, Python, Databases and SQL, and Data Structures and Algorithms. Each page shows:
  - what you will learn
  - what you need to know first
  - market demand, time to learn and average pay as bar graphs
  - the skills needed to get a job
  - links to free courses
- **Blog:** detailed beginner guides on how the web works, choosing a first language, SQL, and learning data structures.
- **Easy to use:** large readable text, works on phones and keyboards, and needs no sign-up.

## Project structure

```
openlearn/
├── index.html      The whole website (HTML, CSS and JavaScript)
├── logo-icon.png   Small logo used in the header
├── logo-full.png   Full logo used on the home page
└── README.md       This file
```

## Run it on your computer

No installation is needed.

1. Download or clone the repository.
2. Double-click `index.html` to open it in your browser.

For automatic refresh while editing, open the folder in VS Code and use the **Live Server** extension.

## Publish it with GitHub Pages

1. Push the files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the **main** branch and the **/ (root)** folder, then click **Save**.

The site goes live within a few minutes.

## Customize the content

Everything is inside `index.html`:

| What to change | Where to find it |
| --- | --- |
| Colors | The `:root` block at the top of the CSS |
| Courses, graph numbers, requirements, links | The `C` object in the script |
| Four-year plans for each path | The `T` object in the script |
| Blog posts | The `B` array in the script |

To add a course, copy an existing entry in `C`. To add a blog post, copy an entry in `B` and give it a new `id`.

## Important notes

- The demand scores, learning times and salary ranges are **indicative estimates for India**, not live data. Check current job sites before making career decisions.
- The four-year plans are suggestions. Adjust them to your college syllabus.
- The guide follows a fixed script. It does not use AI.
- Course names and materials belong to their creators. This site only links to them.

## Free resources linked

- [The Odin Project](https://www.theodinproject.com)
- [MIT OpenCourseWare](https://ocw.mit.edu)
- [Harvard CS50](https://cs50.harvard.edu)
- [freeCodeCamp](https://www.freecodecamp.org)
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn)
- [SQLBolt](https://sqlbolt.com)

## Contributing

Suggestions and fixes are welcome. Open an issue or send a pull request, for example to add a course, fix a broken link, or improve a blog post.

## License

No license has been added yet. If you want others to reuse the code, add one such as the MIT License (GitHub can create it for you under **Add file → Create new file → name it LICENSE**).
