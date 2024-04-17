<div align="justify">
  
# Space Narration Interactive Content Design in Mixed Reality

## Project Overview
"Space Narration Interactive Content Design in Mixed Reality" leverages the thematic essence of "The Little Prince" to create an engaging MR environment within hospital settings. This project intricately blends physical interactions using Arduino with virtual responses via Unity and Hololens, creating a narrative where emotional and physical inputs influence the healing space. Scenes from "The Little Prince" are reimagined within this framework, allowing users to interact with a virtual rose and surrounding environment, which respond dynamically to user input, capturing the magic and intimacy of the classic tale.

The MR environment is structured around key scenes:
- **Scene 1**: The user, embodying the Little Prince, notices a lone red rose in a virtual desert.
- **Scene 2**: Drawn to its beauty, the user approaches the rose, triggering proximity interactions.
- **Scene 3**: Upon touching the rose, using Arduino-based touch sensors, the rose reacts subtly.
- **Scene 4**: Emotional responses, captured via EEG, cause the surrounding virtual landscape to bloom with more flowers, reflecting the user's emotional state.

This project not only captures the narrative but also integrates sophisticated technology to create a seamless interaction between the real and virtual worlds, where physical movements and emotional states are translated into meaningful virtual experiences.

## Key Contributions
- **Thematic Integration**: Using "The Little Prince" as a narrative backdrop to deepen the emotional engagement and relatability of the MR experience.
- **Technological Fusion**: Combining EEG for emotional input, Arduino for physical interaction, and Hololens for augmented reality display, creating a comprehensive mixed reality environment. This setup utilizes:
  - **Pressure and Distance Data**: To trigger interactions in Unity's visual world, enhancing the realism and responsiveness of the virtual elements.
  - **Emotional Data**: EEG sensors detect the user's emotional states to dynamically alter the virtual environment, enriching the user experience by aligning it with their feelings.
- **Innovative Storytelling in MR**: The project pushes the boundaries of how mixed reality can be used for storytelling, not just through visual elements but through interactive and responsive environments that adapt to the user's emotional and physical inputs.

## Installation and Usage
This section guides you through setting up the necessary software and hardware to get the project running.

### Prerequisites
- **Arduino IDE** (Version 1.8.19 or higher)
- **Visual Studio 2019 Pro** (Version 2019 or higher)
- **Unity** (Configured for MR environments; refer to `MR Environment.zip`)
- **Blender** (Version 3.1.21111 or higher)
- **EEG Device Setup** (compatible model for emotion sensing)
- **Hololens** or similar MR headset

### Detailed Installation Guide
1. **Arduino Configuration**:
   - Connect the Arduino to your development system.
   - Load the provided Arduino script which controls the physical aspects like sensors and actuators based on EEG input.

2. **Unity and MR Toolkit Setup**:
   - Install Unity and import the project from `MR Environment.zip`.
   - Configure Unity to communicate with Arduino and Hololens, setting up scenes as per the storyboard detailed in the `Space Narration Interactive Content Design in Mixed Reality photos.pdf`.

3. **Hololens and EEG Integration**:
   - Ensure that Hololens is paired and correctly configured with your development machine.
   - Set up the EEG device following manufacturer guidelines to ensure accurate emotional input capture.

### Usage Instructions
- **Starting the Experience**:
   - Wear the EEG headset and the Hololens.
   - Initiate the Unity application. As you move around the configured space, the virtual entities (flowers, etc.) respond to your proximity and emotional state, changing visually and behaviorally.
- **Interacting with the Environment**:
   - Approach specific markers or areas within the space to trigger interactions. These can include blossoming of flowers or changes in color and intensity, corresponding to the user's emotional state detected via EEG.

## Files and Resources
- **`MR Environment.zip`** and **`MRTK-Update.zip`**: Available for download at [Google Drive](https://drive.google.com/drive/folders/1Ohd53vIOyQFkL1-iX9nAu_RPeldZDOFH?usp=sharing). These contain the Unity project and updates necessary for setting up the MR environment.
- **`Space Narration Interactive Content Design in Mixed Reality photos.pdf`**: Final project presentation, providing an overview and visual documentation.
- **`Space Narration Interactive Content Design in Mixed Reality.mp4`**: Demonstrates the test interactions within the MR environment.
- **`flower.blend`**: Blender file for the primary model used in the test: Available for download at [Google Drive](https://drive.google.com/drive/folders/1Ohd53vIOyQFkL1-iX9nAu_RPeldZDOFH?usp=sharing).

## Project Team
- Zhirui Bian
- Qian Xu
- Fujian Zhao
- Sky Lo Tian Tian (Advisor)

## Acknowledgements
Thanks to all contributors, especially the advisory and technical support from the community and institutions dedicated to advancing mixed reality technologies.
