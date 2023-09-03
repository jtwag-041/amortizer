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

![runtointeractive_floatingassets (2)](https://github.com/jtwag-041/amortizer/assets/48776287/2c38f2f6-91f6-4d2f-b9fc-b2363c54950d)





5 fixed assets with varying rates to amortize pay on a quarterly basis:

![runtointeractive_fixedassets (2)](https://github.com/jtwag-041/amortizer/assets/48776287/d70a8ce2-dd85-4476-88c1-eeacaf477626)




Benchmark rates**: 

![rates_data_screen (2)](https://github.com/jtwag-041/amortizer/assets/48776287/83483ac3-28fa-4845-be66-22b03b43379e)

**Note: Most benchmark rates used for this demo were estimated and projected based on publicly available LIBOR and Prime curves




**Demo**

![runtointeractive_outputf_floatingassets](https://github.com/jtwag-041/amortizer/assets/48776287/458dc9d7-5a14-489b-a6a7-f51a1ead7d7c)


Note: The more assets there to amortize, the longer it takes. In the demo, 5 assets took ~40 seconds.




**Output**

5 floating assets:

![runtointeractive_output_floating_assets](https://github.com/jtwag-041/amortizer/assets/48776287/6df43b88-6d7a-4151-abfe-5424b10c331c)



Output with 5 fixed assets:

![runtointeractive_output_fixedassets](https://github.com/jtwag-041/amortizer/assets/48776287/249dc11a-eb93-40f7-9fcd-338ce6ba009a)






