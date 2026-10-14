# Models

A personal playground for data models: I try [datamodels-toolkit](https://github.com/geolonia/datamodels-toolkit) here with my own data first. The models are experimental and may change.

A data model node: JSON Schemas, JSON-LD @contexts and vocabularies at https://dkastl.github.io/models, built with [datamodels-toolkit](https://github.com/geolonia/datamodels-toolkit) (what a node publishes: [docs/node.md](https://github.com/geolonia/datamodels/blob/main/docs/node.md)).

- `node.yaml`: the settings.
- `models/activity/`: the first subject. A model is a folder in it with `schema.json`, `catalog.yaml` and `examples/example.json`, laid out as in [datamodels.jp](https://github.com/geolonia/datamodels/tree/main/models).
- `.github/workflows/publish.yml`: checks pull requests, and publishes main to GitHub Pages.

Licence: [CC0-1.0](LICENSE).

```bash
npx @geolonia/datamodels@0.3.15 check
npx @geolonia/datamodels@0.3.15 build   # into _site/
```
