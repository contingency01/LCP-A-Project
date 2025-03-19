# LCP-A-Project

This project is based on the paper DOI: 10.1103/PhysRevLett.93.178103. 

In this paper written by Kiyono et al. in 2004, it is found that the human heart rate (RR) shows scale invariance, which supports the idea that the human heart rate stays in a critical state. This project aims to confirm these results by repeating a similar methodology that was used in the research.

In this project, we used heart rate data of 10 healthy individuals of various ages and genders. The long-term RR data consist of sequential interbeat intervals, denoted as $b(i)$, where $i$ represents the beat number. To explore the probability density function (PDF) of heart rate increments across varying time scales, the analysis begins by removing non-stationary trends through local detrending.

Then, we build the increments from the detrended data and apply Gaussian and Castaing fit.

Lastly, we create a collapse plot to show the scale invariance of the data.

This process is repeated for each dataset.