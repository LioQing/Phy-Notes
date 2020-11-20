# Ch.1 Lighting

## 1.1 Domestic Electricity

**end-use energy efficiency**  
def: the ratio of the *useful* energy output E<sub>out</sub> to the electrical energy input E<sub>in</sub>

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\eta=\frac{E_{out}}{E_{in}}\times100percent)  
*η*: efficiency  
*E*<sub>out</sub>: energy output  
*E*<sub>in</sub>: energy input  

**energy efficiency labels**  
Energy Efficiency Labelling Scheme (EELS) in HK  
 
<img src="https://www.emsd.gov.hk/energylabel/mobile/en/images/faq_label.jpg" height="400px">  

image from government website: https://www.emsd.gov.hk/energylabel/en/about/background2.html 

**energy saving devices**
- thermostats
	- air conditioners
- timers
	- air conditioners
- motion sensor
	- hand dryers
- standby mode
	- computers

## 1.2 Lighting

**luminous flux**  
def: power of light from a light source with respect to the responsiveness of human eye to different wavelengths (for clearer answer)  
def: *perceived power* of light from a light source (according to wikipedia)

factors:  
1\. power of light energy emitted by the source, i.e. the *power output*  
2\. response of the human eye to the *wavelengths* of light emitted   

unit: lumen (lm)  
symbol: Φ

**luminous efficacy**  
def: how efficiently a lighting device converts *electricity into light*  
this information is shown on energy label (HK)

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\efficacy=\frac{\phi}{P_{in}})  
*Φ*: luminous flux  
*P*<sub>in</sub>: power input

unit: lm W<sup>-1</sup>  

**energy level**  
def: electron in a state corresponds to a specific value of energy  

when an atom is excited, it absorbs energy and the electron jump to higher energy level  
excited atom is unstable  
electron return to lower energy level, emitting EM wave

### Types of lighting  

**incandescent lamp**  
by heating the filament to high temperature (~2000°C) emitting lights  
most energy is *lost from emitting IR*

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Incandescent_light_bulb.svg/800px-Incandescent_light_bulb.svg.png" height="300">  

image from wikipedia: https://en.wikipedia.org/wiki/Incandescent_light_bulb

(below only important parts are mentioned)

2\. **inert gas fill**  
to *reduce the filament's evaporation rate*  
e.g. *argon*, nitrogen, krpton, xenon  
  
3\. **tungsten filament**  
work at very high temperature  
tungsten has a *high melting point*  
*hotter* => more visible light => *higher efficacy*  

**gas discharge lamp**  
make use of an *ionized gas* to work  

**flourescent tube lamp (FTL)**  
filled with argon gas and mercury vapour, and a coating of phosphor on the internal surface  
**compact fluorescent lamp (CFL)**  
has a folded tube for replacing incandescent lamp  
promoted as *energy-saving lamps*  

3 stages of **light emission procedure**:  
1\. a large pd. is applied, an E-field is set up, electrons accelerate from one filament to another  
=> ionizes the argon gas, form a current  

2\. mercury atoms gain energy and excited when bombarded with electrons  
=> return to a lower energy level, emit UV  

3\. phosphor atoms absorb energy from UV  
=> return to a lower energy level, emit visible light (process called *flourescence*)  

components:  
\- **starter**  
=> provide a large voltage to start the gas discharge  

\- **ballast**  
=> control and stabilize the current  

\- filled with low pressure inert gas  
=> increase chance of electrons interacting with the mercury atoms  

\- inner wall coated with phosphor powder  
=> emit light  

**light emitting diodes (LED) lamp**  
make use of semiconductors to work  
consists of p-type and n-type semiconductors  
require DC, convert using *rectifier*

<img src="https://www.electronics-notes.com/images/diode-light-emitting-led-operation-theory.svg" height="350">  

image from electronicnotes: https://www.electronics-notes.com/articles/electronic_components/diode/light-emitting-diode-led-technology-how-does-led-work.php  

**light emission procedure**:  
1\. E-field is applied from p-type to n-type  
=> holes and electrons move towards the p-n junction in opposite direction  

2\. electron fall into a hole, i.e. jumps down to lower energy level  
=> visible light is released  

3\. the difference in the energy levels of the two semiconductor  
=> colour of the light

**comparison table**

</empty> | incandescent lamp | gas discharge lamp | LED lamp 
--- | --- | --- | ---
size | medium | large/medium | small
light source | hot filament | phosphor (flourescent coating) | 2 layers of semiconductors
working temperature | high | medium | low
price | low | medium | high
lifetime | short | medium | long
efficacy | low | medium | high
major advantage | cheap | price-efficacy balance | high efficacy
major disadvantage | low efficacy | mercury content (pollution), electronic waste | heavy-metal content, electronic waste
current | AC/DC | (mostly)AC | DC

**colour spectrum**  
<img src="https://hips.hearstapps.com/pop.h-cdn.co/assets/cm/15/06/54d11defcb70b_-_lightbulb-wars-00-0911-xln.jpg?resize=500:*">  

image from popular mechanics: https://www.popularmechanics.com/technology/gadgets/reviews/g164/incandescent-vs-compact-fluorescent-vs-led-ultimate-light-bulb-test/  

## 1.3 Measuring Illumination

**illuminance**  
def: the *luminous flux* falling on a surface *per unit area* (perpendicularly)  
![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\E_{0}=\frac{\phi}{A})  
*E*<sub>0</sub>: illuminance on suface perpendicular to the incident light  
*A*: area  

**Lambert's cosine law**:  
![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\E=E_{0}cos\theta=\frac{\phi}{A}cos\theta)  
*E*: illuminance  
*θ*: incident angle  

unit: lux (lx)

**point light source**  
a *small* light source giving out light *evenly in all directions*

**inverse-square law**:  
![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\E_{0}=\frac{\phi}{A}=\frac{\phi}{4\pi\\\r^2})  
r: distance from the source

assumptions:
\- the source is small
\- the surface is perpendicular to the incident light  

**oblique incidence**  
Lambert's cosine law + inverse-square law  

![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\E=\frac{\phi}{4\pi\r^2}cos\theta)  
  
when the perpendicular distance *d* from the light source is given  
![formula](https://render.githubusercontent.com/render/math?math=\LARGE\\\E=\frac{\phi}{4\pi\\\r^2}cos\theta=\frac{\phi}{4\pi(\frac{d}{cos\theta})^2}cos\theta=\frac{\phi}{4\pi\\\d^2}cos^3\theta)  
*d*: perpendicular distance from the light source
