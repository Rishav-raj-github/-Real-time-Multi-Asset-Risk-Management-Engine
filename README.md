# -Real-time-Multi-Asset-Risk-Management-Engine
Developing a comprehensive risk management system that processes millions of trades per second with real-time anomaly detection.

A scalable engine to manage portfolio and trade risk **in real-time** across equities, derivatives, and futures.

## Key Features
- Written in **OCaml** for low-latency & reliability
- Apache Kafka powered event-driven design
- Online-learning ML algorithms for anomaly detection
- Stress test simulation framework

## Tech Stack
- **Core Language**: OCaml
- **Event Pipeline**: Apache Kafka
- **ML**: Scikit-learn / PyTorch (via bindings)
- **DB**: PostgreSQL / TimescaleDB

## Architecture
1. Kafka streams receive market/trade events
2. Core OCaml engine calculates risk metrics
3. ML models flag unusual risk spikes
4. Dashboard for live monitoring
