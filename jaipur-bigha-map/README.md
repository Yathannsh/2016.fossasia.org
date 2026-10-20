# Jaipur Bigha Price Map

Interactive OpenStreetMap choropleth of **Greater Jaipur** agricultural / peri-urban land prices, quoted as average **₹ lakh per Pucca Bigha** (1 bigha = 3,025 sq yards).

## Open locally

```bash
# from repo root
python3 -m http.server 8765 --directory jaipur-bigha-map
# then visit http://localhost:8765/
```

## What’s on the map

- **25 zones** covering highway corridors (Ajmer, Tonk, Delhi, Agra, Kalwar, Sikar), tehsils (Bagru, Bassi, Chaksu, Chomu, Phagi, Shahpura, Viratnagar…), and urban-fringe pockets (Sirsi/Bindayaka, Mansarovar, Jagatpura).
- Click a coloured polygon or the sidebar list for avg / range / drivers / sources.
- Separate table of **urban plot bigha-equivalents** (crore-scale) so plot rates are not confused with agri bigha rates.

## Caveats

Indicative market asks (mid-2025 → Sep 2026), not a valuation certificate. Registered deeds usually settle below asks. Verify khasra DLC on [e-Panjiyan](https://epanjiyan.rajasthan.gov.in/) and 90A / JDA status before any transaction.
