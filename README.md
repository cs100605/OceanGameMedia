<h1>April Week 1</h1>

<p>I'm Still not completely happy with the changes here yet on the water and caustics, but the performance is so many leagues better than the typical HDRP water, it could be possible to have the HDRP water as an option in the settings if the user desired.</p>
<img src="OceanGame 4_6_2024 4_55_19 PM.png" width="512">
<img src="OceanGame 4_6_2024 4_55_31 PM.png" width="512">

<br/> 

<p>Kelp is now offset by the world position for the wave function, added a color modifier, and fixed a weird problem with ambient occlusion on the kelp.</p>
<img src="OceanGame 4_4_2024 1_55_26 PM.png" width="512">

<br/> 

<p>Testing the kelp shader works for now, but it will need to offset the wave function by world position to make them move differently from each other.</p>
<img src="OceanGame 4_3_2024 10_47_20 PM.png" width="512">
<img src="OceanGame 4_3_2024 10_47_28 PM.png" width="512">

<br/> 

<p>Adding a player controller to the game, is very barebones at this point.</p>
<img src="OceanGame - OutdoorsScene - Windows, Mac, Linux - Unity 2022.3.20f1 _DX11_ 4_3_2024 4_41_57 PM.png" width="512">

<br/> 

<p>Testing a different foliage method, this time using an opaque rendering method, preventing overdraw on the GPU.</p>
<img src="OceanGame_4_3_2024_12_28_28_AM.png" width="512">

<br/> 

<p>Testing foliage with VFX graph, this method of drawing the alpha resulted in a ton of overdraw, increasing GPU times. Foam and ripples are added to enhance the ocean surface's look from below.</p>
<img src="OceanGame_4_2_2024_11_11_27_PM.png" width="512">

<br/>

<p>Also testing bubbles and terrain textures.</p>
<img src="OceanGame_4_1_2024_11_53_17_PM.png" width="512">

<br/>

<p>Testing bubbles, terrain textures, and post-processing effects.</p>
<img src="OceanGame_4_1_2024_11_52_02_PM.png" width="512">

<br/>

<p>Testing HDRP and the art style that is planned, and faking volumetric lighting with VFX graph</p>
<img src="OceanGame_4_1_2024_12_24_37_AM.png" width="512">

<br/>

<h1>March Week 4</h1>
<p>URP test, found to be difficult to add caustics to surfaces receiving main light, so URP is cut.</p>
<img src="image1.png" width="512">

<br/>

<p>HDRP test with volumetric lighting, overall underperformant so volumetrics were cut.</p>
<img src="image.png" width="512">
