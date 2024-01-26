<p align="center">
  <a href="" rel="noopener"></a>
</p>

<h1 align="center">Motion Amplification Video Techniques for Vibration Analysis</h1>

![Motion Amplification Video](https://github.com/Soumyojyotisaha/Devpost-2024/blob/main/assets/283361105-421bf306-46cb-4869-a285-32557d155ca5.gif)

# 📝 Description <a name="description"></a>

Motion Amplification Video (MAV) is a technique used to visualize and measure vibrations in structures and machinery. This involves processing a video clip, extracting moving features between frames, and amplifying and replaying the motion in each frame. It renders defects at micro scales visible, enabling the determination of vibration amplitudes and mode shapes. This technology finds applications in evaluating noise, vibration, and shock across various platforms, including the automobile, power plants, and other engineering sectors.

# 💡 Approach <a name="approach"></a>

1. Input the video into a desktop application containing the object or structure with vibrations to be analyzed.
2. Perform frame-by-frame analysis using a 2-frame approach for motion amplification.
3. Define parameters for motion analysis, such as frame rate, resolution, and analysis duration.
4. Utilize the Lucas-Kanade method (Optical Flow) to calculate motion between consecutive frames.
5. Set up a mask to visualize motion vectors and adjust parameters for point selection and motion accuracy.
6. Visualize motion using red lines and circles.
7. Apply Eulerian Video Magnification to amplify motion in each frame by scaling pixel values, with an adjustable scaling factor.
8. Apply a color map to enhance motion visualization.
9. Generate data, mode shapes, FFT (Fast Fourier Transform) spectrum results, and time waveforms for vibrational analysis, along with detailed reports.

![Motion Amplification Video](https://github.com/Soumyojyotisaha/Devpost-2024/blob/main/assets/283361105-421bf306-46cb-4869-a285-32557d155ca5.gif)

# 📝 Use Cases <a name="use"></a>

- **Structural Health Monitoring:** MAV can identify hidden defects in buildings and bridges, ensuring safety and integrity.
- **Machinery Condition Assessment:** Detect defects, imbalances, or misalignments in industrial equipment, preventing breakdowns.
- **Automotive Diagnostics:** Employed to diagnose and improve vehicle component performance for safety and reliability.
- **Automobile Industry:** Analyze vibrations in automotive components, aiding in manufacturing quality control and vehicle maintenance.
- **Power Plants:** Monitor vibrations for reliability and safety, identifying potential faults and optimizing maintenance.
- **Aerospace Industry:** Assess structural integrity of aircraft, spacecraft, and components for safety and compliance.

# 💡 Novelty <a name="novelty"></a>

- **Eulerian Video Magnification:** Generates MAV in colors, providing superior results in amplifying subtle changes in color video.
- **Temporal Filters:** Reduce noise and enhance clarity in motion amplification videos.
- **Detailed Report on Vibrational Analysis:** Includes FFT spectrum, time waveform, and insightful statistical data from video frames.
- **Lucas-Kanade Method:** Optical flow generation assists in detecting the direction of vibrations.

## ⛏️ Built With <a name="tech_stack"></a>

- **Data Analysis:** Data Collection, Data Integration, Data Handling, Data Management, Data Processing
- **Backend Service:** NodeJS, ExpressJS, GraphQL, Flask
- **Machine Learning:** Python, TensorFlow, Numpy, Pandas, Scikit_Learn, Jupyter Notebook, VsCode, Flask, Keras, ML, DL (CNN, ANN, Neural Networking)
- **Data Visualization:** Matplotlib, Seaborn, Statistics
- **Frontend Service:** ReactJS, NextJS, MaterialUI, Tauri, ElectronJS, CSS, HTML, JS, ApolloClient

![Motion Amplification Video](https://github.com/Soumyojyotisaha/Devpost-2024/blob/main/assets/283361131-52330a3e-c2cd-48db-9bca-1090c2f97cc3.gif)

![Flow](https://github.com/Soumyojyotisaha/Devpost-2024/blob/main/assets/283364094-c3c043d1-0e81-46dd-8d87-d54e4ffde545.jpeg)

## Demonstration
[View Demonstration](https://github.com/vp-1234ms/SIH2023/assets/102847008/ae5fca94-d9d8-4003-ac83-76b313294f65)
