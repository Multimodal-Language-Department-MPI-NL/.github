<p align="center">
  <img src="assets/logo_long.png" alt="Multimodal Language Department Logo" width="500"/>
</p>

# Multimodal Language Department – MPI for Psycholinguistics

We study how visible bodily signals (hands, face, body posture) coordinate with speech to form multimodal language. Our work spans corpora, experimental design, computational modeling, and kinematic / gesture analysis.  
More info: [MPI Multimodal Language Department](https://www.mpi.nl/department/multimodal-language-department/23)

---

## Foundational Code for Kinematic Analytics

Below are foundational code modules used by members of our department that support general kinematic analyses of gestures and signs. Portions of many of these scripts are sourced and adapted from EnvisionBox (https://envisionbox.org) which maintains a library of coding modules for open exchange among researchers.

| Module | Purpose | Repository |
|---|---|---|
| [Extracting MediaPipe keypoints](https://github.com/Multimodal-Language-Department-MPI-NL/MediaPipe_keypoints_extraction) | Extract motion tracking data from videos using MediaPipe | `gesture-keypoints` |
| [Smoothing](https://github.com/Multimodal-Language-Department-MPI-NL/Smoothing) | Smooth raw motion tracking data to reduce noise due to tracking inaccuracies | `gesture-smoothing` |
| [Normalization](https://github.com/Multimodal-Language-Department-MPI-NL/Normalization) | Normalize the size, position, and viewpoint of motion tracking data across participants | `gesture-normalization` |
| [Merging ELAN and MediaPipe](https://github.com/Multimodal-Language-Department-MPI-NL/Merging_Motion_ELAN) | Merge motion tracking data with ELAN annotations | `gesture-merge` |
| [Speed, Acceleration, and Jerk](https://github.com/Multimodal-Language-Department-MPI-NL/Speed_Acceleration_Jerk) | Calculate motion measures: velocity, acceleration, jerk | `gesture-kinematics` |
| [Submovements and Holds](https://github.com/Multimodal-Language-Department-MPI-NL/Submovements_Holds) | Detect movement segments, pauses, hold events | `gesture-submovements` |
| [Gesture Space, Size, and Volume](https://github.com/Multimodal-Language-Department-MPI-NL/Gesture_Space_Size_and_Volume) | Quantify use of gesture space (e.g., height, size, volume) | `gesture-space` |
| [Heatmap Visualization](https://github.com/Multimodal-Language-Department-MPI-NL/Heatmap) | Plot heatmap scatterplot showing density of gesture locations | `gesture-heatmap` |



---

## Other Department Projects & Codebases

These are research code projects by other collaborators in our department. Their structure or maintenance may vary, but they often link to domain-specific methods or applications.

| Project | Description | Link / Repository |
|---|---|---|
| [Medal Workshop] | Methods for the automatic processing of multimodal interaction | [medal_workshop_on_multimodal_interaction](https://github.com/Multimodal-Language-Department-MPI-NL/medal_workshop_on_multimodal_interaction) |
| [WhisperX Tutorial] | Tutorial for transcribing speech automatically using WhisperX | [whisperx_tutorial](https://github.com/Multimodal-Language-Department-MPI-NL/whisperx_tutorial) |
| [Dynamic time warping] | Validating dynamic time warping as a measure of gesture form similarity | [dynamic time warping](https://github.com/Multimodal-Language-Department-MPI-NL/dtw_osf) |

---

### Contact & Links

- Department homepage: [mpi.nl](https://www.mpi.nl/department/multimodal-language-department/23)  
- MPI main site: [mpi.nl](https://www.mpi.nl)  

---
