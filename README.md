# How To Guide Junior Engineers In The Age Of AI

This is the slide deck, made using [Slidev](https://sli.dev/), for my presentation.

Links to studies mentioned in the slides:

* https://arxiv.org/abs/2309.13060
* https://arxiv.org/abs/2603.24197
* https://arxiv.org/abs/2410.03017

## Present offline

This repository has been created with the possibility to run offline. To do so, first execute the following commands
while you have internet:

1. `npm install`
2. `npm run build`

You should now have a `dist` directory with the files for the presentation. Run this command when having no internet:

```
python -m http.server --directory dist
```

The presentation is now available at http://localhost:8000.
