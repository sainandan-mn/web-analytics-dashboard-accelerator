# Design Decisions

## Sessionization
GA4 does not provide sessions directly in BigQuery exports.
Sessions are derived using user identifiers and event timestamps.

## Bounce Rate
Bounce rate is calculated using GA4 engagement criteria rather than
legacy Universal Analytics definitions.

## Performance
Flattened and pre-aggregated tables are used to reduce query complexity
and improve Looker Studio performance.
