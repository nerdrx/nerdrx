<img src="assets/header.svg" alt="nerdrx — VR, creative tools, and local-first software." width="100%" />

I build the **NX family**: expressive avatar materials, GPU experiments, and software you can run on your own hardware. This is the workshop—try a build, explore the research, or follow what comes next.

## NXSG

[![NX Shader Graph — visual materials for VRChat](https://raw.githubusercontent.com/nerdrx/nxsg/main/docs/assets/nxsg-banner.svg)](https://github.com/nerdrx/nxsg)

Build VRChat avatar materials by connecting nodes in Unity. Toon and PBR shading, fur, particles, procedural textures, and animated effects—with live previews as you work. Built for PC VRChat; mobile materials use a separate snapshot bake.

<a href="https://github.com/nerdrx/nxsg"><img src="https://raw.githubusercontent.com/nerdrx/nxsg/fa81d1095fd976936f6fa6e8ee5490a67cbb9111/docs/images/auto-organize-branches.png" width="100%" alt="NXSG node editor in Unity, with grouped material branches and a live particle preview" /></a>

<sub>Connect the graph. Preview the material. Build for VRChat.</sub>

<table><tr>
<td width="50%"><a href="https://github.com/nerdrx/nxsg"><img src="https://raw.githubusercontent.com/nerdrx/nxsg/fa81d1095fd976936f6fa6e8ee5490a67cbb9111/docs/assets/hologram-study.png" width="100%" alt="Violet and cyan hologram material rendered on a sphere and capsule" /></a><br/><sub>Hologram study</sub></td>
<td width="50%"><a href="https://github.com/nerdrx/nxsg"><img src="https://raw.githubusercontent.com/nerdrx/nxsg/fa81d1095fd976936f6fa6e8ee5490a67cbb9111/docs/assets/pearl-study.png" width="100%" alt="Pearl material rendered on a sphere and capsule" /></a><br/><sub>Pearl study</sub></td>
</tr></table>

[**Get NXSG →**](https://nerdrx.github.io/nxsg/#install) · [First material](https://github.com/nerdrx/nxsg/blob/main/docs/QUICK_START.md) · [Source](https://github.com/nerdrx/nxsg)

## zVram

Explore GPU memory beyond local VRAM: Vulkan and HIP allocation tools, lossless idle snapshots, and managed buffers. **Experimental research**, with measured results and explicit compatibility limits.

<a href="https://github.com/nerdrx/zVram"><img src="https://raw.githubusercontent.com/nerdrx/zVram/84d010f852268708f7c38e094d36b5d5361c61df/assets/manager-preview.png" width="100%" alt="zVram manager preview showing memory telemetry and controls for managed applications" /></a>

<sub>Manager preview. Example allocations illustrate the interface; they are not a performance benchmark.</sub>

[**Explore zVram →**](https://github.com/nerdrx/zVram) · [Project website](https://nerdrx.github.io/zVram/)

## Warp

A GPU-native video codec exploring low-latency VR streaming with WiVRn NX. Follow the experiments, measured results, and tradeoffs. **Research prototype; no end-user download yet.**

<a href="https://github.com/nerdrx/nx-warp"><img src="https://raw.githubusercontent.com/nerdrx/nx-warp/88a6ff8bbbadb2e28415e88eadec00ee226944a2/bench/results/90fps-2026-10-05/continuous/zstd-jobs/bundled.png" width="100%" alt="Two matched Warp host packing runs: fixed jobs reduce median time, but the first run has a slower p95 tail" /></a>

<sub>Measured host packing time, lower is better. Fixed jobs improved the mean in both runs; p95 worsened in one. This default-off component experiment does not establish live VR latency. [Method and results](https://github.com/nerdrx/nx-warp/blob/88a6ff8bbbadb2e28415e88eadec00ee226944a2/bench/results/90fps-2026-10-05/continuous/zstd-jobs/README.md).</sub>

[**Explore Warp →**](https://github.com/nerdrx/nx-warp) · [Design paper](https://github.com/nerdrx/nx-warp/blob/main/docs/PAPER.md)

## Novum Xenium

Bring models, tools, projects, and chats together in a self-hosted AI workspace, with desktop and Android companions. Built on Odysseus, with NX improvements to usability, reliability, and integration.

<a href="https://github.com/nerdrx/novum-xenium"><img src="https://raw.githubusercontent.com/nerdrx/novum-xenium/d5dc635c9cc73cc440e2d943388f40f6a974dfd0/assets/branding/workspace-home.png" width="100%" alt="Novum Xenium dashboard with example activity, recent chats, and workspace tools" /></a>

<sub>Your workspace, models, and tools together. Dashboard shown with example activity.</sub>

[**Get started with Novum →**](https://github.com/nerdrx/novum-xenium#get-started) · [Desktop and Android releases](https://github.com/nerdrx/novum-xenium/releases)

## Recall

Local speech transcription, speaker identity, and searchable conversation history for VR and voice chat. Capture starts with the applications you explicitly allow.

<a href="https://github.com/nerdrx/nx-recall"><img src="https://raw.githubusercontent.com/nerdrx/nx-recall/0e876a89ce3d8be1840a590d9979f25bea704fe1/assets/readme/voice-settings.png" width="100%" alt="Recall local voice assistant settings with voice choice and speaking speed controls" /></a>

<sub>Choose a local voice and tune its speaking speed.</sub>

```mermaid
flowchart LR
  A["Allowed audio"] --> B["Local transcription"]
  B --> C["Searchable memory"]
  classDef nx fill:#211335,stroke:#b699ff,color:#ffffff
  class A,B,C nx
```

[**Explore Recall →**](https://github.com/nerdrx/nx-recall) · [Linux download](https://github.com/nerdrx/nx-recall/releases/latest)

## Hub

One place to discover, install, update, and launch the NX apps. Downloads come from GitHub Releases, with checksum and signature verification where available.

<a href="https://github.com/nerdrx/nx-hub"><img src="https://raw.githubusercontent.com/nerdrx/nx-hub/49d001375a087c01e701ef2d823546a2e7cc9e7f/docs/screenshots/launch.png" width="100%" alt="NX Hub launch view with an example multi-app stack" /></a>

<sub>Launch view with an example app stack.</sub>

```mermaid
flowchart LR
  A["GitHub Releases"] --> B["NX Hub"]
  B --> C["Install and update"]
  C --> D["Launch your apps"]
  classDef nx fill:#211335,stroke:#b699ff,color:#ffffff
  class A,B,C,D nx
```

[**Get NX Hub →**](https://github.com/nerdrx/nx-hub#start-here)

---

**Follow the builds.** Follow [@nerdrx](https://github.com/nerdrx), or choose **Watch → Custom → Releases** on a project for new builds. Tried something? Bug reports, screenshots, and specific feedback are welcome in that project's issues.
