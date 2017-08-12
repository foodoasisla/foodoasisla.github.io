
# foodoasis.la

This is the live website for foodoasis.la.

The files in this repository are generated by Jekyll from the source files in the [site](https://github.com/foodoasisla/site) repository.

## How to update the files

[Installing Ruby and Jekyll](https://jekyllrb.com/docs/installation/) is a good place to start. You’ll also need [Node.js and NPM](https://nodejs.org/en/download/).

1. Clone the [foodoasis.la](https://github.com/foodoasisla/foodoasis.la) respository into a folder called `_site`.

2. Move that `_site` folder into your local [site](https://github.com/foodoasisla/site) repository, replacing the `_site` folder that’s already there, if it exists. (That's right! You can put a repository inside of a repository. It’s like Inception!)

3. Switch to your local [site](https://github.com/foodoasisla/site) repository.

4. Install our project’s dependencies…

```
npm install
```

5. Run Node.js and Jekyll, to build the website files…

```
npm run build
```

6. Switch to your local [foodoasis.la](https://github.com/foodoasisla/foodoasis.la) repository. Commit and push the new files.

Your changes should now be visible at: https://foodoasis.la
