# Attenuator

Attenuator — Lazarus (Free Pascal) RF attenuation calculator for discrete crystal filters.

Quick start

- Requirements: Lazarus / Free Pascal (tested with Lazarus 2.x / FPC 3.x) to build from source. A Windows binary (Attenuator.exe) and a ZIP with the project source (Attenuator.zip) are included.
- Run (Windows): double-click Attenuator.exe.
- Build from source: unzip Attenuator.zip, open the project in Lazarus, then Build/Run.

Usage

- Inputs: center frequency, span, motional capacitance (Ci). See the program UI for exact field names.
- Outputs: a manufacturer data text file and a CSV response file (open in Excel or LibreOffice to view the simulated response).

Files of interest

- Attenuator.exe — prebuilt Windows binary (included).
- Attenuator.zip — Lazarus project and source files.

Notes

- This tool is provided as-is and has been lightly tested. Values for C0 (static/strain capacitance) and motional parameters must be known or estimated for accurate results.

License

This repository is licensed under the MIT License — see the LICENSE file for details.

Contact

For questions or corrections, open an issue or contact @glastones on GitHub.
