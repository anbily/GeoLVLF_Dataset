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
  - LATITUDE/LONGITUDE: The WGs84 geographic location of UAV (°).
  - ALTITUDE/REL HElGHT: The absolute altitude and fusion height relative to the ground (m).
  - DRONE SPEED: The 3D flight speeds of UAV in the geographic coordinate system (m/s).  
  - DRONE ATTITUDE: The 3D attitude of UAV in the geographic coordinate system (°).
  - GIMBAL CAM ATTITUDE: The 3D attitude of drone gimbal camera in the geographicordinate system (°).
  - GIMBAL CAM ATTITUDE: The 3D attitude of drone gimbal camera in the geographicordinate system (°).
  - DISTANCE: The flight distance relative to the UAV start position (m).
---

## 2. File Structure

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


## 3. Download Links

**Google Drive**:  
🔗 [Google Drive URL](https://drive.google.com/drive/folders/1D8e6pMLcQTHyklHN7HIolLSbICfsGWgD?usp=sharing): `https://drive.google.com/drive/folders/1D8e6pMLcQTHyklHN7HIolLSbICfsGWgD`

**Baidu Cloud**:  
🔗 [Baidu Cloud URL](https://pan.baidu.com/s/1O_hgbovls3nZYDXWNPVMwg?pwd=9172): `https://pan.baidu.com/s/1O_hgbovls3nZYDXWNPVMwg?pwd=9172`

---

### Usage Notice  
⚠️ **This dataset is intended for academic and research purposes only. Commercial use, redistribution, or modification for profit is strictly prohibited.**  

