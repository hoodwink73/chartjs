# Chart.js 

Had to make some very hacky changes to roll out some desired chart in Airwoot Analytics.

**These changes will break the desired behaviour Chart.js if the repository is updated.**

Changes are done in a very non-extensible manner.

-  Add an auxiliary dataset so that tooltip can augment some data from it
-  Disable default multi-tooltips for line charts
-  While calculating the proximity of cursor and data point in a Line chart, do consider x-axis also
-  Hide some y-axis grid lines
-  Hide some labels on x-axis

**Note: - Changes are only made to the Chart.js file in the root of the repo. Modular files inside `src` folder are untouched.**


*Simple HTML5 Charts using the canvas element* [chartjs.org](http://www.chartjs.org)

## Documentation

You can find documentation at [chartjs.org/docs](http://www.chartjs.org/docs/). The markdown files that build the site are available under `/docs`. Please note - in some of the json examples of configuration you might notice some liquid tags - this is just for the generating the site html, please disregard.

## Bugs, issues and contributing

Before submitting an issue or a pull request to the project, please take a moment to look over the [contributing guidelines](https://github.com/nnnick/Chart.js/blob/master/CONTRIBUTING.md) first.

For support using Chart.js, please post questions with the [`chartjs` tag on Stack Overflow](http://stackoverflow.com/questions/tagged/chartjs).

## License

Chart.js is available under the [MIT license](http://opensource.org/licenses/MIT).
