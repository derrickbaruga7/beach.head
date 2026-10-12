# Beachhead market-sizing exploration

A saved Python notebook report exploring revenue-based scenarios for energy and aviation markets. The repository currently contains the rendered report, [index.html](index.html).

## View locally

```bash
git clone https://github.com/derrickbaruga7/beach.head.git
cd beach.head
python3 -m http.server 8000
```

Open <http://localhost:8000>. This serves the saved HTML; it does not rerun Python. Some notebook rendering assets load from external CDNs.

## What the report calculates

- A combined revenue baseline for six named companies.
- Low and high scenarios using assumed percentages for energy and aviation.
- Conservative and aggressive text-alert scenarios derived from those assumptions.

Amounts are expressed in billions of USD. The figures and percentages are historical inputs preserved in the report. The report labels the revenue sum as TAM, but company revenue is only a proxy here: it does not establish the market for a particular product. The inputs have no source dates or citations in this repository, so these scenarios should not be presented as a verified market estimate.

## Reproducibility

The original `.ipynb` file and a dependency manifest are not included. The HTML displays the calculation code and saved results. A future update should add the source notebook, dated source references, and an explanation of the assumed percentages.
