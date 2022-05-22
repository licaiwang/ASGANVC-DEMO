### Abstract
One-shot voice conversion has been widely studied in recent years, and a bunch of VC  systems uses feature-disentangle-based learning techniques to separate the speaker’s voice timbre and linguistic content information. These VC systems convert the source speaker's voice style to target by changing the style information while the content information is preserved.  To prevent the speaker style information from blundering the content embeddings, previous works quantize or reduce the dimension of the content embedding as the information bottleneck. However, an imperfect disentanglement will harm the quality and similarity of the converted voice. In this paper, we propose a new style transfer method that involves a generative adversarial network. We further show that our method can obtain the best performance with other VC systems in a faired-third party speaker verification systems as our objective evaluations in speaker similarity.

### DEMO ( Seen to Seen )

| **Source** | **Target** | **Conversion**|
|       :--- |       :--- |          :--- |
| P280<br><audio src="all/all/seen/p280_p306_0/source.wav" controls preload></audio>| P306<br><audio src="all/all/seen/p280_p306_0/target.wav" controls preload></audio> |<audio src="all/all/seen/p280_p306_0/conversion.wav" controls preload><br></audio><audio src="all/all/seen/p280_p306_0/adain/converted.wav" controls preload></audio><br><audio src="all/all/seen/p280_p306_0/autovc/source.wav" controls preload></audio><br><audio src="all/all/seen/p280_p306_0/autovc/source.wav" controls preload></audio>|
