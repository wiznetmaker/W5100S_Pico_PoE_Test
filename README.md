# W5100S_Pico_PoE_Test

PoE Test board production record - Let's test various modules

I made a board to test PoE with W5100S + Pico board.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/a145307a-50a9-469c-aa4a-11569432c0ae)

PROJECT DESCRIPTION

Story

Hello.I'm making a PoE Test board now.

In general cases, it is recommended to purchase and use PoE (Power over Ethernet) modules as there are many affordable and good-quality options available in the market.

So, I have created a board that allows me to test the PoE module by attaching it to the W5100S.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/98126cec-d822-42fc-bd8c-17f939e08d90)


I only needed to make a few modifications to the W5100S HAT board.
The circuit is configured as shown above.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/e7310b18-e8a8-4ecd-b7d9-b2ef7181176e)

Unlike the circuit, I had to completely reconfigure the PCB.
It was challenging because the RJ-45 connector was different, and the header turned out to be larger than expected.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/f591879c-9105-40b8-903d-ba4c0bb74a11)


The board is designed as shown above! It looks very nice!

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/7f1bfb0f-6954-4ffd-bd34-693de901a16b)

I waited for three days and finally received the PCB!
Now it's time to assemble it!

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/c8810dbd-6c5d-401c-944c-3674650fa518)

I have finished assembling the board. It was challenging because there were many 1005-sized components..

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/601394dd-e781-4298-9287-cc9732c925ad)

I installed the Pico board and tested it, and it worked successfully.
That's great to hear! It's good to confirm that the power is being supplied well.

# Issue

The problem is that the board's appearance is unattractive. After connecting everything, it looks very unusual.

I will raise the Raspberry Pi Pico board up and move the PoE module down.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/3a67793c-e6dd-4c4f-b4ba-28c9bef86bed)

Hmm... This also looks a bit strange
Which one looks better? Both work fine, but the form is strange.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/33063e09-b3ff-4b37-93b8-c45e33c31519)

The power supply operates very well at 5V. Of course, connecting a load and testing it would be necessary to accurately determine if it is a reliable module.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/4449f81b-5bc9-41cb-a139-e0a3e5a019e9)

I can test various modules like this.
These modules are completely different in price and characteristics. Therefore, you can test these modules with this test board to select a good module.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/93cc7ade-05fd-4315-8e75-a2dfd5fd3918)

I can also test it by connecting a simple load. Some modules have significant characteristics depending on the load.

![image](https://github.com/wiznetmaker/W5100S_Pico_PoE_Test/assets/111826791/6363dfa1-c30f-4a20-b511-b6a091f27403)

By connecting the Pico W, you can easily use BLE to Ethernet or WiFi to Ethernet functionality.
Next time I'll post with a better form of module!
