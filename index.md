# Build a Website with GitHub

## 1. Create a public repository

A repository, or repo, is your project folder on GitHub.

1. Open [GitHub](https://github.com/new) to create a new repository.
2. Choose your own account as the owner.
3. Name the repository.
4. Select **Public** and turn on **Add README**.
5. Click **Create repository**.

Public means others can view the project files. Use content you want to share publicly. [GitHub guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)

## 2. Edit the README

**README.md** explains the project to people viewing your repository.

Click **Commit changes** to save. A commit records a version of your files.

## 3. Add the homepage

**index.html** is the homepage visitors will see in this exercise.

1. In the repository, choose **Add file > Create new file**.
2. Name it exactly **index.html**.
3. Paste the code below. Change Tyler to your name.
4. Click **Commit changes**.

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Website</title>
</head>
<body>
  <h1>Hello World!</h1>
  <p>Welcome to this website.</p>
</body>
</html>
```

Your repository now contains two files:

```text
  README.md
  index.html
```

## 4. Publish with GitHub Pages

Making the repository public lets others see its files. GitHub Pages publishes the website.

1. Open **Settings > Pages** in your repository.
2. Under Source, choose **Deploy from a branch**.
3. Select your default branch, usually **main**, and **/ (root)**.
4. Click **Save**.

Your website address will normally be:

```text
https://YOUR-USERNAME.github.io/REPO-NAME/
```

## 5. Using Themes

Using a theme allows you to style your website wiithout doing the work yourself.

1. Create a new file named **_config.yml**
2. Add the following lines:
```yml
remote_theme: THEME-NAME
plugins:
- jekyll-remote-theme
```
3. Commit
4. Add the following above the current content of your **index.html**:
```html
---
layout: default
---
```
5. Commit

After this is completed, your website should be restyled with the theme you selected. 
