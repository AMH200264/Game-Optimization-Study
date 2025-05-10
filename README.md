# By Ameer Hamad
May 10th, 2025

## Introduction

  As of recent, technology has been advancing at an exponential rate: the TVs get thinner, the processors get faster, and everyone's racing for the next breakthrough idea. Among these developments, video games are no different. In the span of roughly 40 years, video games have gone from side-scrolling adventures that could barely handle a few colors on screen, to photorealistic setpieces that look better and better with each release. These facelifts definitely don't come for free however. The phrase "next-generation" seems to become louder and louder with each passing year, and with it other large phrases that the technologically untrained ear would interpret as that of a supercomputer: "teraflops", "multi-core processing", "solid-state disks", and a lot more. Despite all of these advancements, a trend has been noticed by hardware enthusiasts, developers, and gamers alike: it takes a lot of power to run modern games. The argument isn't being made that high fidelity titles should be able to run on the likes of a toaster; the fact that some are *nearly* able to however, raises questions. Are developers cutting corners optimizing their game's performance to save money? Is there an increasing reliance on AI technologies to pick up the slack? Or have these blockbuster titles reached a level of fidelity that truly require some heavy horsepower? Let's take a look at the numbers and find out.
  
## Collecting Performance Data From Players
  
### High Fidelity, High Requests

  What better place to collect data than from the people playing the games? Can You RUN It[^1] is a public forum where users can poll what kind of hardware they have, what kind of titles they can run, and how well they run. I decided to take the most popular games listed in the last 30 days (as of May 1st, 2025) and chart them based on release year and percentage of users who passed the minimum requirements for the title.
  
