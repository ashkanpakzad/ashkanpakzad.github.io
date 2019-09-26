## Portfolio
UCL Medical Imaging PhD student, research focusing on implementing deeplearning to analyse X-ray CT images of the lungs.
Interests include Heritage Science imaging, 3D visualisations, Raspberry Pi, Arduino and making.
Will take any excuse to get on a boat!

---

## Education:
* MRes Medical Imaging 2019, University College London
* MSci Medical Physics 2017, University College London

---
## Projects:

### Airway tapering rate analysis based on chest X-ray CT
<img src="images/taper_rate_pipeline.png?raw=true"/>
<br>
The goal of this project is to come up with a more objective method to measure the severity of structural lung diseases such as cystic fibrosis. In these diseases, the airways dilate and worsen with disease progression (bronchiectasis). Currently, the standard for measuring lung diseases that affect the airway structure are by breath function tests which are insensitive. This means that large cohorts of patients are necessary to measure the effects of new drugs. This in turn drives up the price of new drugs. In August 2019 NHS Scotland couldn’t afford new Cystic Fibrosis drugs that came with a high price tag. It is therefore necessary to establish a more precise measure to reduce drug development costs.
<br>
An automated pipeline based on Quan et. al. 2018* to measure the tapering rate of all airways given an airway segmentation and CT has been produced. The pipeline considers the cross-sectional area at successive intervals from the carina to peripheral end along the airway, identifying false measurements due to bifurcations. An exponential curve is then fit to the remaining area measurements, computing a tapering rate. Measuring not just the inner airway taper rate but also the airway wall taper rate. As the airway lumen is often plugged in Cystic Fibrosis, the measurement of an inner taper rate is not feasible. This gives us a direct objective measure of the geometry of the airway and could help to precisely ascertain disease severity in structural airway diseases.
<br>
&ast; *K. Quan et al., “Tapering analysis of airways with bronchiectasis,” Proc. SPIE 10574, 105742G (2018)*


### Improving X-ray CT images of the Antikythera Mechanism
<img src="images/akm_sino.png?raw=true"/>
The Antikythera Mechanism is best described as a 2000 year old ancient greek astronomical computer. Having laid on the sea for the majority of this time its bronze interior has corroded and calcified making it incredibly fragile. X-ray CT was utilised as a non-destructive tool to analyse it, unfortunately it became apparent that the most promising scan of the main fragment was missing raw projections.
<br>
In this project, those missing projections were identified by analysis of the raw data. The X-ray CT reconstruction was recomputed with irregular angular intervals resulting in the originally intended quality.
<br>
* [PAPER](https://doi.org/10.1371/journal.pone.0207430): Improved X-ray computed tomography reconstruction of the largest fragment of the Antikythera Mechanism, an ancient Greek astronomical calculator *Pakzad A, Iacoviello F, Ramsey A, Speller R, Griffiths J, Freeth T, Gibson A (2018) PLOS ONE*
* [3D MODEL](https://sketchfab.com/3d-models/antikythera-mechanism-main-fragment-ct-model-d7f48c8999c5406db1a9edba8a350a47) Sketchfab model based on the improved CT images
* [X-RAY CT DATA](https://doi.org/10.7910/DVN/UCXZWU)


---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
