# amortizer
Notional amortizer 1.0


Created to amortize loan-level or representative lines of assets with the given inputs* (in that order):
- Description
- Original principal balance
- Current Principal balance
- Asset amortization type
- Weighted average fixed rate (if asset amortization type = 'Fixed')
- Original term
- Remaining term
- Floating rate curve (if asset amortization type = 'Floating')
- Margin
- Periodic cap/floor
- Lifetime cap
- Lifetime floor
- Rate rest frequency


*Note: this demo does not take into account the following inputs used to generate actual amortization:



- Seasoning
- Servicer advances
- Default rates
- Prepayments
- Losses
- Recoveries
- Interest only periods




**Input sheets**

(Click on the GIFS to enlarge and open in new tab)

5 floating assets to amortize:

https://github.com/jtwag-041/amortizer/blob/main/runtointeractive_floatingassets%20(2).gif




5 fixed assets with varying rates to amortize pay on a quarterly basis:

https://github.com/jtwag-041/amortizer/blob/main/runtointeractive_fixedassets%20(2).gif

![rates_data_screen (2)](https://github.com/jtwag-041/amortizer/assets/48776287/83483ac3-28fa-4845-be66-22b03b43379e)

Benchmark rates**: 

https://github.com/jtwag-041/amortizer/blob/main/rates_data_screen%20(2).PNG

**Note: Most benchmark rates used for this demo were estimated and projected based on publicly available LIBOR and Prime curves




**Demo**

https://github.com/jtwag-041/amortizer/blob/main/runtointeractive_outputf_floatingassets.gif

Note: The more assets there to amortize, the longer it takes. In the demo, 5 assets took ~40 seconds.




**Output**

5 floating assets:

https://github.com/jtwag-041/amortizer/blob/main/runtointeractive_output_floating_assets.gif


Output with 5 fixed assets:

https://github.com/jtwag-041/amortizer/blob/main/runtointeractive_output_fixedassets.gif





