# Paris public safety data feed

Public, non-personal JSON describing protest, avoid and curfew areas and
public safety alerts in Paris, compiled from public news and official
channels. Approximate; always verify with official channels.

Files (served via GitHub Pages):
- map.json: {version, updated_at, zones:[{id, label, type: avoid|protest|curfew, polygon:[[lat,lng],...], note, ref_url}]}
- alerts.json: {version, updated_at, alerts:[{id, region, severity, title, body, starts, ends, ref_url}]}

updated_at is UTC ISO 8601. version increments on each change.
