# Drums-JS

Every press on the assinged-key produces a drum kit sound.

## AddEventListener
Using the addEventListener keyup or keydown events,
This can be achieved knowing the key-code of the keys where the sounds are being attached using the **audio** HTML tag.

```javascript
   <audio data-key="65" src="sounds/clap.wav"></audio>
   .
   .
   .
   .
   <audio data-key="65" src="sounds/clap.wav"></audio>
```

I have attached a video in the background making its position fix, it overall looks better than just keeping a boring 
background-image.

```javascript
  <video autoplay muted loop id="myVideo">
        <source src="drums.mp4">
  </video>
```
  
You can find the video inside the __assets/media__ folder.
