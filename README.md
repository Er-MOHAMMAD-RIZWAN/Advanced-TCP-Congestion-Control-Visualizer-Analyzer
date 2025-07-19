
# 🛰️ Advanced TCP Congestion Control Visualizer & Analyzer

A web-based tool for visualizing, analyzing, and comparing TCP congestion control algorithms (e.g., Reno, Cubic, BBR) using real packet captures or simulated traffic.

## 🚀 Features

- 📊 **Congestion Window (CWND) Visualization**
- 📈 **Throughput, RTT, and Packet Loss Graphs**
- 🔍 **Analysis of TCP Events**: Slow start, congestion avoidance, fast retransmit, etc.
- 🧠 **Comparison of TCP Algorithms** (Reno, Cubic, BBR)
- 💾 **Pcap File Upload and Parsing**
- 🔴 **Live Traffic Capture** *(optional)*
- 🧮 **Statistics Dashboard** per connection
- 🧰 Extensible for research and education

---

## 📂 Project Structure

```plaintext
tcp-visualizer/
├── backend/            # Python FastAPI or Flask backend
│   ├── parser/         # Pcap parsers using Scapy or PyShark
│   ├── models/         # TCP flow & analysis models
│   └── main.py         # API entry point
│
├── frontend/           # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   └── App.tsx
│   └── public/
│
├── sample_data/        # Sample pcap files
├── README.md
└── requirements.txt
