# Hugo Setup

1. Install Brew: 
2. Install Git:
```
brew install git
```
1. Install Go:
```
brew install go
```
1. Install Hugo:
```
brew install hugo
```

1. May be??: Open the hidden `~/.zshrc` (or `~/.bashrc`) file in a text editor, add the following line, and restart your Terminal app so that Hugo can find the location of its Go dependency:
```
export PATH=$PATH:/usr/local/go/bin
```

1. Add Content (Add a new page to your site)
```
hugo new content content/posts/my-first-post.md
```
1.  Hugo created the file in the `content/posts` directory. Open the file with your editor.

```
+++
title = 'My First Post'
date = 2024-01-14T07:07:07+01:00
draft = true
+++
```




Make a folder for all the hugo sites (optional)
Create a new site at the desired folder: hugo new site <site name>

Just a few more steps...

1. Change the current directory to /Users/rasesh/Documents/Hugo/sielra.
2. Create or install a theme:
   - Create a new theme with the command "hugo new theme <THEMENAME>"
   - Or, install a theme from https://themes.gohugo.io/
3. Edit hugo.toml, setting the "theme" property to the theme name.
4. Create new content with the command "hugo new content <SECTIONNAME>/<FILENAME>.<FORMAT>".
5. Start the embedded web server with the command "hugo server --buildDrafts".

See documentation at https://gohugo.io/.