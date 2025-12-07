# 🖥️ PC Optimizing Toolkit

A complete **PC optimization and system performance guide** focused
on: - Higher and more stable performance - Lower system latency -
Network stability - Windows cleanup - Hardware and driver diagnostics

This repository is built for **any Windows PC user** who wants **maximum
stability, responsiveness, and efficiency**.

------------------------------------------------------------------------

## 📚 Table of Contents

1.  Tool Categories\
2.  Performance & FPS Tools\
3.  Mouse, Input & Peripheral Tools\
4.  Network, Ping & Routing Tools\
5.  Monitoring & Diagnostics\
6.  Windows Cleanup & Startup Control\
7.  Download Links\
8.  Performance Impact Summary\
9.  Baseline Optimization Stack\
10. System Tuning Presets\
11. General Best Practices

------------------------------------------------------------------------

## 1. Tool Categories Overview

  Category      Purpose
  ------------- -----------------------------------
  Performance   Higher and more stable output
  Input         Lower mouse and keyboard latency
  Network       Lower ping and fewer spikes
  Monitoring    Detect throttling and instability
  Cleanup       Reduce background system load

------------------------------------------------------------------------

## 2. Performance & FPS Tools

### MSI Afterburner

**Purpose:** GPU overclocking, undervolting, fan control, FPS overlay.

**Key Benefits:** - Higher sustained boost clocks - Reduced thermal
throttling - Improved minimum FPS

**Recommended Values:** - Power Limit: Maximum - Core Clock: +25 MHz
steps - Memory Clock: +50--100 MHz steps - Fan Curve: Aggressive custom
curve

**Typical Performance Gain:** +5% to +15%

------------------------------------------------------------------------

### RivaTuner Statistics Server (RTSS)

**Purpose:** Frame pacing and precise FPS limiting.

**Why It Matters:** Stable frame timing improves smoothness and system
responsiveness.

**FPS Caps:** - 144 Hz → 141 FPS - 165 Hz → 162 FPS - 240 Hz → 237 FPS -
360 Hz → 357 FPS

**Frame-Time Stability Improvement:** 20%--60%

------------------------------------------------------------------------

### Intelligent Standby List Cleaner (ISLC)

**Purpose:** Prevents Windows RAM standby stutter.

**Configuration:** - List Size: 1024 MB - 16 GB RAM → Free at 8192 MB -
32 GB RAM → Free at 16384 MB

**Stutter Reduction:** 30%--70%

------------------------------------------------------------------------

### Process Lasso

**Purpose:** CPU thread and priority management.

**Recommended Setup:** - Application Priority: High - ProBalance:
Disabled for critical apps - Do not modify parking unless experienced

**CPU Stability Improvement:** 3%--10%

------------------------------------------------------------------------

### Nvidia Control Panel / AMD Adrenalin

**Nvidia Settings:** - Low Latency Mode → Ultra - Power Management →
Prefer Maximum Performance - V-Sync → Off - Texture Quality → High
Performance

**AMD Settings:** - Anti-Lag → On - Chill → Off - Enhanced Sync → Off

**Input Latency Reduction:** 10%--35%

------------------------------------------------------------------------

## 3. Mouse, Input & Peripheral Tools

### Logitech G Hub / Razer Synapse / SteelSeries GG

**Purpose:** DPI, polling rate, macros, profiles.

**Recommended Setup:** - Polling Rate: 1000--4000 Hz - DPI Range:
400--1600 - Disable heavy RGB effects

------------------------------------------------------------------------

### Wootility (Wooting Keyboards)

**Purpose:** Rapid Trigger and analog input tuning.

**Recommended Values:** - Rapid Trigger: 0.1--0.4 mm - Actuation Point:
0.4--1.0 mm

**Key Reset Speed Increase:** 30%--70%

------------------------------------------------------------------------

### Raw Accel

**Purpose:** Custom mouse acceleration curve control.

------------------------------------------------------------------------

### MouseTester

**Purpose:** Polling rate stability and DPI accuracy testing.

------------------------------------------------------------------------

## 4. Network, Ping & Routing Tools

### Cloudflare WARP

**Purpose:** Internet routing and packet loss stabilization.

**Packet Loss Reduction:** 20%--90%\
**Ping Change:** -5 ms to +10 ms

------------------------------------------------------------------------

### ExitLag

**Purpose:** Paid routing optimization.

**Ping Reduction:** 5--30 ms

