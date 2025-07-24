# PROCESADOR_CHECADOR.xlsm

An Excel macro-powered tool to process and analyse employee entry/exit data for attendance tracking and performance evaluation.

## 📌 Features

- Processes raw check-in/check-out records
- Calculates:
  - Delays
  - Early exits
  - Overtime
  - Missing checks
- Summarizes data by week and employee
- Supports name corrections and shift adjustments
- Outputs clean reports for HR or administrative use

## 📂 Sheets Overview

| Sheet Name             | Purpose                                           |
|------------------------|---------------------------------------------------|
| `PREPARAR_1`, `2`      | Raw data input and cleaning                       |
| `PROCESADOR`           | Core calculation and analysis engine              |
| `TOTALES_POR_SEMANA`   | Weekly summaries by employee                      |
| `HORARIO_ENTRADA`      | Reference for expected entry times                |
| `ENTRADA_SERVICIO`     | Logs related to special service check-ins         |
| `TRABAJO_PARCIAL`      | Define part-time employees                        |
| `CAMBIO_NOMBRE`        | Correct employee names                            |

## 🚀 Getting Started

1. Open the file in **Excel with macros enabled** (`.xlsm` support is required).
2. Paste or import raw check-in/out data into `PREPARAR_1` or `PREPARAR_2` (designed for CrossCheck software export feature in mind).
3. Review and clean data as needed (e.g., adjust names, times).
4. Go to the `PROCESADOR` sheet to view processed outputs.
5. See `TOTALES_POR_SEMANA` for weekly summaries.

> 💡 The tool automatically calculates delays, early leaves, and overtime using embedded VBA macros.

## 🔒 Requirements

- Microsoft Excel (Desktop version, with macro support)
- Enable macros when prompted

## 👨‍💼 Author

Juan José Pasos Elvira  
📧 Optional: [pasos.juan02@gmail.com]

## 📄 License

This project is licensed under a custom **Non-Commercial License**.

- You are free to use, modify, and share this tool **for personal or internal business use only**.
- **Commercial use is not allowed** without **explicit written permission** from the author.
- Contact: [pasos.juan02@gmail.com] to request commercial licenses.

© 2025 Juan José Pasos Elvira. All rights reserved.