# FAQ

- Q: I am unable to select one of my data queries, even though it shows up in the query selection dropdown. What's happening?
    - See the note on: [Adding Data](/#adding-data).

- Q: Can I upload an image as a background? Will this be added as a feature?
    - I would love to add this feature (and have in fact implemented it and then removed it), however Grafana does not currently have a good way to manage user image uploading through plugins, and during my original plugin review this feature was removed at their request. They said they are looking into adding a better way to manage this, so it's up to Grafana as to when this will be a possibility.

- Q: Plugin is throwing `toReturn.source is undefined`?
    - Just reload or force reload the page. I have yet to properly track down this bug, but rest assured it seems to only occur directly after saving and applying your changes and can be easily fixed.

Other problems and you're somehow on this page before Github? [Leave a new issue!](https://github.com/knightss27/grafana-network-weathermap/issues)