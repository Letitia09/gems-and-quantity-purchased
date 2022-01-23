# gems-and-quantity-purchased

<p>ARS Gems Store sells different varieties of gems to its customers. <br> Write a Python program to calculate the bill amount to be paid by a customer based on the list of gems and quantity purchased. Any purchase with a total bill amount above Rs.30000 is entitled for 5% discount. If any gem required by the customer is not available in the store, then consider total bill amount to be -1. <br> Assume that quantity required by the customer for any gem will always be greater than 0.<br>  Perform case-sensitive comparison wherever applicable</p>

<pre>
<b>Input                                                                                                                            Output</b>
reqd_gems-['Ivory'],reqd_quantity-[10],price_list-[3498, 1257, 5467],gems_list-['Moonstone', 'Sapphire', 'Quartz']               -1
reqd_gems-['Ivory', 'Quartz'],reqd_quantity-[5, 8],price_list-[3498, 1257, 5467],gems_list-['Moonstone', 'Sapphire', 'Quartz']   -1
reqd_gems-['quartz'],reqd_quantity-[10],price_list-[8723, 2346, 7532],gems_list-['Beryl', 'Garnet', 'Quartz']                    -1
reqd_gems-['Beryl'],reqd_quantity-[2],price_list-[8723, 2346, 7532],gems_list-['Beryl', 'Garnet', 'Quartz']                      17446
</pre>