![game_release_year run_percentage](https://github.com/user-attachments/assets/155be95d-312c-48b9-95ab-c5004d6386e4)
  > Average percentage of users meetings titles' requested minimum hardware requirements between 2009 and 2025

   Overall, we see a 27% decrease in users meeting minimum game hardware requirements between the 16 year span of 2009 and 2025. On average, nearly 80% of users met minimum hardware requirements. There's a considerable drop in 2025 however, with a little over half of users meeting those minimum requirements, and a ≈ -2.47% drop between all years.

  As time goes on, more and more graphics cards (GPUs), processors (CPUs), RAM (random access memory), and other components flood the market, causing a greater variety of hardware setups to exist, which can account for overall fluctuation. What the data here says however, is that regardless of those varied setups, the average user is having more and more trouble meeting minimum hardware requirements for titles as time goes on.

### How The Performance Stacks Up

  Let's take a look at how all of this hardware performs. I've collected data from hardware blogs like Digital Foundry[^2], TechSpot[^3], and Tom's Hardware[^4], detailing the average performance of 100 triple A titles released between 2009 and 2025 on recommended PC level hardware.
  
![year averagefps](https://github.com/user-attachments/assets/09f79671-49d8-432c-96c5-689fb7ea0a88)
  > Average framerate of triple A games at recommended hardware requirements between 2009 and 2025

Despite a very volatile visual presentation, there's actually a slight upturn here with a ≈ +3.64% framerate increase from 2009 to 2025. More recent trends however (2020 to 2025) show a more prevalent drop of ≈ -21.92%, with a drop of ≈ -5.48% between each year. The gaming industry has slowly crept to a framerate of 60 frames per second from a primitive 30 frames per second. The fact that hardware setups are returning inconsistent average frame rates at recommended hardware levels can lead us to believe that the hardware isn't being utilized to it's full potential, especially since the recommended GPUs are less than 2 years old and boast impressive potential, such as Nvidia's 40 series and AMD's 7000 series cards.

## Evolving Hardware

### Climbing Requirements

 As much as we wish legacy hardware could render individual strands of hair and realistic light physics, the truth is it can't. While it's natural for stronger hardware to be present for more demanding titles, many developers throughout the years have used a level of finesse to make these titles run on older hardware; that was before the introduction of frame-generation technologies like Nivida's DLSS and AMD's FSR, technologies that are becoming more and more popular with each occurring hardware generation.<br/>
  <br/>
  **NOTE: many of these titles are console ports from Playstation and Xbox systems, which account for titles having GPU requirements more recent than the title's release.**
  
  ![game_release_year gpu_year_requirement](https://github.com/user-attachments/assets/12816003-0108-4a7a-b452-db74079a2f01)
  > Release year of titles and release year of reccommened GPU

  As we can see from this upward trend, titles generally require a GPU that has released within 5 years of the title, which is fair considering how quickly fidelity has advanced. The minimum GPU release year hovers at about 2012, which means some of these cards are at most 13 years old and still able to run these games. Of course there are GPUs that have released more recently, like Nvidia's 50 series cards (if those were requirements in any capacity we would truly be in trouble). Most data collected stems from more recent GPUs however, which is concerning considering the previously discussed drop in average FPS.

### Additional Hardware Upticks
  
  We've discussed GPUs quite a bit. Despite the heavy lifting they do, they're not the only pieces of hardware that are being put to work. Many titles are requiring users to have more RAM (random access memory) and storage.
  
![ram year](https://github.com/user-attachments/assets/c83ae62e-edd9-440d-9566-f0c9fab26a22)
  > Title release year and recommended amount of RAM (gb)

![storage year](https://github.com/user-attachments/assets/f49ced84-d9c5-4a96-b3e3-573b3608aed0)
  > Average recommended amount for titles per year

Overall, we can see a pretty consistent increase of the recommended RAM requirement throughout the years (despite a few outliers):
+ 2009-2012 titles request 4GB
+ 2013-2016 titles request 8GB
+ 2017-2022 titles request 16GB
+ 2023-2025/currently (as of publication) titles request 32GB

For the longest time, 16GB has been considered the sweet spot for anyone, from the average consumer to the avid gamer. While an increase in RAM requirements is logical given the increasing fidelity of games, the exponential nature of increasing RAM makes the jump from 16GB to the modern day standard of 32GB a considerably large one. Despite this large jump, titles still struggle to maintain consistent frame rates. It's possible that developers could be leveraging this large amount of RAM to pick up the slack and make up for a lack of optimization.

It's not just performance requirements that are spiking; modern games are requiring more and more storage. Once again, this isn't surprising since games have had increasingly higher resolution textures, higher LOD (level of detail) models, and more interactive physics. There are some instances however that suggest developers aren't doing all they can to keep sizes as low as possible. An example many point to is _Call of Duty: Black Ops 6_ which not only comes in at a staggering 130GB storage requirement, but even requires an SSD, a trend that's been gaining speed. Another instance is Square Enix's recent _FINAL FANTASY VII REBIRTH_, which has a shocking size of 150GB. We can see that the lack of optimization has also spread to compressing game sizes.

## A Worthwhile Investment?

### GPU Prices

A large appeal of PC gaming to many is the modularity of the hardware. Unlike home consoles that have to tough it out the entire hardware generation, PC users have the freedom to change out their GPU, processor, RAM, and more. Therefore, players have a better chance of being able to run most titles. There's been a stark uptick in hardware prices that seems to be climbing higher and higher though, making upgrading inaccessible, costly, and an investment that many are now having second thoughts on.

![gpu_price year](https://github.com/user-attachments/assets/5d8b2718-08c6-4dad-9370-6b0a2e6abff6)
> Average GPU price and year of release

In the span of a decade, we see an massive price hike of ≈ +377.75% to the average GPU price for the respective year. The largest jump is between 2012 and 2013 at +119.25%, which can be attributed to multiple factors. For one, Nvidia's 600 and AMD's 7000 series cards were introduced; new generation hardware that ushered in the idea of a high end GPU. In addition, cryptocurrency surged between 2012 and 2013, which relies on GPUs for processing. This surge strained the supply of GPUs. Many other factors like supply issues, scalping and general greed have caused these prices to skyrocket. With title hardware requirements increasing every year (and GPU prices along with them), the race to keep up the latest titles has no doubt put a strain on consumer wallets.

### The Returns

As exciting as getting new hardware is, we've seen that it's become a hefty investment. With so many consumers holding onto their hardware and hoping it holds out in return, how much of it will actually stand the test of time? In a 2022 GPU Benchmarks Compilation[^5], the performance of multiple GPUs is scored on a standardized series of tests. We'll focus on the G3Dmark test, which is a normalized test for GPUs that produces a 'G3D Mark', a numerical value that sums up the GPU's performance. The higher the value, the more valuable the GPU will be in the long run. For reference of this dataset, the GPU with the highest G3D Mark is Nvidia's 2022 RTX 3090 ti with a mark of 29094, and the GPU with the lowest G3Dmark is AMD's 2012 Radeon HD 7340G sitting at a lowly 196. The values graphed below however are the average G3D Mark scores for each year.

![G3dmark releaseyear](https://github.com/user-attachments/assets/9e2552eb-dc82-4a45-bbac-00f622c92b24)
>Average GPU G3DMark score and release year

Finally, some good news for consumers: in the span of a decade, we've seen a ≈ +159.10% increase in G3D Mark scores for GPUs, meaning that they are in fact becoming more capable. There are only 2 consecutive drops in 2020 and 2021; the scores quickly rebound the following year with a +28.80% jump, making up for the previous 2 years' losses.

## Conclusions and Possibilities

After sifting through so much data, there are many possibilities we can draw. We've seen increasingly powerful hardware produce diminishing returns as time moves forward. In addition, game sizes have inflated and requirements have become more and more tight.

As previously mentioned, one possibility for this data is the reliance on AI frame generation techniques, which many newer cards support. By utilizing DLSS or FSR, developers can have their titles produce artificially generated frames and "enhance performance". All while under the hood, these games are truly producing subpar performance. The same goes for resolution upscaling techniques, that while on paper produce palpable results, leave behind visual artifacts that can compromise the visual quality of the title.

Even without the aid of DLSS/FSR, we've seen that GPUs have become the most capable they've ever been. With that being said, developers could be relying on the raw strength of enhanced hardware to run their titles. By relying on this and casting most forms of optimization to the side, hardware is underutilized and lackluster performance is the result. The recent popularity of Epic's Unreal Engine 5 has also left a trail of poor performance in it's wake, with developers often leaving the default settings to do their work (which they unfortunately do not do very well).

To illustrate an example of the absence of optimization, we can look at Bloober Team's recent 2024 remake of Konami's _SILENT HILL 2_. There is an optimization technique where everything within the player's field of view or vicinity is rendered to the player, or at least done so in a way where the level of detail is decreased. Upon inspection, Digital Foundry discovered that practically zero level of detail changes are performed, forcing the game to render everything at the highest default detail despite not even being visible.

![ss_002b780c7a34d50f186456adcc87dc6012741f97 1920x1080](https://github.com/user-attachments/assets/9288de78-4229-4b47-bfb3-ccae390b187e)
> Beyond the fog of Silent Hill, everything is rendered at maximum quality. _(KONAMI 2024)_

It's easy to assume that games have just become too advanced and high fidelity for the hardware to keep up. While yes, running recent titles is no small feat, a lack of optimization has reared its head as a culprit. The damage this does extends to bloated game sizes, increasing minimum and maximum requirements, underutilization of capable hardware, and subpar performance. If developers spend apt time optimizing titles and leverage use of the historical leveled hardware we have, everyone can benefit from an enhanced experience where both consumers and developers can enjoy and create media without compromise.

# References
[^1]: (https://www.systemrequirementslab.com/cyri)
[^2]: (https://www.digitalfoundry.net/)
[^3]: (https://www.techspot.com/)
[^4]: (https://www.tomshardware.com/)
[^5]: (https://www.kaggle.com/datasets/alanjo/gpu-benchmarks)
