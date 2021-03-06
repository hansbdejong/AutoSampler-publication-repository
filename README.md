# AutoSampler-publication-repository
Code for the publication "Code from the Publication: Mucciarone, David A., Hans B. DeJong, Robert B. Dunbar, Yui Takeshita, Rebecca Albright, and Keaton Mertz. "Autonomous submersible multiport water sampler." HardwareX 9 (2021): e00197.(https://www.sciencedirect.com/science/article/pii/S2468067221000262)

The code was written by H. DeJong and D. Mucciarone. There are 4 Arduino programs that are needed to run the AutoSampler.

1. Program "time_set_manually" is used to set the correct time on the real-time clock. 

2. Program "current_time" is used after the "time_set_manually" to verify the real-time clock has the correct time. It can also be used after the deployment to check for any clock drift. The time and date will display in the Arduino serial reader.

3. Program "AutoSampler_Continuous_RTC" is the main program for the AutoSampler to operate in continuous mode. The real-time clock must have the correct time and date before using this program. There are comments in the program on how to enter the time and date and this information is in the AutoSampler user manual.

4. Program "AutoSampler_Discrete_RTC" is the main program for the AutoSampler to operate in discrete mode. The real-time clock must have the correct time and date before using this program. There are comments in the program on how to enter the time and date and this information is in the AutoSampler user manual.
