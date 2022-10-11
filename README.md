# 1C-Bitrix backup for autos' booking
Common employees have an access to autos' category 1 (ex. KIA RIO).<br>
Deputy directors have an access to autos' categories 1 and 2 (category 2 ex. KIA STORTAGE).<br>
Director has an access to all autos' categories (category 3 ex. KIA TAHOE).

- The booking realized by using special created component (OOP). 
- Information about autos stored in infoblocks.
- Information about autos' drivers stored in High-Load blocks.

Driver binds to auto. If you bind driver to auto in infoblock element information will display in driver entry in High-Load blocks. And vice versa (realized by EventHandler).<br>
Also there is the "booking" infoblock which passes an info about busy autos for a certain time, and the component displays free autos.

# Acounts
If you'll setup this backup, you need accounts:

admin <br>
x12345

zam <br>
x12345

employee <br>
qwerty123
