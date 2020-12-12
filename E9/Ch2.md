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

## 2.3 Endoscopy

**total internal reflection**  
def: all the light incident on the boundary is reflected

conditions:  
\- light ray from optically denser to less dense medium  
\- angle of incidence > critical angle  

**critical angle**  
def: the minimum angle of incidence for TIR to occur
symbol: C  

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\sinC=\frac{n_{2}}{n_{1}})  

*n<sub>x</sub>*: reflective index of medium X  
remark: *n<sub>2</sub>* < *n<sub>1</sub>*  

**optical fibre**  
structure: glass core surrounded by cladding of slightly lower reflective index  

usage of cladding:  
\- protect the core  
\- prevent dust causing refraction instead  

<img src="https://i.stack.imgur.com/oO5Ai.jpg">  

iamge from: https://math.stackexchange.com/questions/2734479/maximum-incidence-angle-in-optic-fiber  

max entrance angle θ<sub>a</sub> is given by:  
1\. sin θ<sub>c</sub>=n<sub>c</sub>/n<sub>f</sub>  
2\. θ<sub>t</sub> = 90°- θ<sub>c</sub>  
3\. n<sub>i</sub> sin θ<sub>a</sub> = n<sub>f</sub> sin θ<sub>t</sub>  

**endoscope**  

<img src="https://i.pinimg.com/originals/7d/41/9f/7d419f056373f7359f11f82a46f9a54e.gif">  

iamge from: https://www.pinterest.com/pin/56224695325377162/  

<img src="https://www.max-more.com/wp-content/uploads/2020/02/detail-5.png">  

image from: https://www.max-more.com/ 

types:  
\- rigid  
\- flexible  

tip of endoscope:  
\- one channel for passing down tools such as forceps for cutting tissues  
\- one channel (coherent) for transmit image  
\- one channel (incoherent) for illumination  
\- one channel for passing down air or water  

usage:  
\- diagnosis of hollow organs such as stomach and colon  
\- keyhole surgery, only few cuts are made in the body  

advantages:  
\- allows doctor to inspect inner surface of body through natural openings  
\- no ionizing radiation  
\- keyhole surgery can speed up recovery time  
\- small tissue samples can be taken out  

disadvantages:  
\- require anaesthesia  
\- may require fasting  
\- field of view is relative narrow  
\- can only be used for viewing inner surface of organ with cavity  
\- minimal invasive  
\- may cause internal bleeding or allergic reaction  

**coherent & incoherent fibre bundles**  
coherent fibre bundle: the relative positions of fibres in the bundle are the same between the 2 ends  

**resolution**  
factors:  
\- fineness of each fibre  
\- number of fibre in the bundle