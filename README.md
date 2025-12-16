<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0B0F,50:2A0845,100:4B1B7C&height=210&section=header&text=Diana%20Laura%20Bocardo%20Gonz%C3%A1lez&fontSize=38&fontAlignY=35&fontColor=FFFFFF&desc=Biomedical%20Engineering%20|%20Medical%20Instrumentation%20|%20Embedded%20Systems&descAlignY=55&descColor=E0E0E0" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&pause=1000&color=00E5FF&center=true&vCenter=true&width=750&lines=Biomedical+Engineering+Student;Medical+Devices+%26+Instrumentation;Embedded+Systems+%7C+Signal+%26+Image+Processing;Target+Roles%3A+Intel+%7C+Micron+%7C+Texas+Instruments" />
</p>

---

## 🚀 About Me (Industry-Focused)

<p align="justify">
I am a <b>Biomedical Engineering student</b> with a strong focus on <b>medical instrumentation, embedded systems, and signal processing</b>, aligned with industry-grade development and validation practices.

Throughout my academic career, I have designed and implemented <b>end-to-end biomedical systems</b>: sensor acquisition, analog conditioning, embedded programming, digital signal processing, and data visualization. My approach emphasizes <b>precision, robustness, and documentation</b>, skills highly relevant to semiconductor, hardware validation, and medical device environments.

I am actively preparing for engineering roles at <b>Intel, Micron, and Texas Instruments</b>, where attention to detail, system-level thinking, and hardware–software integration are critical.

</p>

---

## 🧠 Core Technical Skills

### 💻 Programming Languages (with practical usage)

![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge\&logo=cplusplus\&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D.svg?style=for-the-badge\&logo=arduino\&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8.svg?style=for-the-badge\&logo=mathworks\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00.svg?style=for-the-badge\&logo=openjdk\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge\&logo=html5\&logoColor=white)

**Estimated Lines of Code (academic + projects):**

* **C++:** ~12,000+ LOC (signal processing, algorithms, data handling)
* **Arduino (C/C++):** ~9,000+ LOC (embedded control, sensor acquisition)
* **MATLAB:** ~8,000+ LOC (signal & image processing, analysis)
* **Java:** ~4,000+ LOC (structured programming, OOP)
* **HTML:** ~3,000+ LOC (interfaces, visualization support)

> *LOC values are cumulative across university projects and continuous development.*

---

## 🧩 Code Samples (Representative)

### 🔹 C++ — Signal Processing Logic

```cpp
// Simple moving average filter for biomedical signals
float movingAverage(float* signal, int index, int window) {
    float sum = 0.0;
    for (int i = 0; i < window; i++) {
        sum += signal[index - i];
    }
    return sum / window;
}
```

### 🔹 Arduino — Sensor Acquisition

```cpp
int sensorPin = A0;
float voltage;

void setup() {
  Serial.begin(9600);
}

void loop() {
  int raw = analogRead(sensorPin);
  voltage = (raw * 5.0) / 1023.0;
  Serial.println(voltage);
  delay(10);
}
```

### 🔹 MATLAB — Signal Filtering

```matlab
fs = 1000;                % Sampling frequency
fc = 40;                  % Cutoff frequency
[b,a] = butter(4, fc/(fs/2));
filteredSignal = filtfilt(b,a,rawSignal);
plot(filteredSignal);
```

### 🔹 Java — Object-Oriented Structure

```java
public class SensorData {
    private double value;

    public SensorData(double value) {
        this.value = value;
    }

    public double getValue() {
        return value;
    }
}
```

### 🔹 HTML — Data Visualization Interface

```html
<!DOCTYPE html>
<html>
<head>
  <title>Biomedical Data Viewer</title>
</head>
<body>
  <h1>Signal Visualization</h1>
  <canvas id="chart"></canvas>
</body>
</html>
```

---

## ⚙️ Hardware & Embedded Systems Focus (Industry-Oriented)

* Microcontroller-based system design
* Analog signal conditioning (amplification & filtering)
* Sensor calibration and validation
* Hardware–software integration
* Simulation and debugging using **Proteus**

---

## 🧪 Selected University Projects

### 🫁 Digital Spirometer

* Differential pressure sensing
* Calibration and validation procedures
* Flow and volume computation
* Embedded data acquisition

### ❤️ Electrocardiogram (ECG)

* Low-amplitude bio-signal acquisition
* Noise reduction and filtering
* Waveform identification

### 🧠 Electroencephalogram (EEG)

* High-gain amplification stages
* Signal stability and conditioning
* Data interpretation

### 🩺 Digital Blood Pressure Monitor

* Pressure sensor integration
* Embedded processing
* Measurement accuracy analysis

### ⚙️ Process Automation

* Embedded logic control
* System optimization

### 🖼️ Image Processing

* Feature extraction
* Quantitative biomedical analysis

---

## 🎯 Career Goals

* Entry-level engineering role or internship in:

  * Hardware validation
  * Embedded systems
  * Medical devices
  * Semiconductor-related applications
* Continuous improvement in low-level programming and signal integrity
* Contribution to high-reliability engineering teams

---

## 📊 GitHub Statistics

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=dianabocardo&show_icons=true&theme=tokyonight" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=dianabocardo&theme=tokyonight" width="48%" />
</div>

---

## 🔗 Connect With Me

<p align="center">
<a href="https://www.linkedin.com/in/diana-bocardo/">
<img src="https://img.shields.io/badge/LinkedIn-Diana%20Bocardo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
</p>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>

⭐ <i>Industry-ready engineering portfolio — built for impact.</i>
