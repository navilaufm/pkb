# Remote Sensing

**Summary**: Notes on satellite/aerial imagery, geospatial foundation models, and Earth observation data pipelines.
**Last updated**: 2026-08-27

---

- See [[Agentic_Coding]] for a note on GeoLibre, a browser-based GIS tool with an AI Assistant that builds geoprocessing workflows.
- See [[Climate_Change]] for a note on the GPM satellite precipitation mission.
- See [[Python]] for a note on a full Python course covering rioxarray for raster data.
- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Article comparing different earth embeddings. Examines the fragmentation across geospatial foundation model [[Embeddings]] products — incompatible file formats, coordinate systems, and storage strategies force downstream users to write custom integration code. Argues for standardizing on formats like GeoParquet and COG, including rich metadata, quantizing embeddings to cut storage costs, and shipping shared benchmarks instead of private leaderboards. keywords: earth embeddings, geospatial foundation models, GeoParquet, COG, [[Data]] standardization, interoperability
