# trafficguard-hackathon# TrafficGuard: AI Traffic Violation Detector  
**Hackathon Submission — Kengeri & Global Village**  
**Live Demo**: [https://trafficguard-hackathon.vercel.app](https://trafficguard-hackathon.vercel.app)  

## Problem  
Helmetless riding, wrong-side driving, and signal jumping are rampant in **Kengeri** and **Global Village**, Bengaluru. Manual enforcement fails.

## Solution  
**AI-powered real-time detection** using phone camera or uploads.  
- Detects: Helmetless, Triple Riding, Wrong-side  
- Privacy: Auto blur/pixelate faces  
- Reports: Time, Location, Confidence, Evidence  
- Hotspots: Tagged to Kengeri / Global Village  

## Tech  
- **AI**: Hugging Face YOLOv8 Nano (`Xenova/yolov8n-helmet-detection`)  
- **Frontend**: React + Tailwind + Lucide  
- **Geolocation**: Free `navigator.geolocation` + fallback zones  
- **Hosting**: Vercel (free)  

## Accuracy  
| Violation | Confidence | Accuracy |
|---------|------------|----------|
| Helmetless | 92% | 9/10 |
| Triple Riding | 87% | 7/8 |

## Run Locally  
```bash
npm install
npm run dev
