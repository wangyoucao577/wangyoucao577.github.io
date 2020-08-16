# wangyoucao577.github.io 

## Tips for Jekyll & Github Pages

### Valuable to read before setting up 
These docs may take a few hours to read, but it's valuable. After go through them, you'll get a very good understanding of [Github Pages](https://pages.github.com/) and [jekyll](https://jekyllrb.com/), as well as what you can customize.    

- [Getting started with GitHub Pages](https://docs.github.com/en/github/working-with-github-pages/getting-started-with-github-pages)
- [jekyll](https://jekyllrb.com/)
- [jekyll docs](https://jekyllrb.com/docs/)

### Theme 
I use the default theme [jekyll/minima](https://github.com/jekyll/minima) with a little customization:
- use customized [footer.html](./_includes/footer.html) to removed some social contents, as well as multi-line description support;    
- use customized [home.html](./_layouts/home.html) and [home-zh.html](./_layouts/home-zh.html) to support independent English and 中文 pages;    

Read more in [jekyll resources](https://jekyllrb.com/resources/) if you'd like to choose differernt themes or customize more on the theme you selected.    

Moreover, [Liquid](https://shopify.github.io/liquid/) can be your handbook when you do some customzation.     

### Daily commands 

```bash
# update dependencies if necessary
$ bundle update

# find hided contents of your theme
$ bundle info --path minima

# launch on local for debugging
$ bundle exec jekyll serve --host 0.0.0.0
```