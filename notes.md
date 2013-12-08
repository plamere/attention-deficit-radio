# notes

 - Seed with artist
 - Generate dynamic playlist based on artist with target hotttnesss of 1
 - steer to the tempo of every Nth song to allow the tempo to gradually wander
 
 
 User Inputs:
 
 - Seed artist
 - Song time (default 30secs)
 - Cross fade time (default 5 secs)
 
 
 Display
 
  - Cur track name
  - Cur track time / remaining time
  - Beat meter
  - skip button - starts segue immediately
  - mix percentage
  - current tempo, natural tempo
  - info
      - loading track, loading analysis, finding best song bits,
      - transitioning
      
  - optional - news/blog headlines? Artist Images? Blog, bio (via newsticker) - for A.D.D. we need to keep the info flowing
      
   
 The Cross Fade
 
  - drive to the tempo of the song with the highest tempo song 
  - select loudest 'song time' - transition time) for the song
 
 
 Opinions
 
 - no preview of next track
 - skip button starts segue immediately - skip not enabled until next song is fully loaded
 - transition can't start until next track and analysis is fully loaded, so we may have to play for longer than the transition
 - zippy song transition (slider, spinner or something)