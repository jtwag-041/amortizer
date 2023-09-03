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

![runtointeractive_floatingassets](https://github.com/jtwag-041/amortizer/assets/48776287/227a9b08-7e0f-4a35-b52b-7bf067563654)




5 fixed assets with varying rates to amortize pay on a quarterly basis:

![runtointeractive_fixedassets](https://github.com/jtwag-041/amortizer/assets/48776287/c026caf5-7dd4-4810-93c3-3fd082e5af63)


Benchmark rates**: 

![rates_data_screen](https://github.com/jtwag-041/amortizer/assets/48776287/6153a6b3-c0c2-4a27-bc8f-6bcb093182be)

**Note: Most benchmark rates used for this demo were estimated and projected based on publicly available LIBOR and Prime curves




**Demo**

![runtointeractive_outputf_floatingassets](https://github.com/jtwag-041/amortizer/assets/48776287/b5432194-80d9-4514-85fb-451d25390d22)

Note: The more assets there to amortize, the longer it takes. In the demo, 5 assets took ~40 seconds.




**Output**

5 floating assets:

![runtointeractive_output_floating_assets](https://github.com/jtwag-041/amortizer/assets/48776287/6c4cea47-cfd9-4390-a872-cbbe75441a4c)


Output with 5 fixed assets:

![runtointeractive_output_fixedassets](https://github.com/jtwag-041/amortizer/assets/48776287/d0c50221-0c69-47f8-9baa-0c9f997a669f)





