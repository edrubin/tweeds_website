# TWEEDS Website

I.e., the website for TWEEDS conference.

I currently create the website using R's `blogdown` package and host the website on [netlify](https://www.netlify.com).

To serve the site locally:
```{r}
blogdown::serve_site()
```

To deploy a test version of the site:
```{sh}
netlify deploy
```

To deploy the official site:
```{sh}
netlify deploy --prod
```
