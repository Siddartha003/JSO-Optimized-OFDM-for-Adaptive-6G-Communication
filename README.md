# JSO-Optimized-OFDM-for-Adaptive-6G-Communication
Jumping Spider Optimization (JSO)-enhanced SISO-OFDM system 
for real-time adaptive BER-SE optimization in non-stationary 6G channels, implemented 
on USRP B210 software-defined radios. The proposed framework dynamically optimizes 
three key parameters: 
1. Cyclic Prefix Length (16–64 samples) 
2. Pilot Spacing (4–16 subcarriers) 
3. Modulation Order (QPSK to 64-QAM) 
Using a bio-inspired JSO algorithm with 50 iterations and 5 search agents, the system 
achieves: 
• 62% lower BER (from 0.023 to 0.0087)   
• 23% higher spectral efficiency (4.82 bps/Hz)  
Experimental results demonstrate robust performance across 3GPP-defined 
channels (EPA/EVA/TDL), validated by: 
• Real-time over-the-air tests at 1.8 GHz center frequency 
• Dynamic parameter adaptation tracking (CP, pilots, modulation) 
• Comprehensive metrics (BER, SE, convergence) 
The implementation bridges theoretical optimization with practical deployment, offering 
a scalable solution for 6G networks in vehicular, UAV, and high-speed rail scenarios. 
Keywords: 6G, OFDM, Jumping Spider Optimization, USRP B210, Adaptive BER-SE, Non Stationary Channels.


