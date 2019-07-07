# Analog-design-of-4-bit-current-steering-DACs
This project shows the design & comparison of two 4-bit current steering DACs, based on Binary and Segmented architectures at VDD=1.8V supply, using high-swing cascode current mirror structures for the current source arrays.

## High-Swing Cascode Bias Circuit (PMOS)
![HighSwingCurrentSource](https://user-images.githubusercontent.com/27668656/60772614-1050df80-a0ae-11e9-91fa-5e259bb42280.png)

## 1) Binary DAC:
![BinaryDAC](https://user-images.githubusercontent.com/27668656/60772684-be5c8980-a0ae-11e9-84fb-bd65ed3ac313.png)

## 2) Segmented DAC:
![SegmentedDAC](https://user-images.githubusercontent.com/27668656/60772761-c10bae80-a0af-11e9-8a31-f3f725c36d23.png)

## Testbench for Monte Carlo Simulations:
![7_MonteCarlo_DNL_w](https://user-images.githubusercontent.com/27668656/60772817-835b5580-a0b0-11e9-9a25-d871120d1554.png)

## Monte Carlo Results:
![delta](https://user-images.githubusercontent.com/27668656/60772851-14323100-a0b1-11e9-8f43-558d017ed73f.png) <br/>
The standard deviation of the segmented DAC is smaller than that of the Binary DAC, giving better DNL performance. <br/>
==> Details on how to perform Monte Carlo Simulations: <br/>
https://github.com/muhammadaldacher/Analog-design-of-4-bit-current-steering-DACs/tree/master/Monte%20Carlo <br/>

*****************
### References:
My project on google drive:<br/>
https://drive.google.com/drive/folders/1W9ip4MpMZNf3IQsoFQkhgg6QaUya4Yp4 <br/>
EE288 Lecture Notes:<br/>
https://drive.google.com/drive/folders/12Qqfw_TX1i7dvVVYXksaSdHV4gth1OD5 <br/>
Videos on how to create VerilogA blocks for ADCs:
https://drive.google.com/drive/folders/1GAobRzzFTkD6ywqSdDJUsO5g2C06hh_i <br/>
https://www.youtube.com/channel/UC7jwESeWKLcRbtxHwFS3A7Q/videos 
