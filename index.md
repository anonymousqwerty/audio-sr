We propose an audio enhancement technique that
increases the sampling rate of audio signals such
as speech or music using deep convolutional neural networks. Our model is trained on pairs of
low and high-quality audio examples; at test-time, it predicts missing samples within a low-resolution signal in an interpolation process similar to image super-resolution. Our method is
considerably simpler than previous approaches
and outperforms baselines on standard speech
and music benchmarks at 2×, 4×, and 6× up-scaling ratios. The method has practical applications in telephony, compression, and text-to-speech generation; it also introduces new architectures that could help scale recently proposed
generative models of audio.

## Audio Super-Resolution Samples

Below, you may find samples from our neural network-based audio super-resolution model and several baselines.

We will be adding more samples here as they become available.

### Single Speaker (6x upscaling)

We start with models trained and tested on different utterances from the same speaker. At 6x upscaling, the low-resolution audio becomes very hard to comprehend, but our method can recover a significant fraction of the high frequency, at the cost of introducing a small amount of noise.

### Sample 1

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.1.6.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.1.6.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.1.6.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.1.6.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 2

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.2.6.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.2.6.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.2.6.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.2.6.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 3

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.3.6.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.3.6.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.3.6.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/6/sp1.3.6.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Single Speaker (8x upscaling)

Next, we look at 8x upscaling. Again, the super-resolution algorithm recovers a large fraction of the high frequencies.

### Sample 1

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.1.8.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.1.8.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.1.8.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.1.8.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 2

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.2.8.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.2.8.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.2.8.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.2.8.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 3

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.3.8.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.3.8.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.3.8.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/sp1/8/sp1.3.8.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>


### MultiSpeaker (2x upscaling)

Next, we look at the more interesting setting where we train on one set of speakers, and test on a second set of speakers. At 2x upscaling, the task is not too difficult and our methods reconstructs almost perfectly the original sample.

### Sample 1

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.1.2.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.1.2.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.1.2.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.1.2.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 2

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.2.2.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.2.2.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.2.2.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.2.2.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 3

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.3.2.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.3.2.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.3.2.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.3.2.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 4

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.4.2.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.4.2.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.4.2.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.4.2.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 5

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.5.2.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.5.2.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.5.2.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/2/msp.5.2.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Multispeaker (4x upsampling)

On the more interesting 4x task, our output is slightly noisier, but it also clearly outperforms the baseline.

### Sample 1

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.1.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.1.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.1.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.1.4.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 2

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.2.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.2.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.2.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.2.4.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 3

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.3.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.3.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.3.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.3.4.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 4

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.4.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.4.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.4.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.4.4.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Sample 5

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.5.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.5.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.5.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Cubic interpolation: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/msp/4/msp.5.4.sp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Interesting samples

Finally, we are going to look at a few more samples that provide useful insights into how our method works.

### Sample 1 (4x upscaling)

Our first sample shows that our method can "hallucinate" new sounds when they can no longer be exactly recovered. Sometimes, this works correctly, as in some of the examples above. In other cases, it leads to some interesting failure modes, like the one below.

<div> High resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/extra/extra.1.4.hr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Low resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/extra/extra.1.4.lr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

<div> Super-resolution: <audio controls>
  <source src="https://raw.githubusercontent.com/kuleshov/audio-super-res/master/samples/extra/extra.1.4.pr.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> </div>

### Piano Samples

We are regenerating our Piano samples, and we will add them as soon they become available.
