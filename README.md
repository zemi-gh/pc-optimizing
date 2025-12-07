# Pro Gaming Performance Toolkit --- Full Setup & Optimization Guide

This README covers **performance, input, network, monitoring, and
Windows optimization tools** used in competitive gaming.\
It includes **what each tool does, how to use it, recommended settings,
performance impact ranges, and hardware scaling tiers**.

------------------------------------------------------------------------

## Table of Contents

1.  Performance & FPS Tools\
2.  Mouse, Input & Peripheral Tools\
3.  Network, Ping & Routing Tools\
4.  System Monitoring & Diagnostics\
5.  Windows Cleanup & Startup Control\
6.  Comparison Tables\
7.  Performance Impact Ranges\
8.  Recommended Pro Baseline Stack\
9.  General Best Practices\
10. CPU-Tier & GPU-Tier Scaling Tables

------------------------------------------------------------------------

## 1. Performance & FPS Tools

(unchanged from previous version)

------------------------------------------------------------------------

## 7. Performance Impact Ranges

  Tool                  Main Benefit      Impact Range
  --------------------- ----------------- -------------------------------
  MSI Afterburner       Raw FPS           +5% to +15%
  RTSS                  Frame Pacing      20%--60% smoother frame times
  ISLC                  Stutter Control   30%--70% reduction
  Nvidia/AMD Settings   Input Latency     10%--35% lower delay
  ExitLag               Ping              -5 ms to -30 ms
  Autoruns              Boot Speed        15%--50% faster startup
  Windows Debloater     RAM Usage         -0.5 to -2.5 GB

------------------------------------------------------------------------

## 8. Recommended Pro Baseline Stack

Minimum competitive install: - MSI Afterburner - RTSS - ISLC - Nvidia
Control Panel or AMD Adrenalin - Peripheral Software - Cloudflare WARP
or ExitLag

------------------------------------------------------------------------

## 9. General Best Practices

-   Keep BIOS and chipset drivers updated.
-   Use wired Ethernet, not Wi-Fi.
-   Disable Discord overlay.
-   Avoid background RGB software.
-   Never use registry "FPS booster" tools.
-   Test changes one at a time.

------------------------------------------------------------------------

## 10. CPU-Tier Scaling Table (Competitive 1080p)

  -------------------------------------------------------------------------------
  Tier         Example CPUs  Game FPS Range (Esports Titles)  Bottleneck Profile
  ------------ ------------- -------------------------------- -------------------
  Entry        i3-10100,     144--220 FPS                     CPU-limited
               Ryzen 3 3100                                   

  Mid          i5-10400,     200--320 FPS                     Balanced
               Ryzen 5 3600                                   

  High         i5-13600K,    280--450 FPS                     GPU or
               Ryzen 7 5800X                                  engine-limited

  Enthusiast   i9-13900K,    360--600+ FPS                    Engine-limited
               Ryzen 7                                        
               7800X3D                                        
  -------------------------------------------------------------------------------

------------------------------------------------------------------------

## 11. GPU-Tier Scaling Table (Competitive 1080p)

  Tier       Example GPUs            Esports FPS Range   Render Latency Profile
  ---------- ----------------------- ------------------- ------------------------
  Entry      GTX 1660, RX 5500 XT    120--200 FPS        GPU-limited
  Mid        RTX 3060, RX 6600 XT    180--300 FPS        Balanced
  High       RTX 3070, RX 6800       240--400 FPS        Latency-optimized
  Flagship   RTX 4080, RX 7900 XTX   300--600+ FPS       CPU-engine capped

------------------------------------------------------------------------

## 12. Combined CPU + GPU Scaling Overview

  -------------------------------------------------------------------------
  CPU Tier  GPU Tier      Entry GPU   Mid GPU    High GPU   Flagship GPU
  ----------------------- ----------- ---------- ---------- ---------------
  Entry CPU               120--180    140--200   150--210   150--210 FPS
                          FPS         FPS        FPS        

  Mid CPU                 140--220    200--300   230--330   230--330 FPS
                          FPS         FPS        FPS        

  High CPU                160--240    240--360   300--450   320--500 FPS
                          FPS         FPS        FPS        

  Enthusiast CPU          180--260    280--420   360--550   420--650 FPS
                          FPS         FPS        FPS        
  -------------------------------------------------------------------------

------------------------------------------------------------------------

End of document.
