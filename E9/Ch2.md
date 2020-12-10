## Ch.2 Non-ionizing Medical Imaging

## 2.1 Medical Imaging
def: the process of creating a visual representation of the inside of our body for medical use

**invasive & non-invasive**  
def of invasive: instruments have to be introduced into a patient's body

examples:  
- radioactive tracer for thyroid scan
- endoscope in endoscopy

## 2.2 Ultrasound Scans
def: sound wave with frequency > 20 kHz  
(> upper limit of human audible frequency)  

nature: 
- longitudinal
- travelling
- mechanical

properties:  
- reflection
- refraction
- diffraction
- interference

**echolocation**  
def: emitting ultrasound wave and analyse the choes to locate an object

**ultrasound imaging**  
frequency range: 1 - 20 MHz
- 3 - 5 MHz for deeper structures
    - kidney
    - liver
- 7 - 12 MHz for near surface organs  
    - thyroid
    - breast

**piezoelectric effect**  
def: the ability of a material to generate electric charge by compression & stress, and vice versa

production of ultrasound wave:  
1. ac voltage of > 20 kHz is appied across a crystal
2. the crystal will be compressed & stressed
3. ultrasound wave is emitted

detection of ultrasound wave:
1. ultrasound wave hits the crystal
2. the crystal is stretched & compressed by the wave
3. ac voltage is generated

**transducer**  
<img src="https://prod-images-static.radiopaedia.org/images/30966422/373633fc1097636384e9e71c26563d_big_gallery.jpeg">  

image from: https://radiopaedia.org/articles/ultrasound-transducer  

main components:  
- piezoelectric crystal/element
    - emits ultrasound waves
    - detect reflected ultrasound echoes
- damping block/**backing material**
    - damp & absorb the ultrasound wave emitted backward
    - damp the ultrasound wave & the oscillation of the crystal when entering waiting time
- electrodes
    - transmit electrical signals to and from the crystal
- matching layer
    - increase sensation of returning echoes
    - increase transfer efficiecny of ultrasound wave from the crystal to the patient

**pulse emission**  
<img src="https://www.researchgate.net/profile/Adi_Singh/publication/334784649/figure/fig4/AS:786638879866889@1564560732986/Pulsed-emission-of-a-transducer-with-a-waiting-period-of-t-in-between-pulses.ppm">  

image from: https://www.researchgate.net/figure/Pulsed-emission-of-a-transducer-with-a-waiting-period-of-t-in-between-pulses_fig4_334784649  

t<sub>p</sub> = emits pulse duration = 10 μs  
Δt = waiting time = 1 ms = 1000 μs  

waiting time is for detection of ultrasound echoes  

**acoustic impedance**  
def: the opposition of a medium to the ultrasound (higher acoustic impedance easier the ultrasound can travel through)  
unit: Rayl/kg m<sup>-2</sup>s<sup>-1</sup>  
symbol: Z

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\Z=\rho\\\c)  

*ρ*: density of the medium  
*c*: speed of ultrasound in the medium  

**intensity reflection coefficient**  
def: the ratio of the reflected intensity to the incident intensity of the ultrasound wave  
symbol: α  

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\alpha=\frac{I_{r}}{I_{0}}=(\frac{\Delta\\\Z}{\Sigma\\\Z})^2)

*I<sub>r</sub>*: intensity of reflected ultrasound  
*I<sub>0</sub>*: intensity of incident ultrasound  
*ΔZ*: difference between the acoustic impedances of the 2 medium  
*ΣZ*: sum of acoustic impedances of the 2 medium  

**coupling gel**  
air->skin => high ΔZ & low ΣZ => high α => more reflected  
gel->skin => low ΔZ & high ΣZ => low α => less reflected   

principle:  
1\. the gel eliminate the air-skin boundary between the skin and the transducer  
2\. the gel's acoustic impedance is similar to that of typical skin  
3\. low ΔZ & high ΣZ => low α => low I<sub>r</sub>/I<sub>0</sub>  
4\. high ratio of transmitted intensity to incident intensity

**pulse-echo technique**  
def: the technique used to determine the distance the ultrasound wave travelled from its speed in the medium & the time interval between echoes received

<img src="https://wiki.tum.de/download/attachments/225771669/Display_on_display.png?version=1&modificationDate=1554966796430&api=v2">  

iamge from: https://wiki.tum.de/display/zfp/Ultrasonic+Pulse-Echo+Method  

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\s=\frac{ct}{2})  

*s* = thickness of the tissue (distance travelled in the medium)  
*t* = time interval between the 1st echo & the 2nd echo  

**ultrasound scans**  
</empty> | A-scan | B-scan
--- | --- | ---
name | A = amplitude | B = brightness
direction of emission of ultrasound | linear beam | fan beam shape
graph displayed | amplitude of echoes against their depth | 2D positions
intensity of echoes repesented by | amplitude of spike | brightness of a dot
commonly used for | eye's thickness | foetus, tumour & cysts in liver, pancreas, kidneys
image produced | 1D | 2D/3D  
<br>

advantages:  
\- ultrasound is non-ionizing, does not damage body cells  
\- can be used to distinguish soft tissues  
\- real time image to detect movements of a structure  
\- inexpensive & readily available  
disadvantages:  
\- cannot be used to scan structures covered by bones, they get reflected  
\- cannot be used to scan structures filled with gases, they get reflected  
\- brain, spinal cord, liver cannot be imaged by ultrasound
\- energy carried by ultrasound absorbed by tissues and converted to heat  
\- gas bubbles may form due to ultrasound and could damage surrounding tissues if they burst

**attenuation (and penetration)**  
def: the reduction in ultrasound intensity as it travels through a medium  
remark: high frequency => high attenuation & low penetration

factors:  
\- nature of medium  
\- frequency of ultrasound  

effect of frequency:  
1\. ultrasound causes particles vibrate parallel to the wave propagation as they travel in the medium  
2\. higher frequency => absorption of ultrasound higher  
3\. results in high attenuation & low penetration  

**resolution**  
high frequency => high resolution

**comparison between high & low frequency ultrasound**  
</empty> | high frequency | low frequency
--- | --- | ---
attenuation (penetration) | high (low) | low (high)
resolution | high | low