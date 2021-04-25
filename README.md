# tinyAlarm
movement-triggered alarm that sends text-messages alerts through GSM

# Hardware
* mainboard is Raspberry Pi Zero W v1.1 because it's cheap, powerfull, and i happen to have one available in a drawer.
* movement sensor is PIR HC-SR501 : https://www.amazon.fr/gp/product/B01C6O9C38/ref=ppx_yo_dt_b_asin_title_o01_s00 (waaaay cheaper on aliexpress but shipping period would have been discouraging)
* GSM module is SIM800C https://fr.aliexpress.com/item/4000174785868.html?spm=a2g0s.9042311.0.0.79ad6c37dUyJ0R (SIM800L have been purchased too for benchmark purpose, as it's cheaper). but the SIM800C module comes packaged, we should'nt have to bother with power regulation, and MIC / headphones io are regular 3.5")

# What it should do
* main purpose is, when enabled, to send text message through GSM to a list of recipients
# What is should'nt do
