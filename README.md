# ez_PianoL
Detect and log piano notes from Synthesia-style Youtube videos automatically

Input : Youtube video link

Output : A text or Midi file showing what notes are played and when

Tech Stack: 

Video download : pytube
Frame extraction :OpenCv
Key dectection : YOLOv5
Note mapping : NumPy
Output formatting : Plain text (for now)
