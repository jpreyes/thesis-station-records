# thesis-station-records
# Strong-Motion Records – Illapel Earthquake (Chile, 2015)

This repository contains the baseline-corrected acceleration records used in the doctoral thesis of **Juan Pablo Reyes Cancino**, related to the seismic event of **September 16, 2015 (Mw 8.4) in Illapel, Chile**.

The dataset includes time series of ground acceleration (in m/s²) for both North and East components, as well as metadata such as station name, geographic location, and hypocentral distance.

---

## 📘 Context

These records were used in the doctoral thesis:

> **Lessons Learned from the Survey of Damage to School Buildings by the Mw = 8.4 Illapel Earthquake (Chile, September 2015)**  
> Author: Juan Patricio Reyes Cancino  
> Universitat Politècnica de Catalunya (UPC), 2025

---

## 🗂️ Dataset Structure

Each station has its own `.txt` file named as `StationCode.txt`.  
The structure of each file is as follows:

StationName Centro Deportivo Municipal Pisco Elqui
StationCode C14O
Latitude -30.123091
Longitude -70.490608
Rhypo_km 205.501755

Time_s Acceleration_North_mps2 Acceleration_East_mps2
0.000000 -8.88E-05 -7.46E-07
...


At the end of each file, a reference note is included.

---

## 📚 Data Source

All ground motion records were extracted from the following open-access dataset:

> Sebastián Castro, Roberto Benavente, Jorge G. F. Crempien, Gabriel Candia, Juan Carlos de la Llera (2022).  
> *A Consistently Processed Strong‐Motion Database for Chilean Earthquakes.*  
> Seismological Research Letters, 93(5), 2700–2718.  
> https://doi.org/10.1785/0220200336

---

## 📜 License

This project is licensed under the **MIT License**. See below for details.

MIT License

Copyright (c) 2025 Juan Patricio Reyes Cancino

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE


---

## 👨‍🎓 Author

**Juan Patricio Reyes Cancino**  
Doctoral candidate in Structural and Earthquake Engineering  
Universitat Politècnica de Catalunya (UPC)

---
