# RAINDROP website

## Contribute

### Prerequisites

1) [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)

2) [Install Jekyll](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller)

### Launch

```
cd /path/to/project

jekyll serve
```

The website is running at [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

### Update

The pages can be updated at the root `/` of the project. Each page is represented by a Markdown file `*.md`. E.g., the "Team" page is represented by the the `/Team.md` file.

The posts are located in the `/_post` directory. Each post is represented by a Markdown file following that format `YYYY-MM-DD-Title.md`.

The images can be updated in the `/images` directory.

The layout can be updated in the `/_layouts` and `/_includes` directories.

The style can be updated in the `/public` directory.

Once the server is started, each modification save (CTRL-S) will result in the update of the website. It is not necessary to restart the server at each single modification.

The code of the website is generated in the `/_site` directory. This is what needs to be deployed afterwards.