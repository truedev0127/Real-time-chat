# Firechat Website

## Initial Setup

To deploy the Firechat website, first make sure you have Firebase Hosting deploy privileges for the
`firechat` Firebase project.

Also, make sure you have [Jekyll](https://jekyllrb.com/docs/installation/) and [Rdiscount](https://github.com/davidfstr/rdiscount) installed:

```
$ gem install jekyll rdiscount
```



```
$ jekyll build
$ firebase deploy
```
