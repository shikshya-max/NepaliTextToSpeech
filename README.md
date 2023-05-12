# NepaliTextToSpeech
![alignment_matrix](https://github.com/shikshya-max/NepaliTextToSpeech/assets/51810639/aeacfa23-b62d-464d-af49-3027e9764869)
The given graph of encoder timestep versus decoder timestep is known as the "alignment matrix" or "attention matrix". The alignment matrix represents the alignment between the input text and the generated speech waveform. Each element in the matrix represents the attention weight assigned by the decoder to the corresponding input text feature when generating the output speech waveform at the current timestep.The alignment matrix is typically visualized as a heatmap, with darker colors indicating higher attention weights and lighter colors indicating lower attention weights. By examining the alignment matrix, you can gain insights into how the TTS model is using the input text to generate the output speech waveform, and how the attention mechanism is aligning the two sequences.

![comparision of gen speech and ground speech](https://github.com/shikshya-max/NepaliTextToSpeech/assets/51810639/fa095e7f-a5f9-40d1-b758-d20d4e078d19)

The given figure is a comparision of ground truth speech waveform and a generated speech waveform, the x-axis represents the same time scale for both waveforms, indicating when the speech was spoken. The y-axis represents the amplitude of the speech waveform at each point in time. Comparing the ground truth and generated speech waveforms, we can see how closely it matches the original speech in terms of timing, intonation, and loudness.

Reference colab file:
https://colab.research.google.com/drive/1N_B_38MMRk1BUqwI_C829TyGpNmppUqK?usp=sharing&authuser=2#scrollTo=DviNKw7rzkyK
