# Realistic baby character previews

The product detail page now uses photographic mini-model previews with a click interaction and a spoken “hee-hee” response where a matching lifestyle preview is available.

Matching previews currently included for:
- Blue Snowflake Dress
- Red Plaid Bow Dress
- Classic Black Suspender Set
- Green Check Waistcoat Set
- Ruby Red Suspender Set

The original garment images and gallery files remain untouched. The Ruby Ruffle Dress and Ruby Button Romper currently show a clearly marked “Model preview in progress” state because a matching, product-accurate baby photograph was not available in the existing assets; no unrelated child/customer photo is substituted.

To finish those two previews, generate a separate lifestyle photograph for each product using its original garment image as the reference, then add the resulting image under `assets/baby-models/` and set that product record's `babyImage` field in `index.html`.
