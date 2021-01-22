
# SEND Assessment

## Instructions to find and run entry-point file

The run entry-point file is the index.html which can be found in the root folder.

## Any assumptions made about any part of the assessment

- Laravel Mix Preprocessor build work flow was used to bootstrap webpack to compile my scss
- I used random icons, images and I assumed dimensions since the test was an image with inaccessible elements. 

## Instructions to configure and prepare the source code to build and run properly

### Build for development

Run this comand to compile the scss

```bash
yarn && yarn dev
```

Once that is done, On Mac, right click on the index.html file and select copy path. Paste the url in your browser.
You can also just right click on the index.html file and open with a Live Server.

To enable automatic compile (watch) any time changes are made

```bash
yarn && yarn watch
```

### Build for production

```bash
yarn && yarn prod
```

