# Real-World Flight Dataset for Drone-Satellite Visual Geo-Localization

---

### Flight Scenes
- **Total 4 Scenes**:
  - `01`: Afternoon/Shadowy/150m  
  - `02`: Afternoon/Shadowy/250m  
  - `03`: Noon/Bright/150m  
  - `04`: Evening/Foggy/150m  

---

## 1. Introduction
Experimental platform: **DJI Matrice 300 RTK** quadrotor with high-precision SINS positioning system.  
- **Sensor**: Zenmuse H20 wide-angle gimbal camera  
- **Video Spec**: 1080p@30Hz nadir imagery  
- **Key Measurements**:
  - Geographic coordinates (WGS84)  
  - 3D speed/attitude  
  - Gimbal camera orientation  
  - Flight trajectory metrics

---

## 2. File Structure
```bash
/Root
├─DJI_01_Afternoon_150m
│  ├─Frame_Cut       # 3s-interval frames from Video.mp4 (start at 2s)
│  ├─Ref             # Reference trajectory data
│  └─Video           # Raw video files
├─DJI_02_Afternoon_250m
│  ├─Frame_Cut
│  ├─Ref
│  └─Video
├─DJI_03_Noon_150m
│  ├─Frame_Cut
│  ├─Ref
│  └─Video
├─DJI_04_Evening_150m
│  ├─Frame_Cut
│  ├─Ref
│  └─Video
└─Map                # Satellite map & platform photos
