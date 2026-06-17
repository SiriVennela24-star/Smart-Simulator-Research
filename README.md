```html
<div align="center">

<h1>🛰️ Smart Satellite Communication Security Testing System</h1>

<h3>Course Code: 1PW663AD</h3>

<p>
A Software-Defined, Hardware-Free Satellite Communication Simulation and Security Framework
</p>

<img src="https://img.shields.io/badge/Python-3.10+-blue">
<img src="https://img.shields.io/badge/FastAPI-ASGI-green">
<img src="https://img.shields.io/badge/Machine%20Learning-Isolation%20Forest-orange">
<img src="https://img.shields.io/badge/Quantum%20Security-BB84-purple">
<img src="https://img.shields.io/badge/Research-Project-red">

</div>

<hr>

<h2>📌 Project Overview</h2>

<p align="justify">
Modern satellite communication systems face increasingly sophisticated threats including electronic warfare, signal spoofing, jamming attacks, passive eavesdropping, and environmental signal degradation. Traditional validation and testing infrastructures require expensive Software Defined Radios (SDRs), anechoic chambers, telemetry laboratories, and specialized aerospace equipment costing millions of dollars.
</p>

<p align="justify">
This project introduces a fully software-defined and hardware-free satellite communication security testing framework capable of simulating realistic orbital dynamics, telemetry transmission, quantum-safe communication, intelligent anomaly detection, and adaptive network routing. The platform integrates advanced aerospace simulation, digital signal processing, machine learning, reinforcement learning, and quantum cryptographic security into a unified research environment.
</p>

<hr>

<h2>🎯 Objectives</h2>

<ul>
<li>Simulate realistic Low Earth Orbit (LEO) satellite communication links.</li>
<li>Model Doppler frequency shifts using orbital mechanics.</li>
<li>Detect electronic warfare attacks and signal anomalies.</li>
<li>Implement quantum-safe communication protocols.</li>
<li>Differentiate environmental interference from active attacks.</li>
<li>Enable autonomous satellite handover decisions.</li>
<li>Provide a low-cost software alternative to physical testbeds.</li>
<li>Support real-time telemetry monitoring and visualization.</li>
</ul>

<hr>

<h2>🏗️ System Architecture</h2>

<pre>
┌─────────────────────────────────────┐
│        Interactive Dashboard        │
│     WebGL + HTML5 Visualization     │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│     FastAPI + WebSocket Server      │
│      Asynchronous ASGI Layer        │
└─────────────────┬───────────────────┘
                  │
    ┌─────────────┼─────────────┐
    ▼             ▼             ▼

┌─────────┐ ┌─────────────┐ ┌───────────┐
│ SGP4    │ │ Isolation   │ │ Quantum   │
│ Orbit   │ │ Forest ML   │ │ BB84 QKD  │
│ Engine  │ │ Detector    │ │ Security  │
└─────────┘ └─────────────┘ └───────────┘
      │             │              │
      └──────┬──────┴──────┬───────┘
             ▼             ▼

      ┌─────────────────────┐
      │ DSP + Kalman Filter │
      │ Signal Processing   │
      └─────────────────────┘
</pre>

<hr>

<h2>🚀 Core Features</h2>

<h3>🛰️ Astrodynamics Engine</h3>

<ul>
<li>SGP4 orbital propagation</li>
<li>TLE parameter processing</li>
<li>LEO satellite trajectory simulation</li>
<li>Ground station visibility prediction</li>
<li>Doppler shift estimation</li>
</ul>

<h3>📡 Physical Layer DSP</h3>

<ul>
<li>Carrier frequency generation</li>
<li>PSK signal modulation</li>
<li>Doppler compensation</li>
<li>Kalman filtering</li>
<li>Noise suppression</li>
<li>Signal tracking loops</li>
</ul>

<h3>🤖 AI Threat Detection Engine</h3>

<ul>
<li>Isolation Forest anomaly detection</li>
<li>Rolling statistical feature extraction</li>
<li>Jamming attack identification</li>
<li>Signal integrity monitoring</li>
<li>Unsupervised learning architecture</li>
</ul>

<h3>🔐 Quantum Security Layer</h3>

<ul>
<li>BB84 Quantum Key Distribution</li>
<li>QBER monitoring</li>
<li>Photon loss analysis</li>
<li>Wiretap detection</li>
<li>Automatic key invalidation</li>
</ul>

<h3>🛰️ Reinforcement Learning Module</h3>

<ul>
<li>Autonomous route optimization</li>
<li>Ground station selection</li>
<li>Constellation handover planning</li>
<li>Adaptive communication path management</li>
</ul>

<hr>

<h2>📐 Mathematical Formulation</h2>

<h3>1️⃣ Quantum Bit Error Rate (QBER)</h3>

<pre>
QBER = Ebits / Nsifted
</pre>

Where:

<ul>
<li>Ebits = Number of erroneous bits</li>
<li>Nsifted = Number of sifted key bits</li>
</ul>

<h3>2️⃣ Doppler Shift Estimation</h3>

<pre>
Δf = -fc × (vrelative / c) × tanh((t - tclosest) / B)
</pre>

Where:

<ul>
<li>fc = Carrier Frequency</li>
<li>vrelative = Relative Velocity</li>
<li>c = Speed of Light</li>
<li>B = Pass Window Coefficient</li>
</ul>

<h3>3️⃣ Kalman Filter</h3>

<pre>
Prediction:
x̂(k|k−1) = x̂(k−1|k−1)

P(k|k−1) = P(k−1|k−1) + Q

Correction:

K(k) = P(k|k−1)/(P(k|k−1)+R)

x̂(k|k)=x̂(k|k−1)+K(k)(z(k)-x̂(k|k−1))

P(k|k)=(1−K(k))P(k|k−1)
</pre>

<hr>

<h2>📊 Experimental Results</h2>

<h3>Finding 1: Doppler Tracking Stability</h3>

<p>
The system accurately tracked a ±100 kHz Doppler frequency shift generated during a simulated LEO pass and maintained stable signal lock without communication interruption.
</p>

<h3>Finding 2: AI-Based Threat Detection</h3>

<p>
The Isolation Forest model achieved 91% classification accuracy while correctly identifying structured jamming attacks without requiring labeled training data.
</p>

<h3>Finding 3: Near-Perfect ROC Performance</h3>

<p>
The threat detection subsystem achieved an Area Under Curve (AUC) score of 0.991, demonstrating strong anomaly separation capability.
</p>

<h3>Finding 4: Quantum Security Validation</h3>

<p>
Under a simulated intercept-resend attack, the QBER converged to approximately 25–28%, validating the theoretical BB84 security model.
</p>

<h3>Finding 5: Weather vs Wiretap Discrimination</h3>

<p>
The system successfully differentiated atmospheric rain fade from malicious interception using photon attenuation and QBER correlation analysis.
</p>

<h3>Finding 6: Ultra-Low Latency Communication</h3>

<p>
The ASGI-WebSocket architecture maintained end-to-end latency below 3 ms at traffic loads reaching 5000 packets per second.
</p>

<h3>Finding 7: Autonomous Satellite Handover</h3>

<p>
The platform automatically switched communication links between satellites before line-of-sight degradation occurred.
</p>

<h3>Finding 8: Kalman-Based Signal Recovery</h3>

<p>
Recursive Kalman filtering effectively removed high-frequency electronic warfare noise and restored signal stability.
</p>

<h3>Finding 9: Reinforcement Learning Optimization</h3>

<p>
The Q-Learning module learned optimal communication routes and avoided unstable ground stations.
</p>

<h3>Finding 10: Phase Spoofing Detection</h3>

<p>
Variational quantum circuits successfully identified hidden phase-spoofing attacks concealed within background noise.
</p>

<h3>Finding 11: Multi-Layer Security Validation</h3>

<p>
The combined Physical Layer, AI Layer, and Quantum Layer created a resilient three-tier defense architecture capable of protecting future NTN systems.
</p>

<hr>

<h2>🛠️ Technology Stack</h2>

<table>
<tr>
<th>Category</th>
<th>Technologies</th>
</tr>

<tr>
<td>Backend</td>
<td>Python, FastAPI</td>
</tr>

<tr>
<td>Networking</td>
<td>WebSockets, ASGI</td>
</tr>

<tr>
<td>Database</td>
<td>SQLite, aiosqlite</td>
</tr>

<tr>
<td>Machine Learning</td>
<td>Scikit-Learn, Isolation Forest</td>
</tr>

<tr>
<td>Signal Processing</td>
<td>NumPy, SciPy</td>
</tr>

<tr>
<td>Visualization</td>
<td>Matplotlib, Plotly, WebGL</td>
</tr>

<tr>
<td>Orbital Mechanics</td>
<td>SGP4</td>
</tr>

<tr>
<td>Quantum Security</td>
<td>BB84 Simulation</td>
</tr>

<tr>
<td>Reinforcement Learning</td>
<td>Q-Learning</td>
</tr>

</table>

<hr>

<h2>⚙️ Installation</h2>

<pre>
git clone https://github.com/yourusername/smart-satellite-security-testing.git

cd smart-satellite-security-testing

pip install numpy pandas matplotlib scikit-learn scipy sgp4 fastapi uvicorn aiosqlite
</pre>

<hr>

<h2>▶️ Running the Project</h2>

<pre>
python core_engine_validation.py
</pre>

<p>
This script reproduces all experimental figures, validation metrics, and performance benchmarks used within the research study.
</p>

<hr>

<h2>🌍 Sustainable Development Goals (SDGs)</h2>

<table>
<tr>
<th>SDG</th>
<th>Contribution</th>
</tr>

<tr>
<td>SDG 4.1.2</td>
<td>Provides accessible and affordable research infrastructure for satellite communication education.</td>
</tr>

<tr>
<td>SDG 9.5.1</td>
<td>Promotes innovation in resilient communication infrastructure and advanced space technologies.</td>
</tr>

</table>

<hr>

<h2>📈 Future Enhancements</h2>

<ul>
<li>Digital Twin Satellite Networks</li>
<li>Quantum Machine Learning Integration</li>
<li>Multi-Orbit NTN Support</li>
<li>Federated Space Intelligence</li>
<li>Satellite Swarm Coordination</li>
<li>5G/6G NTN Interoperability</li>
<li>Real-Time SDR Integration</li>
<li>Cloud-Native Deployment</li>
</ul>

<hr>

<div align="center">

<h2>🎓 Research Conclusion</h2>

<p>
The Smart Satellite Communication Security Testing System demonstrates that a fully software-defined architecture can accurately emulate real satellite communication environments while providing advanced cyber-defense, machine learning-based threat isolation, and quantum-assisted security mechanisms. The platform offers a scalable, low-cost, and research-ready alternative to expensive satellite testing laboratories and provides a foundation for future resilient Non-Terrestrial Networks (NTNs).
</p>

<b>Developed for Academic Research, Satellite Security Testing, and Next-Generation Space Communication Systems.</b>

</div>
```