------------------------------------------------------------------------

### PingPlotter

**Purpose:** Network path diagnostics and spike monitoring.

------------------------------------------------------------------------

### NetLimiter

**Purpose:** Bandwidth monitoring and background network control.

------------------------------------------------------------------------

## 5. Monitoring & Diagnostics

  Tool          Thermals   Power   Frame-Time   Drivers   Network
  ------------- ---------- ------- ------------ --------- ---------
  HWiNFO64      Yes        Yes     No           No        No
  CapFrameX     No         No      Yes          No        No
  LatencyMon    No         No      Indirect     Yes       Yes
  PingPlotter   No         No      No           No        Yes

------------------------------------------------------------------------

## 6. Windows Cleanup & Startup Control

### Autoruns

**Boot Speed Improvement:** 15%--50%

------------------------------------------------------------------------

### O&O ShutUp10++

**Background Load Reduction:** 5%--15%

------------------------------------------------------------------------

### Revo Uninstaller

**Function:** Full leftover file and registry removal.

------------------------------------------------------------------------

### Windows Debloater

**RAM Recovery:** 0.5--2.5 GB

Do NOT remove: - .NET Framework - Visual C++ Runtimes - Xbox Services

------------------------------------------------------------------------

## 7. Download Links

  -------------------------------------------------------------------------------------------------------------------------
  Tool                                Link
  ----------------------------------- -------------------------------------------------------------------------------------
  MSI Afterburner                     https://www.msi.com/Landing/afterburner

  RTSS                                https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html

  ISLC                                https://www.wagnardsoft.com/ISLCw

  HWiNFO64                            https://www.hwinfo.com/download/

  CapFrameX                           https://www.capframex.com/

  LatencyMon                          https://www.resplendence.com/latencymon

  Process Lasso                       https://bitsum.com/

  Nvidia Drivers                      https://www.nvidia.com/Download/index.aspx

  AMD Drivers                         https://www.amd.com/en/support

  Logitech G Hub                      https://www.logitechg.com/ghub

  Razer Synapse                       https://www.razer.com/synapse-3

  SteelSeries GG                      https://steelseries.com/gg

  Wootility                           https://wooting.io/wootility

  Raw Accel                           https://github.com/a1xd/rawaccel

  MouseTester                         https://github.com/microe1/MouseTester

  Cloudflare WARP                     https://1.1.1.1

  ExitLag                             https://www.exitlag.com

  PingPlotter                         https://www.pingplotter.com

  NetLimiter                          https://www.netlimiter.com

  Autoruns                            https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns

  O&O ShutUp10++                      https://www.oo-software.com/en/shutup10

  Revo Uninstaller                    https://www.revouninstaller.com

  Windows Debloater                   https://github.com/Sycnex/Windows10Debloater
  -------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

## 8. Performance Impact Summary

  Area                   Improvement
  ---------------------- -----------------
  Output Performance     +5% to +15%
  Frame-Time Stability   20%--60%
  Input Latency          10%--35%
  Network Ping           -5 to -30 ms
  RAM Usage              -0.5 to -2.5 GB
  Boot Speed             15%--50% faster

------------------------------------------------------------------------

## 9. Baseline Optimization Stack

Minimum recommended setup: - MSI Afterburner - RTSS - ISLC - Nvidia
Control Panel or AMD Adrenalin - Peripheral Software - Cloudflare WARP
or ExitLag

------------------------------------------------------------------------

## 10. System Tuning Presets

  RAM     ISLC Free Value
  ------- -----------------
  16 GB   8192 MB
  32 GB   16384 MB

  Monitor   FPS Cap
  --------- ---------
  144 Hz    141
  165 Hz    162
  240 Hz    237
  360 Hz    357

------------------------------------------------------------------------

## 11. General Best Practices

-   Keep BIOS and chipset drivers updated.
-   Use wired Ethernet.
-   Disable unnecessary overlays.
-   Avoid excessive background software.
-   Never use registry cleaners claiming FPS boosts.
-   Restart after major driver updates.
-   Apply one optimization at a time.

------------------------------------------------------------------------

## ✅ Final Notes

This toolkit is designed for: - System performance tuning - Competitive
gaming and low-latency setups - Daily-use responsiveness improvement -
Hardware diagnostic and stability testing

Applied correctly, it provides **clean performance gains, lower system
latency, and stronger stability**.

------------------------------------------------------------------------

End of README.
