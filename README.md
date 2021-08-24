# PYTHON for 5G MU,Massive MIMO



# Introduction

Challenges for existing Cellular Networks - 

+ Peak downlink data rate in LTE is 150Mbps. 
+ Can support approximately 37 users at HD rate(4Mbps).
+ LTE networks can support around 100-1000 users per cell.
+ Latency in 4G networks is around 30-50ms. Hence they cannot support applications such as autonomous vehicles and drone communication.

Hence, new application requires a massive increase in aggregate data rates. 

5G targets enhanced mobile broadband(eMBB) with ultra high data rates around 10Gbps.
5G is expected to connect 10s of 1000s of devices (1 million devices per square meter) through Enhanced Machine Type Communication(eMTC) 
5G allows ultra-reliable low latency communication(<1ms) (URLLC).



# MASSIVE MIMO Technology

![electronics-10-01667-g001](https://user-images.githubusercontent.com/86367130/130400310-307cac76-67f7-4c65-b5d9-046597f787fd.png)

Massive MIMO Technology base station has a substancially large number of antennas approximately 300-400. It results in huge spatial multipexing gains. By adding more number of antennas leads to increase in the capacity of cellular netwkorks by several times. This also reduces radiated power but at the same time signal processing is simplified. 
Current wireless networks use 300Mhz - 6GHz band which are limited to sub-6Ghz spectrum.

mmWave exploits high frequency mm-Wave band which is in the range of 6-300GHz with large spectral bands.

# Projects

+ # Additive White Gaussian Noise (AWGN) System

> Bit Error Rate analysis of AWGN system

BER deceases exponentially with increase in SNR(dB)
   
   ![image](https://user-images.githubusercontent.com/86367130/130403351-ca724b17-041e-46a1-b9a8-15b6ac0d7bb8.png)
 
+ # Rayleigh Fading Channel

> Bit Error Rate of Rayleigh Fading Channel decreases linearly.
   
   ![Rayleigh_fading](https://user-images.githubusercontent.com/86367130/130616864-a56fca5d-dea8-4cac-a083-e5cc4d88daf4.PNG)

+ # Maximal Ratio Combiner(MRC)
 
> Bit Error of Maximal Ratio Combiner is less than that of Rayleigh Fading Channel

   ![BER for MRC](https://user-images.githubusercontent.com/86367130/130618365-621fd436-8203-4560-8a00-c544f4c72127.PNG)

+ # Multiple Input Multiple Output(MIMO)

> Bit Error Rate
 
   
