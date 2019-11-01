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

## media-queries

I have also made the Drums to be responsive so there must not be any interruption for the player the code for the media-queries at present the functionality is not working on the mobile-view still working on it.
goes as below:

```
@media all and (max-width:768px) {
   html {
     font-size: 8px;
   }
   .section {
     background: rgba(175, 190, 187, 0.712);
     display: grid;
     grid-template-columns: repeat(3,1fr);
   }
   .kbd {
     font-size: 2rem;
   }
   .keys {
     display: flex;
     flex: 1;
     min-height: 75vh;
     align-items: center;
     justify-content: center;
   }
}
```
### Responsive Drumkit

![Responsive DrumKit](https://github.com/bhavishya2107/drums-JS/blob/master/assets/media/drums.gif?raw=true)

Look at the live drumkit here **[Drum-Kit](https://bhavishya2107.github.io/drums-JS/)**

__Follow me here__ [Bhavishya@Github](https://github.com/bhavishya2107)
