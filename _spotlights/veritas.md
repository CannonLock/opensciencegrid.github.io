---
title: VERITAS and OSG explore extreme window into the universe
date: 2017-06-02 12:00:00 -0600
categories: Veritas
card_image: /assets/images/veritas_1.png
---

Understanding the universe has always fascinated mankind. The VERITAS Cherenkov telescope array unravels its secrets by detecting very-high-energy gamma rays from astrophysics sources.

Gamma-ray astronomy studies the most energetic form of electromagnetic radiation, with photon energies in the GeV – TeV range (gigaelectronvolt to teraelectronvolt). The Very Energetic Radiation Imaging Telescope Array System (VERITAS) uses four 12-meter diameter imaging telescopes. The system uses the Imaging Atmospheric Cherenkov Telescope (IACT) technique to observe gamma rays that cause particle showers in Earth’s upper atmosphere.

Inside the system, there are four photo-multiplier, 499-pixel cameras, each 0.15 degree in diameter, which record images of the showers by detecting the Cherenkov light emitted by particles in the air shower. The field of view of each camera is 3.5 degrees.

There are currently three operating IACT arrays: H.E.S.S., MAGIC, and VERITAS. VERITAS is sensitive to very-high-energy (VHE) gamma rays in the energy range between ~80 GeV up to several tens of TeV. It is one of the most sensitive instruments in that energy band.

 
<figure class="figure">
  <img src="{{site.baseurl}}/assets/images/veritas_1.png" alt="Image of VERITAS">
  <figcaption class="figure-caption">The Very Energetic Radiation Imaging Telescope Array System (VERITAS) uses four 12-meter diameter imaging telescopes. The system uses the Imaging Atmospheric Cherenkov Telescope (IACT) technique to observe gamma rays that cause particle showers in Earth’s upper atmosphere. The picture shows the four telescopes at their permanent location at the Fred Lawrence Whipple Observatory (FLWO) observatory one hour south of Tucson, AZ. Courtesy Nepomuk Otte.</figcaption>
</figure>

A. Nepomuk Otte, Ph.D., is an assistant professor in the School of Physics at the Georgia Institute of Technology. He works in the Center for Relativistic Astrophysics and is a collaborator in VERITAS.

“We use the VERITAS telescopes in Arizona to study black holes, the remnants of exploding stars, pulsars, and other objects in the sky,” says Otte. “A high-energy gamma ray has a trillion times more energy than a light particle from the sun. When such a gamma ray hits the atmosphere, it produces millions of electrons and positrons that travel faster than the speed of light through the atmosphere.”

Otte explains that these charged particles emit a bluish flash of light as they zip through the atmosphere. The VERITAS telescopes collect that light and project it onto special cameras to take an image of the particle shower.

“In our analysis software, we compare the recorded images with simulated ones to find out if a shower was produced by an actual gamma ray or a cosmic ray, which would be a background event,” says Otte. “We also have to compare our events with simulated ones to reconstruct the energy and its origin in the sky—everything we need for a full reconstruction. For our analysis, it is crucial that we properly simulate our experiment to make sense of the data.”

Otte relies on the Open Science Pool to run the simulations. “Without simulations, we are blind because the characteristics of each recorded image depend on too many parameters to be described analytically,” says Otte. “We have to repeat every step of the experiment in the computer, from the gamma-ray interaction in the atmosphere up to the point where the digitized photon detector signals are written to disk about 100 million times. That is a very time-consuming process.” Otte then compares each recorded event with simulated ones. “The simulated events that best match the recorded event tell us what the energy of the recorded event was and whether it was a gamma ray or a cosmic ray.”

VERITAS began recording data ten years ago. Over that time span, VERITAS accumulated 10,000 hours of observations on more than 100 objects. Some objects were observed for more than 300 hours. The analysis of these large data sets is sensitive to even small differences between the experiment and the simulations, which was not important when VERITAS started. Two years ago, the VERITAS collaboration reworked the simulation models to account for these small differences by including more details about the experiment itself.

“We had to rewrite large fractions of our simulation code,” says Otte. “The added detail also meant we needed more computing power. In the past, we could do our simulations on a few hundred CPUs. Now, we need a hundred times more power because we want to simulate ten times more showers than before.”

OSG gives the VERITAS collaboration the computing power they need. “Using free cycles that others are not using is almost perfect for us,” says Otte. He and his group started using the OSG in August 2016. Initially, Otte wrote an XSEDE allocation application to use Stampede, and the XSEDE experts recommended OSG as a better fit for the project. “I knew about OSG, having used it for other experiments,” says Otte, “but the shared free cycles in this case was a huge help.”

Otte says the grand challenge in their field is to look at the air showers in the atmosphere; they see very few gamma rays and just a handful of them observed for over 100 hours. At the same time, millions of background events are recorded that are cosmic rays but look very similar to gamma-ray air showers. “So, our challenge is to dig needles out of a huge haystack,” says Otte. “This has been a huge challenge for decades.”

It was possible only after realizing the power of image analysis of air showers in the late 1980s to distinguish between gamma-ray events and background events with very high efficiency. The simulations tell what features to look for in the images to suppress the background events in the analysis.

“Simulations are crucial,” says Otte. “We could not make sense of the data without them. And now with bigger data sets it has become very important to also include aspects of the telescopes that did not matter before. For example, we have now recorded events with energies of several tens of TeV. These events are extremely rare, but we have them in our data. The images of these events are so bright that a lot of the camera pixels saturate. We had not included these saturation effects in our simulations before and thus made large errors in reconstructing the energy of these events.”

After the VERITAS analysis is done, the data are combined with observations in X-ray, radio, and optical and compared with models that try to explain what happens inside the source. One of the important science drivers for VERITAS is to find the origin of cosmic rays, which is a century-old puzzle. “The remnants of supernovae are prime candidates to accelerate cosmic rays,” says Otte. “In some cases, we resolve the expanding shell in gamma rays and can directly see where the cosmic rays come from.”

Otte uses the OSG mostly for the simulations. “We don’t need these massive computing resources like other experiments might,” says Otte. “Running the simulations is a single effort that takes a lot of time and a lot of computing resources. Buying resources for such a short time would not be sustainable. The sharing concept of OSG is perfect for us. We borrow the resources, do production, have the data on disk, and then do our science for the next few years on our local computing clusters at the universities.”

Without the OSG, Otte says they would be stuck with local clusters, and that would hold them back. Another important aspect for the VERITAS collaboration is they have groups across the nation with computing resources, but only the OSG can combine them all into one big virtual computing cluster. That makes them far more productive. “With tens of terabytes of data,” says Otte, “the grid makes things much easier.”

“With the help of the OSG, we are exploring a new and very exciting window into the most extreme objects in our universe. Like black holes and exploding stars, we study the origin of dark matter, which makes up 25 percent of the universe, and we don’t even understand what it is. We explore the evolution of the universe and can even test the fabric of space-time. VERITAS is a very versatile tool and a world-leading instrument.”

“As we pursue our research, we develop new technologies and algorithms. These find use in other areas as well. For example, the photon detector technology we use is also used in apparatus for cancer screening and diagnostics. And our algorithms can apply to and be used for other large data sets.”

<figure class="figure">
  <img src="{{site.baseurl}}/assets/images/veritas_2.png" alt="Picture of Veritas research group">
  <figcaption class="figure-caption">Research group of Nepomuk Otte. Courtesy Nepomuk Otte.</figcaption>
</figure>
