# 📚 VLSI / Open-Source Chip Design — Complete Resource List

---

## 📑 Table of Contents

- [🧱 1. PDK & Process Technology](#cat-1)
- [🛠️ 2. EDA Tools & Design Flows](#cat-2)
- [⚙️ 3. RISC-V Cores & SoC Projects](#cat-3)
- [🤖 4. AI/ML Accelerators & Hardware for AI](#cat-4)
- [🔬 5. FPGA Tools, Boards & Projects](#cat-5)
- [📐 6. Analog, RF & Mixed-Signal Design](#cat-6)
- [🎓 7. University Courses & Curricula](#cat-7)
- [🏫 8. Online Courses & Learning Platforms](#cat-8)
- [🧪 9. Hardware Description Languages (HDL) & High-Level Design](#cat-9)
- [🖥️ 10. Simulators, Applets & Visualizers](#cat-10)
- [📦 11. Tapeout Programs & Fabrication Opportunities](#cat-11)
- [🌐 12. Open Hardware Communities & Initiatives](#cat-12)
- [📚 13. Research Groups & Academic Labs](#cat-13)
- [🗂️ 14. Curated Lists & Awesome Collections](#cat-14)
- [📖 15. Books, Articles & Blogs](#cat-15)
- [🔧 16. Dev Tools, Programming & Productivity](#cat-16)
- [🔩 17. Interesting DIY & Embedded Hardware Projects](#cat-17)
- [💬 18. Forums & Community Support](#cat-18)
- [🗃️ 19. Datasets & Research Data](#cat-19)
- [▶️ 20. YouTube Playlists & Videos](#cat-20)

---

<a id="cat-1"></a>
## 🧱 1. PDK & Process Technology

### Skywater 130nm
| Name | URL |
|------|-----|
| Skywater 130nm Installation Guide | https://positivefb.com/skywater-130nm-installation/ |
| Skywater_tools (Install Scripts) | https://github.com/RobertoDiLorenzo/Skywater_tools |
| Skywater PDK Progress Blog | https://positivefb.com/skywater-130nm-pdk-in-progress/ |
| Installing Skywater Tutorial | https://philipwig.com/tutorials/installing-skywater/ |
| Hammer VLSI – Sky130 Tech Notes | https://hammer-vlsi.readthedocs.io/en/stable/Technology/Sky130.html |
| Skywater PDK on SemiWiki Forum | https://semiwiki.com/forum/threads/an-open-source-pdk-for-130nm-process-node.12729/ |
| Reddit – Skywater 130nm Q&A | https://www.reddit.com/r/chipdesign/comments/1ih8nql/ |
| EDAboard – Skywater PDK & Cadence | https://www.edaboard.com/threads/skywater-130nm-pdk-and-cadence.403925/ |
| Gonzaga Univ. VLSI Install Guide | http://web02.gonzaga.edu/faculty/talarico/vlsi/install2.html |
| LELO Temp Sky130A Design | https://github.com/wulffern/lelo_temp_sky130a |
| LELO Temp Python Design Script | https://github.com/wulffern/lelo_temp_sky130a/blob/main/design/LELO_TEMP_SKY130A/LELOTEMP_CMP.py |
| OpenRAM Sky130 Fixes | https://github.com/carloscl03/openram-sky130-fixes |

### IHP & Other PDKs
| Name | URL |
|------|-----|
| IHP Open PDK (BiCMOS SG13G2) | https://github.com/IHP-GmbH/IHP-Open-PDK |
| IHP Open Design Library Docs | https://ihp-open-ip.readthedocs.io/en/latest/ |
| Certificate Course: IHP SG13G2 PDK | https://zerotoasiccourse.com/post/certificate-course-ihp-sg13g2/ |
| IHP OpenROAD i2c-gpio Example | https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts/tree/master/flow/designs/ihp-sg13g2/i2c-gpio-expander |
| GDS2Palace IHP Converter | https://github.com/VolkerMuehlhaus/gds2palace_ihp__sg13g2 |
| Greyhound IHP Design | https://github.com/mole99/greyhound-ihp |
| ICPS2023_5 (Mineda / IHP Design) | https://github.com/mineda-support/ICPS2023_5 |
| OpenECOS ICsprout55 PDK | https://github.com/openecos-projects/icsprout55-pdk |
| FreePDK (NCSU) | https://eda.ncsu.edu/freepdk/ |
| NCSU CDK | https://eda.ncsu.edu/ncsu-cdk/ |
| ASAP7 PDK (GitHub) | https://github.com/The-OpenROAD-Project/asap7 |
| ASAP7 PDK Docs – ASU Engineering | https://asap.asu.edu/ |
| FIR Filter GDS2 Flow (SKY130) | https://github.com/paramsaini87/fir-filter-gds2-flow |
| RISC-V SoC RTL-to-GDSII (SKY130) | https://github.com/paramsaini87/soc-gds2-flow |
| Minimal Fab | https://www.minimalfab.com/en/ |
| MinimalFab Design Contest 2024 | https://codeberg.org/mole99/minimalfab-design-contest-2024 |
| Ngspice SkyWater Notes | https://ngspice.sourceforge.io/applic.html |
| EZ Library – ETH Zurich Standard-Cell Library | https://iip.ethz.ch/ez-library.html |
| Tholin's Own Standard Cell Library (GF180MCU) | https://www.crowdsupply.com/wafer-space/gf180mcu-run-3/updates/a-need-for-speed-tholins-own-standard-cell-library |
---

<a id="cat-2"></a>
## 🛠️ 2. EDA Tools & Design Flows

### Full Flow Environments
| Name | URL |
|------|-----|
| IIC-OSIC-TOOLS (All-in-one Docker) | https://github.com/iic-jku/IIC-OSIC-TOOLS |
| OpenROAD Flow Scripts | https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts |
| Bazel ORFS | https://github.com/The-OpenROAD-Project/bazel-orfs |
| mflowgen (Modular Design Flow) | https://github.com/mflowgen/mflowgen |
| mflowgen Paper (DAC 2022) | https://dl.acm.org/doi/10.1145/3489517.3530633 |
| LibreLane | https://github.com/librelane/librelane |
| AhmedLilah/OpenIC (Open Source VM) | https://github.com/AhmedLilah/OpenIC |
| ACT VLSI Design Tools | https://avlsi.csl.yale.edu/ |
| Open Circuit Design (Magic/Netgen) | http://opencircuitdesign.com/ |
| Cloud-V FPGA Cloud | https://cloud-v.co/ |
| RTL2GDS Demo (enicslabs) | https://github.com/enics-labs/rtl2gds-demo |
| Partcl — GPU Accelerated EDA | https://partcl.com/ |
| OpenChip – Natural-Language to RTL Project | https://github.com/harrrshall/openchip |

### Synthesis & Place-and-Route
| Name | URL |
|------|-----|
| Yosys (Synthesis) | https://github.com/YosysHQ/yosys |
| Yosys FPGA Toolchain | https://github.com/YosysHQ/fpga-toolchain |
| OSS CAD Suite Builds | https://github.com/YosysHQ/oss-cad-suite-build |
| nextpnr (P&R) | https://github.com/YosysHQ/nextpnr |
| yosys-slang (SystemVerilog) | https://github.com/povik/yosys-slang |
| SpyDrNet Physical | https://github.com/ganeshgore/spydrnet-physical |
| OpenFPGA | https://github.com/lnis-uofu/OpenFPGA |
| FABulous (FPGA Fabric) | https://github.com/FPGA-Research/FABulous |
| SynthLC | https://github.com/yaohsiaopid/SynthLC |

### Simulation & Verification
| Name | URL |
|------|-----|
| Verilator + SDL Tutorial | https://projectf.io/posts/verilog-sim-verilator-sdl/ |
| cocotb | https://www.cocotb.org/ |
| riscv-isa-sim (Spike) | https://github.com/riscv-software-src/riscv-isa-sim |
| Logisim Evolution | https://github.com/logisim-evolution/logisim-evolution |
| iverilog | https://github.com/steveicarus/iverilog |
| ZathuraDbg | https://github.com/nicowillis/ZathuraDbg |
| MCUViewer | https://github.com/klonyyy/MCUViewer |
| Vaporview (VSCode Waveform Viewer) | https://github.com/Lramseyer/vaporview |
| PyMTL Tutorial | https://www.csl.cornell.edu/courses/ece5745/ |
| Universal Verification Methodology | https://www.accellera.org/activities/working-groups/uvm |
| Pipelining RISC-V CPU with cocotb | https://www.cocotb.org/ |

### Layout & Physical Design
| Name | URL |
|------|-----|
| GDSFactory Docs | https://gdsfactory.github.io/gdsfactory/ |
| KLayout PEX Plugin | https://github.com/martinjankoehler/klayout-pex |
| GDS3D (3D Layout Viewer) | https://github.com/trilomix/GDS3D |
| Logo to GDS2 | https://github.com/mattvenn/logo-to-gds2 |
| Open-Source ASIC Resources List | https://github.com/mattvenn/awesome-opensource-asic-resources/blob/main/README.md |
| BlenderGDS | https://github.com/aesc-silicon/BlenderGDS |
| Blender-FastHenry | https://github.com/samerps/Blender-FastHenry/ |
| KiCanvas Docs | https://kicanvas.org/ |
| EasyEDA to KiCad (uPesy) | https://github.com/uPesy/easyeda2kicad.py |
| EasyEDA to KiCad (wokwi) | https://github.com/wokwi/easyeda2kicad |
| Atopile | https://github.com/atopile/atopile |
| Espressif KiCad Libraries | https://github.com/espressif/kicad-libraries |
| Circuit2TiKZ (schematic to LaTeX) | https://circuit2tikz.tf.fau.de/ |
| setupEM (EM simulation setup) | https://github.com/VolkerMuehlhaus/setupEM |
| Quickboards | https://quickboards.org/ |
| tscircuit – React for Circuits | https://github.com/tscircuit/tscircuit |
| JLC2KiCad Library | https://github.com/TousstNicolas/JLC2KiCad_lib |
| DAC26 DRC Benchmark | https://github.com/ASU-VDA-Lab/DAC26_DRC_Benchmark |
| M3D Routing Challenge | https://github.com/partcleda/eda-3d-routing-challenge |


### EDA Wikis & Overviews
| Name | URL |
|------|-----|
| EDA Open Source & Free Tools Wiki (SemiWiki) | https://semiwiki.com/eda/ |
| Comprehensive Guide to Installing OSS IC Tools | https://www.viksnewsletter.com/p/a-comprehensive-guide-to-installing-oss-tools-for-icdesign |
| Open Source VLSI Resources | https://vlsiresources.com/opensourcevlsi/ |
| EDA Collection (pkuzjx) | https://github.com/pkuzjx/eda-collection |

---

<a id="cat-3"></a>
## ⚙️ 3. RISC-V Cores & SoC Projects

### Major RISC-V Cores
| Name | URL |
|------|-----|
| Rocket Chip Generator | https://github.com/chipsalliance/rocket-chip |
| Rocket Chip Mirror | https://github.com/riscveval/Rocket-Chip |
| Rocket Chip BAR Page | https://bar.eecs.berkeley.edu/projects/rocket_chip.html |
| Rocket Chip Paper (ASPIRE) | https://aspire.eecs.berkeley.edu/publication/the-rocket-chip-generator/ |
| Rocket Chip Tech Report | https://www2.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-17.pdf |
| VexRiscv (SpinalHDL) | https://github.com/SpinalHDL/VexRiscv |
| PicoRV32 (YosysHQ) | https://github.com/YosysHQ/picorv32 |
| CVA6 (OpenHW Group) | https://github.com/openhwgroup/cva6 |
| CV32E40X | https://github.com/openhwgroup/cv32e40x |
| kianRiscV (Linux SoC) | https://github.com/splinedrive/kianRiscV |
| kianRiscV Linux SoC Branch | https://github.com/splinedrive/kianRiscV/tree/master/linux_socs/kianv_mc_rv32ima_sv32 |
| FazyRV | https://github.com/meiniKi/FazyRV |
| RISC-V Sodor (UCB Educational) | https://github.com/ucb-bar/riscv-sodor |
| RV32I Single-Cycle | https://github.com/Abdul-muheet-ghani/RV32I-Single-Cycle |
| tinyrv (Python RISC-V) | https://github.com/s-holst/tinyrv |
| tinyrv on PyPI | https://pypi.org/project/tinyrv/ |
| ElemRV | https://github.com/aesc-silicon/ElemRV |
| RiscY | https://github.com/Nanousis/RiscY |
| Microwatt (PowerPC) | https://github.com/antonblanchard/microwatt |
| Z80 Open Silicon | https://github.com/rejunity/z80-open-silicon |
| 3-Wide RISC-V OOO Processor | https://github.com/aritramanna/3-Wide-RISC-V-OOO-RV32-IM-Processor |
| rsd (RISC-V Out-of-Order) | https://github.com/rsd-devel/rsd |
| dummy32 | https://github.com/satishashank/dummy32 |

### SoC Platforms
| Name | URL |
|------|-----|
| Cheshire RISC-V SoC (PULP) | https://github.com/pulp-platform/cheshire |
| CROC SoC (PULP) | https://github.com/pulp-platform/croc |
| X-HEEP (EPFL Open Hardware SoC) | https://github.com/esl-epfl/x-heep |
| X-HEEP Project Page | https://www.epfl.ch/labs/esl/research/systems-on-chip/x-heep/ |
| ESP SoC Platform (Columbia) | https://github.com/sld-columbia/esp |
| Columbia ESP Homepage | https://esp.cs.columbia.edu/ |
| OpenTitan (Security Root of Trust) | https://github.com/lowRISC/opentitan |
| OpenTitan Site | https://opentitan.org/ |
| lowRISC Open Silicon Designs | https://lowrisc.org/ |
| Shakti Processor | https://shakti.org.in/ |
| CHIPS Alliance | https://www.chipsalliance.org/ |
| RISCV-HDP (BhattSoham) | https://github.com/BhattSoham/RISCV-HDP |
| RISCV-HDP (navi2311) | https://github.com/navi2311/risc-v-HDP |
| chipyard-micro-learning | https://github.com/lftraining/chipyard-micro-learning |
| nibblecpu | https://github.com/mattvenn/nibblecpu |
| Chipyard Lab | https://ucb-ee290c.github.io/tutorials/chipyard/chipyard-lab/ |
| Chipyard Documentation | https://chipyard.readthedocs.io/en/latest/ |
| Cornell C2S2 Tapeout | https://cornell-c2s2.github.io/ |
| IOb-SoC-Linux | https://github.com/IObundle/soc-linux |

---

<a id="cat-4"></a>
## 🤖 4. AI/ML Accelerators & Hardware for AI

| Name | URL |
|------|-----|
| NVIDIA Deep Learning Accelerator (NVDLA) | https://nvdla.org/ |
| Gemmini (UCB Systolic Array) | https://github.com/ucb-bar/gemmini |
| tiny-gpu (Minimal GPU in Verilog) | https://github.com/adam-maj/tiny-gpu |
| Sapphire GPU (Experimental) | https://github.com/robotman2412/sapphire-gpu |
| ztachip (AI Accelerator) | https://github.com/ztachip/ztachip |
| Eyeriss (MIT) | https://eyeriss.mit.edu/ |
| Timeloop (NVLabs) | https://github.com/NVlabs/timeloop |
| Accelergy | https://github.com/Accelergy-Project/accelergy |
| gem5-Aladdin | https://github.com/harvard-acc/gem5-aladdin |
| ALADDIN | https://github.com/harvard-acc/ALADDIN |
| Intel Neuro-Vectorizer | https://github.com/intel/neuro-vectorizer |
| Autophase (UCB) | https://github.com/ucb-bar/autophase |
| GEM (NVLabs) | https://github.com/NVlabs/GEM |
| AccDNN (IBM) | https://github.com/IBM/AccDNN |
| hls4ml | https://github.com/fastmachinelearning/hls4ml |
| TinyTPU-co | https://github.com/Alanma23/tinytinyTPU-co |
| Google Coral NPU | https://github.com/google-coral/coralnpu |
| NeuroSim | https://github.com/neurosim/NeuroSim |
| SECDA-TFLite | https://github.com/gicLAB/SECDA-TFLite |
| DLAgen (CMU VLSI) | https://github.com/CMU-VLSI/dlagen |
| PARADE ARA Simulator | https://github.com/cdsc-github/parade-ara-simulator |
| TeAAL Compiler (FPSG-UIUC) | https://github.com/FPSG-UIUC/teaal-compiler |
| Fibertree Project | https://github.com/Fibertree-Project/fibertree |
| Accelerator Zoo (FPSG-UIUC) | https://github.com/FPSG-UIUC/accelerator-zoo |
| Kria KV260 Vision AI Kit | https://www.xilinx.com/products/som/kria/kv260-vision-starter-kit.html |
| Etched (Transformer ASIC) | https://www.etched.com/ |
| Catalyst N1 (Neuromorphic) | https://github.com/catalyst-neuromorphic/catalyst-n1 |
| BioFoundation (PULP Bio) | https://github.com/pulp-bio/BioFoundation |
| SensorsINI Chipmunk | https://github.com/SensorsINI/chipmunk |
| CHIPKIT (whatmough) | https://github.com/whatmough/CHIPKIT |
| CS 217: Hardware Accelerators for ML | https://cs217.stanford.edu/ |
| AutoDSE (UCLA VAST) | https://github.com/UCLA-VAST/AutoDSE |
| Auto-Arch Tournament Blog Post | https://github.com/FeSens/auto-arch-tournament/blob/main/docs/auto-arch-tournament-blog-post.md |
| NVCell: Standard Cell Layout in Advanced Technology Nodes with Reinforcement Learning | https://research.nvidia.com/publication/2021-12_nvcell-standard-cell-layout-advanced-technology-nodes-reinforcement-learning |
| Sky130 High-Performance MAC Accelerator | https://github.com/EUB-RN/sky130_high_performance_mac |
| 2D Systolic Array | https://github.com/bodsvei/2D-systolic-array |
| openTPU | https://github.com/FeSens/openTPU |
| MAC Array-based DNN Accelerator | https://github.com/Shingyy/MAC-Array-based-DNN-Accelerator |
| GreenMatrix – FPGA AI Matrix Accelerator | https://github.com/ayanayvleo/GreenMatrix |
| Sky130 High-Performance MAC Accelerator | https://github.com/EUB-RN/sky130_high_performance_mac |

---

<a id="cat-5"></a>
## 🔬 5. FPGA Tools, Boards & Projects

| Name | URL |
|------|-----|
| F4PGA (GCC of FPGAs) | https://f4pga.org/ |
| LiteX (SoC Builder) | https://github.com/enjoy-digital/litex |
| Icestudio | https://icestudio.io/ |
| nextpnr (P&R for FPGAs) | https://github.com/YosysHQ/nextpnr |
| openFPGALoader | https://github.com/trabucayre/openFPGALoader |
| FABulous (FPGA Fabric Gen) | https://github.com/FPGA-Research/FABulous |
| WTFpga (FPGA Tutorial) | https://github.com/esden/WTFpga |
| learn-fpga (BrunoLevy) | https://github.com/BrunoLevy/learn-fpga |
| From Blinker to RISC-V Tutorial | https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/TUTORIALS/FROM_BLINKER_TO_RISCV/README.md |
| RISC-V Pipeline Tutorial | https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/TUTORIALS/FROM_BLINKER_TO_RISCV/PIPELINE.md |
| TinyPrograms (BrunoLevy) | https://github.com/BrunoLevy/TinyPrograms |
| FPGA_ECE8893 (SHARC Lab) | https://github.com/sharc-lab/FPGA_ECE8893 |
| Xilinx Vitis Tutorials | https://github.com/Xilinx/Vitis-Tutorials |
| Xilinx Vitis HLS Examples | https://github.com/Xilinx/Vitis-HLS-Introductory-Examples |
| Icebreaker FPGA Board | https://github.com/icebreaker-fpga/icebreaker |
| Vicharak Shrike-Lite | https://github.com/vicharak-in/shrike-lite |
| Vicharak Shrike FPGA Board | https://github.com/vicharak-in/shrike_fpga |
| VGA Playground | https://vga-playground.com/ |
| fpga4fun | https://www.fpga4fun.com/ |
| 8bitworkshop IDE | https://8bitworkshop.com/ |
| Soan Papdi FPGA | https://github.com/goran-mahovlic/soan-papdi |
| ps1.fpgas.online | https://ps1.fpgas.online/ |
| VSD Squadron FPGA IP SPI | https://github.com/vsdip/vsdsquadron-fpga-ip-spi |
| emulsiV RISC-V Simulator | https://brucedodson.github.io/emulsiV/ |
| Cornell ECE 6775 (FPGA) | https://github.com/cornell-ece6775 |
| GOWIN Semiconductor | https://www.gowinsemi.com/ |
| Soan Papdi FPGA (Pyjama Cafe) | https://pyjamacafe.com/fpga/ |
| openFPGA (Analogue Developer) | https://www.analogue.co/developer |
| Alexey Frunze's SediCi PC on FPGA | https://www.hackster.io/news/alexey-frunze-s-sedici-pc-is-a-16-bit-microcomputer-on-an-fpga-with-a-custom-built-cpu-c0637c1a64ea |
| ps1.fpgas.online (PlayStation FPGA) | https://ps1.fpgas.online/fpgas/ |
| Neural Networks on FPGA | https://www.youtube.com/playlist?list=PLJePd8QU_LYKZwJnByZ8FHDg5l1rXtcIq |

---

<a id="cat-6"></a>
## 📐 6. Analog, RF & Mixed-Signal Design

| Name | URL |
|------|-----|
| OpenFASOC (Analog Generator) | https://github.com/idea-fasoc/OpenFASOC |
| Analog IC Design (SSCS OSE) | https://sscs-ose.github.io/analog/ |
| MOSbius Book | https://mosbius.org/ |
| CASCODELABS | https://cascodelab.com/ |
| GDSFactory | https://gdsfactory.github.io/gdsfactory/ |
| LAYGO3 Web Console | https://laygo3.github.io/ |
| OpenDPD (Power Amplifier Linearizer) | https://github.com/lab-emi/OpenDPD |
| RFIC-TL (ETH IDEAS) | https://github.com/ETH-IDEAS/RFIC-TL |
| Awesome Photonics | https://github.com/joamatab/awesome_photonics |
| AnalogHub | https://analoghub.io/ |
| Stanford DragonPHY2 | https://github.com/StanfordVLSI/dragonphy2 |
| msdsl (Mixed-Signal DSL) | https://github.com/sgherbst/msdsl |
| anasymod (Mixed-Signal Sim) | https://github.com/sgherbst/anasymod |
| cicpy (Analog Circuit Synthesis) | https://github.com/wulffern/cicpy |
| pade (Analog Design) | https://github.com/fredrief/pade |
| Open RF Simulation Post (LinkedIn) | https://www.linkedin.com/posts/katerinagalitskaya_every-open-source-rf-simulation-activity-7305150570770657280-VcOT |
| ordec (TU Berlin) | https://github.com/tub-msc/ordec |
| HWTB RADAR 150GHz Design | https://github.com/EngGhaith/mWATTBAT_RADAR_150GHz_TO_July2025 |
| 140GHz Antenna Design | https://github.com/JKU4Ghaith/TO_July2025_140GHzAntenna |
| openWSPR | https://github.com/openwspr/openwspr |
| Tiny WSPR Encoder | https://github.com/Reverea/Tiny-WSPR-Encode |
| Qiskit Metal (Quantum Hardware) | https://github.com/qiskit-community/qiskit-metal |
| LELO_TEMP_SKY130A | https://analogicus.com/lelo_temp_sky130a/ |
| From Schematic to Silicon: Mixed-Signal IC Design in Open-Source Flows | https://indico.cern.ch/event/1680490/ |
| CERN KiCad Libraries | https://gitlab.com/ohwr/cern-kicad-libs |
| IHP SG13G2 AMS Chip Design Tutorial | https://iic-jku.github.io/ihp-sg13g2-ams-chip-template/index.html |
| IHP SG13G2 AMS Chip Design Template | https://github.com/iic-jku/ihp-sg13g2-ams-chip-template |

---

<a id="cat-7"></a>
## 🎓 7. University Courses & Curricula

### UC Berkeley
| Name | URL |
|------|-----|
| CS 61C Spring 2025 | https://cs61c.org/sp25/ |
| EECS 16A Fall 2025 | https://eecs16a.org/ |
| EECS 16B Spring 2024 | https://eecs16b.org/ |
| EECS 151 Tapeout (151T) | https://151tapeout.berkie.ee/ |
| EECS 151 Course Page | https://www2.eecs.berkeley.edu/Courses/EECS151/ |
| ASIC Labs (EECS150) | https://github.com/EECS150/asic_labs |
| New Silicon Initiative (NSI) – Berkeley | https://eecs.berkeley.edu/academics/new-silicon-initiative-nsi/ |
| Berkeley EECS Homepage | https://www2.eecs.berkeley.edu/ |
| Berkeley Course Captures Archive | https://wiki.archiveteam.org/index.php/UC_Berkeley_Course_Captures |
| Berkeley Library Affordable Resources | https://guides.lib.berkeley.edu/affordable-resources |
| EE 105: Microelectronic Devices | https://inst.eecs.berkeley.edu/~ee105/ |
| UCB-BAR Gemmini | https://github.com/ucb-bar/gemmini |
| UCB Chipyard Lab Tutorial | https://ucb-ee290c.github.io/tutorials/chipyard/chipyard-lab/ |

### Cornell University
| Name | URL |
|------|-----|
| ECE 4750 Computer Architecture | https://www.csl.cornell.edu/courses/ece4750/ |
| ECE 5745 Complex Digital ASIC Design | https://www.csl.cornell.edu/courses/ece5745/ |
| Cornell ECE6745 Repos | https://github.com/cornell-ece6745 |
| Cornell ECE5745 Repos | https://github.com/cornell-ece5745 |
| Cornell ECE5745 Repositories | https://github.com/orgs/cornell-ece5745/repositories |
| Cornell C2S2 Tapeout Team | https://cornell-c2s2.github.io/ |
| HeteroCL (Cornell Zhang Lab) | https://github.com/cornell-zhang/heterocl |
| ECE510 Challenges | https://github.com/nkanderson/ECE510-challenges |
| Cornell VLSI (Introduction) | https://www.csl.cornell.edu/ |
| Cornell Custom Silicon Systems – Chip Gallery | https://www.c2s2.dev/chip-gallery |
| Cornell Virtual Workshop – Multithreading | https://cvw.cac.cornell.edu/parallel/memory-access/multithreading |

### MIT
| Name | URL |
|------|-----|
| 6.375 Complex Digital Systems (2016) | https://csg.csail.mit.edu/6.375/6_375_2016_www/handouts.html |
| 6.375 Complex Digital Systems (2019) | https://csg.csail.mit.edu/6.375/ |
| Nand2Tetris | https://www.nand2tetris.org/ |
| Street-Fighting Mathematics (OCW) | https://ocw.mit.edu/courses/18-098-street-fighting-mathematics/ |
| 6.11 Introductory Digital Systems Laboratory | https://web.mit.edu/6.111/www/f2016/ |
| Missing Semester 2026 – Course Shell | https://missing.csail.mit.edu/2026/course-shell/ |

### Stanford
| Name | URL |
|------|-----|
| EE372 Design Projects in VLSI II | https://priyanka-raina.github.io/ee372-spring2022/ |
| CS 217: Hardware Accel. for ML | https://cs217.stanford.edu/ |
| Stanford VLSI Research Group | https://vlsi.stanford.edu/research |
| Stanford STORM Genie | https://storm.genie.stanford.edu/ |
| CS149 – Parallel Computing | https://gfxcourses.stanford.edu/cs149/fall25 |
| CS149 – Parallel Computing | https://gfxcourses.stanford.edu/cs149/fall25/lecture/gpuarch/ |


### Carnegie Mellon University
| Name | URL |
|------|-----|
| 15-418/15-618 – Parallel Computer Architecture and Programming | https://www.cs.cmu.edu/~418/ |

### Columbia University
| Name | URL |
|------|-----|
| EE 6350 Spring 2025 (VLSI Lab) | https://www.ee.columbia.edu/~kinget/EE6350_S25/ |
| EE 6350 Spring 2024 | https://www.ee.columbia.edu/~kinget/EE6350_S24/ |
| EE 6350 Spring 2023 | https://www.ee.columbia.edu/~kinget/EE6350_S23/ |
| CSEE E6861y – CAD of Digital Systems | https://www.cs.columbia.edu/~sedwards/classes/2022/6861y-spring/ |
| ESP (Columbia SLD Lab) | https://github.com/sld-columbia/esp |

### Other Universities
| Name | URL |
|------|-----|
| ECE 425 – Intro to VLSI (Univ. of Utah) | https://ece.utah.edu/ |
| ECE 559 MOS VLSI Design | https://www.ece.ncsu.edu/ |
| VLSI Class (Jacob Abraham – UT Austin) | http://users.ece.utexas.edu/~abraham/vlsi/ |
| Rice ELEC 522 Fall 2023 | https://elec522.rice.edu/ |
| CS 3220 Processor Design | https://cs3220.github.io/ |
| EE3082 Digital Electronics Lab | https://www.ece.nus.edu.sg/stfpage/elelg/EE3082/ |
| EE6321 Advanced Digital ICs | https://ee6321.ece.tamu.edu/ |
| Index of ECE 643 (UWM) | http://cs.uwm.edu/~jhoe/course/ece643/ |
| CURIE Academy (IoT) | https://curie.stanford.edu/ |
| CSE 599s – HW/SW Co-Opt for ML | https://ucsd-cse-599s.github.io/ |
| UCLA Spring 2024 ECE209AS | https://github.com/UCLAEEProfThan/UCLA_Spring2024_ECE209AS_AI_on_chip |
| SoC Labs | https://soclabs.org/ |
| Polimi Electronics Engineering | https://github.com/polimi-vlsi/electronics |
| R. S. Ashwin Kumar Teaching | https://ashwinkumar.info/teaching |
| EFCL Winter School 2026 | https://pulp-platform.org/efclwinter2026/ |
| Gives orientation to EE students - students | https://www.chipschool.org/home/students |
| CS 179: GPU Programming | https://courses.cms.caltech.edu/cs179/ |
| ECE 408 – Applied Parallel Programming | https://courses.grainger.illinois.edu/ece408/su2026/ |
| CIS 565 – GPU Programming and Architecture | https://cis565-fall-2017.github.io/ |

---

<a id="cat-8"></a>
## 🏫 8. Online Courses & Learning Platforms

| Name | URL |
|------|-----|
| Zero to ASIC Course Content | https://www.zerotoasiccourse.com/course_content/ |
| Tiny Tapeout (Learning Program) | https://tinytapeout.com/ |
| Makerchip (TL-Verilog IDE) | https://www.makerchip.com/ |
| TL-Verilog (Redwood EDA) | https://www.redwoodeda.com/tl-verilog |
| QuickSilicon – 21 Days of RTL | https://quicksilicon.in/course/21daysofrtl |
| FOSSEE (IIT Bombay) | https://fossee.in/ |
| TinyMLedu | https://tinyml.seas.harvard.edu/ |
| Open-EDA Course (asinghani) | https://github.com/asinghani/open-eda-course |
| os-chip-design Introduction | https://github.com/os-chip-design/chip-design-intro |
| nanoHUB Nanotechnology Education | https://nanohub.org/ |
| SiliWiz – Learn Semiconductor Basics | https://app.siliwiz.com/ |
| HarveyMuddX Digital Design (edX) | https://www.edx.org/ |
| HarveyMuddX Computer Architecture (edX) | https://www.edx.org/ |
| Arm Online Courses (Coursera) | https://www.coursera.org/partners/arm |
| Arm Education (edX) | https://www.edx.org/learn/computer-architecture/arm-education-computer-architecture-essentials-on-arm |
| Arm Education Kits | https://www.arm.com/resources/education/education-kits |
| Arm Books & Resources | https://www.arm.com/resources/education/books |
| Ansys Training | https://www.ansys.com/training-center/course-catalog |
| Ansys Innovation Courses | https://innovationspace.ansys.com/courses/ |
| Ansys Academic Resources | https://www.ansys.com/academic/learning-resources |
| MATLAB/Simulink Training | https://matlabacademy.mathworks.com/ |
| IITBombayX: LaTeX Course (edX) | https://www.edx.org/learn/latex/iit-bombay-latex-for-students |
| Chipshub Courses | https://chipshub.io/courses |
| Chipshub Tools | https://chipshub.io/tools |
| Learn with Shakti | https://shakti.org.in/learn_with_shakti/intro.html |
| Codecademy | https://www.codecademy.com/ |
| Computation Structures (MIT OCW) | https://computationstructures.org/ |
| CS294/194-280 LLM Agents (Berkeley) | https://llmagents-learning.org/ |
| Cadence Academic Network | https://www.cadence.com/en_US/home/company/academic-network.html |
| NIEIT (India) | https://www.nielit.gov.in/ |
| UNIC-CASS (IEEE CASS) | https://ieee-cas.org/universalization-ic-design-cass-unic-cass |
| LLMLift + Autocomp Tutorial - ASPLOS 2026 | https://charleshong3.github.io/research/asplos2026-tutorial/ |
| UNIC-CASS Home | https://unic-cass.github.io/ |
| Applied Accelerated Artificial Intelligence | https://www.youtube.com/playlist?list=PLyqSpQzTE6M9LibNqhhCYLDvfVGhcRDN5 |
| Parallel Programming for FPGAs – Projects and Labs | https://pp4fpgas.readthedocs.io/en/latest/ |
| Parallel Programming for FPGAs | https://kastner.ucsd.edu/hlsbook/ |
| CS231n – Deep Learning for Computer Vision | https://cs231n.github.io/convolutional-networks/ |
| Machine Learning Systems – Volume I Lecture Slides | https://mlsysbook.ai/slides/vol1.html |

---

<a id="cat-9"></a>
## 🧪 9. Hardware Description Languages (HDL) & High-Level Design

| Name | URL |
|------|-----|
| SpinalHDL | https://github.com/SpinalHDL/SpinalHDL |
| MyHDL | https://www.myhdl.org/ |
| Spade HDL | https://spade-lang.org/ |
| TL-Verilog Projects (TL-X org) | https://github.com/TL-X-org/TL-V_Projects |
| ROHD (Intel – Dart-based HDL) | https://intel.github.io/rohd-website/ |
| HeteroCL (Python-based HLS) | https://github.com/cornell-zhang/heterocl |
| Halide-to-Hardware (Stanford AHA) | https://github.com/StanfordAHA/Halide-to-Hardware |
| Genesis2 (Stanford VLSI) | https://github.com/StanfordVLSI/Genesis2 |
| CIRCT (LLVM/MLIR for HW) | https://github.com/llvm/circt |
| MLIR | https://mlir.llvm.org/ |
| Apache TVM | https://tvm.apache.org/ |
| TVM-VTA | https://github.com/apache/tvm-vta |
| FIRRTL – Adept Lab UCB | https://adept.eecs.berkeley.edu/projects/firrtl/ |
| Leros (Accumulator Machine HDL) | https://github.com/leros-dev/leros |
| HLSF Factory (SHARC Lab) | https://github.com/sharc-lab/HLSFactory |
| GNN Builder (SHARC Lab) | https://github.com/sharc-lab/gnn-builder |
| LightningSim (SHARC Lab) | https://github.com/sharc-lab/LightningSim |
| Designing a Processor in Bluespec | https://svr-informal.cl.cam.ac.uk/wiki/display/BluespecEd/ |
| PandA-bambu (HLS) | https://github.com/ferrandi/PandA-bambu |
| open-logic | https://github.com/open-logic/open-logic |
| Awesome HDL | https://github.com/drom/awesome-hdl |
| HDL Awesome List | https://github.com/hdl/awesome |
| XLS Playground (Google Colab) | https://colab.research.google.com/gist/proppy/5ca7ad39f7c72464c5f667adf11100eb/xls-playground-conda.ipynb |
| Spacely Docs | https://github.com/SpacelyProject/spacely-docs |

---

<a id="cat-10"></a>
## 🖥️ 10. Simulators, Applets & Visualizers

| Name | URL |
|------|-----|
| Falstad Circuit Simulator | https://www.falstad.com/circuit/ |
| Ripes RISC-V Simulator | https://ripes.me/ |
| Ripes GitHub | https://github.com/mortbopet/Ripes |
| emulsiV (RISC-V Minimal Simulator) | https://brucedodson.github.io/emulsiV/ |
| RISC-V CPU Visualizer | https://mostlykiguess.github.io/RISC-V-Processor-Implementation/ |
| VisuAlgo (Algorithm Visualizer) | https://visualgo.net/en |
| Data Structures Viz (USFCA) | https://www.cs.usfca.edu/~galles/visualization/Algorithms.html |
| Logicly (Logic Gate Simulator) | https://logic.ly/ |
| 8bitworkshop Verilog IDE | https://8bitworkshop.com/ |
| VGA Playground | https://vga-playground.com/ |
| Stixu Stick Diagrammer | https://stixu.io/ |
| NN Visualizer (VLSI System Design) | https://nn-visualizer.vlsisystemdesign.com/ |
| Spade Playground | https://spade-lang.org/playground/ |
| Discrete 8-Bit ALU (Interactive 3D) | https://tmarhguy.com/ |
| 8-bit ALU GitHub | https://github.com/tmarhguy/8bit-discrete-transistor-alu |
| LeetGPU (GPU Programming Platform) | https://leetgpu.com/ |
| Velxio | https://velxio.dev/ |
| Cirkit Designer IDE | https://app.cirkitdesigner.com/project |
| Velxio Article (CNX Software) | https://www.cnx-software.com/2026/04/04/velxio-open-source-self-hosted-arduino-raspberry-pi-and-esp32-simulator/ |
| HiEQ – Chip Layout & Dieshot Gallery | https://hieq-home404.pages.dev/#/layout |

---

<a id="cat-11"></a>
## 📦 11. Tapeout Programs & Fabrication Opportunities

| Name | URL |
|------|-----|
| Tiny Tapeout | https://tinytapeout.com/ |
| Tiny Tapeout 9 | https://zerotoasiccourse.com/post/tinytapeout09/ |
| ttsky25a-tinyQV | https://github.com/TinyTapeout/ttsky25a-tinyQV |
| Chipalooza Projects (Set 1) | https://github.com/RTimothyEdwards/chipalooza_projects_1 |
| Chipalooza Projects (Set 2) | https://github.com/RTimothyEdwards/chipalooza_projects_2 |
| tt07-bep-decode | https://github.com/DusterTheFirst/tt07-bep-decode |
| Baochip-1x | https://github.com/baochip/baochip-1x |
| Dabao Eval Board for Baochip-1x | https://github.com/baochip/dabao |
| Minimal Fab | https://www.minimalfab.com/en/ |
| MinimalFab Design Contest 2024 | https://codeberg.org/mole99/minimalfab-design-contest-2024 |
| UofT ASIC Team – IC Hackathon | https://uoftasic.com/ |
| OpenSemi Open-Source HW (IIT Bengaluru) | https://opensemi.iitb.ac.in/ |
| FSiC2025 – Open Silicon Conference | https://wiki.f-si.org/index.php?title=FSiC2025 |
| MLCAD 2025 Drive | https://drive.google.com/drive/folders/1mlcad2025 |
| Designing Silicluster Blog | https://www.electronicdesign.com/technologies/analog/article/55302523/ |
| Tiny Tapeout Personal Story | https://teaandtechtime.com/designing-my-very-own-asic-with-tiny-tapeout/ |
| A-Core GitLab | https://gitlab.com/a-core |
| enicslabs RTL2GDS Demo | https://github.com/enics-labs/rtl2gds-demo |
| ASIC Design (Akash-Perla) | https://github.com/Akash-Perla/ASIC-Design |
| ASIC Books & Resources (LinkedIn) | https://www.linkedin.com/pulse/asic-books-resources-alan-saw/ |
| Open Quantum Design | https://openquantumdesign.org/ |
| Berkeley Quantum Chip Course | https://ciqc.berkeley.edu/ |
| UC Berkeley EE290 (Superconducting QC) | https://inst.eecs.berkeley.edu/~ee290/ |
| Dabao Evaluation Board for Baochip-1x (Crowd Supply) | https://www.crowdsupply.com/baochip/dabao |
| Open Quantum Design (GitHub Org) | https://github.com/OpenQuantumDesign |
| ttSky – CRYPTOGRAPHY DESTROYER OMEGA INFINITY | https://github.com/PolloXDDD/ttsky-CRYPTOGRAPHY-DESTROYER-OMEGA-INFINITY |

---

<a id="cat-12"></a>
## 🌐 12. Open Hardware Communities & Initiatives

| Name | URL |
|------|-----|
| Open Compute Project | https://www.opencompute.org/ |
| CHIPS Alliance | https://www.chipsalliance.org/ |
| CHIPS Alliance Silicon Notebooks | https://github.com/chipsalliance/silicon-notebooks |
| FOSSi Foundation | https://fossi-foundation.org/ |
| FOSSi GSoC 2025 Ideas | https://fossi-foundation.org/gsoc/gsoc25-ideas |
| FOSSi Element Chat | https://element.fossi-chat.org/ |
| Open Hardware Academy | https://www.openhardware.academy/01_Welcome.html |
| Gathering for Open Science Hardware | https://openhardware.science/ |
| OpenHardware.io | https://www.openhardware.io/ |
| OHO Wiki | https://en.oho.wiki/wiki/Home |
| lowRISC Open Source Silicon | https://lowrisc.org/ |
| PULP Platform | https://pulp-platform.org/ |
| PULP FAQs | https://pulp-platform.org/faq.html |
| SwissChips Education | https://www.swisschips.ethz.ch/education-outreach.html |
| Hacker Fab (CMU) | https://hackerfab.ece.cmu.edu/ |
| Hacker Fab IITB | https://hackerfab-iitb.notion.site/HackerFab-IITB-2552a6a9c8098005a80ec47195a01c70 |
| Hacker Fab Docs | https://docs.hackerfab.org/ |
| Arm Semiconductor Education Alliance | https://newsroom.arm.com/news/semiconductor-education-alliance |
| Siemens Graduate Program | https://www.siemens.com/global/en/company/jobs/students.html |
| Arm Graduate Program | https://careers.arm.com/graduates |
| Cadence Community | https://community.cadence.com/ |
| Linux Foundation Projects | https://www.linuxfoundation.org/projects |
| Open Platform for Enterprise AI (OPEA) | https://github.com/opea-project |
| Open Hardware Repository | https://ohwr.org/ |
| IEEE SSCS Open-Source Ecosystem – Code-a-Chip | https://github.com/sscs-ose/sscs-ose-code-a-chip.github.io |

---

<a id="cat-13"></a>
## 📚 13. Research Groups & Academic Labs

| Name | URL |
|------|-----|
| UCB Adept Lab (FIRRTL, Chipyard) | https://adept.eecs.berkeley.edu/ |
| Adept Lab Projects | https://adept.eecs.berkeley.edu/projects/ |
| BAIR (Berkeley AI Research) | https://bair.berkeley.edu/ |
| BAIR Software Resources | https://bair.berkeley.edu/resources/software |
| ASPIRE Lab (Berkeley) | https://aspire.eecs.berkeley.edu/ |
| Krste Asanović Homepage | https://people.eecs.berkeley.edu/~krste/ |
| Krste Asanović Videos | https://people.eecs.berkeley.edu/~krste/videos/ |
| Stanford VLSI Group | https://vlsi.stanford.edu/ |
| AHA Lab (Stanford) | https://aha.stanford.edu/ |
| AHA Software | https://aha.stanford.edu/resources/aha-software |
| SHARC Lab (Georgia Tech) | https://sharclab.ece.gatech.edu/ |
| ETH VLSI Wiki | https://vlsi.ethz.ch/wiki/Main_Page |
| iis-projects (ETH Zurich) | https://iis-projects.ee.ethz.ch/ |
| UCLA VAST Software | https://vast.cs.ucla.edu/software |
| BeBOP (Berkeley Benchmarks & Optimization) | https://bebop.cs.berkeley.edu/ |
| Design Automation Lab | https://www.eda.ee.ucla.edu/ |
| Cornell Zhang Lab | https://zhang.ece.cornell.edu/ |
| Columbia SLD Lab | https://sld.cs.columbia.edu/ |
| SODA Benchmarks (PNNL) | https://github.com/pnnl/soda-benchmarks |
| Ptah (Secure Edge-AI) | https://ptah-project.org/ |
| WDDSA 2023 Workshop | https://xscale.ece.cmu.edu/wddsa/ |
| Sipahigil Lab (Berkeley Quantum) | https://sipahigillab.berkeley.edu/ |
| Microwatt Design Challenge | https://github.com/Lefteris-B/microwatt_design_challenge |

---

<a id="cat-14"></a>
## 🗂️ 14. Curated Lists & Awesome Collections

| Name | URL |
|------|-----|
| Awesome Open-Source Hardware | https://github.com/aolofsson/awesome-opensource-hardware |
| Awesome Semiconductor Startups | https://github.com/aolofsson/awesome-semiconductor-startups |
| Awesome Open-Source ASIC Resources | https://github.com/mattvenn/awesome-opensource-asic-resources/blob/main/README.md |
| Awesome Electronics (Kitspace) | https://github.com/kitspace/awesome-electronics |
| Awesome HDL (drom) | https://github.com/drom/awesome-hdl |
| HDL Awesome List | https://github.com/hdl/awesome |
| EDA Collection (pkuzjx) | https://github.com/pkuzjx/eda-collection |
| Awesome Photonics | https://github.com/joamatab/awesome_photonics |
| Computer Architecture & Systems Resources | https://github.com/rajesh-s/computer-architecture-and-systems-resources |
| Awesome Math Books | https://github.com/valeman/Awesome_Math_Books |
| Awesome Creative Technology | https://github.com/j0hnm4r5/awesome-creative-technology |
| Sindresorhus Awesome (Meta-list) | https://github.com/sindresorhus/awesome |
| Build Your Own X | https://github.com/codecrafters-io/build-your-own-x |
| RISCV Cores List | https://github.com/riscvarchive/riscv-cores-list |
| RISC-V Learn (Official) | https://github.com/riscv/learn |
| RISCV Educational Materials | https://github.com/riscvarchive/educational-materials |
| ASM Lessons (FFmpeg) | https://github.com/FFmpeg/asm-lessons |
| CS249r Book (Harvard Edge) | https://github.com/harvard-edge/cs249r_book |
| Open RISC-V Cores (LibHunt) | https://www.libhunt.com/l/risc-v |
| Guitar Specs (gitfrage) | https://github.com/gitfrage/guitarspecs |
| System AI Prompts (x1xhlol) | https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools |

---

<a id="cat-15"></a>
## 📖 15. Books, Articles & Blogs

| Name | URL |
|------|-----|
| From Code to Chip (Book) | https://books.google.co.in/books?id=qtM9EQAAQBAJ |
| From Code to Chip (Blog Review) | https://sedemos.blogspot.com/2025/01/book-from-code-to-chip.html |
| ASIC Books & Resources (LinkedIn) | https://www.linkedin.com/pulse/asic-books-resources-alan-saw/ |
| DIY Silicon – Design Your Own Chips | https://makezine.com/article/electronics/diy-silicon-design-your-own-chips/ |
| Open-Source IC Design Flow for RISC-V | https://www.mehmetburakaykenar.com/open-source-ic-design-flow-for-an-open-source-risc-v-core/444/ |
| Strategic Thinking on Open-Source PDK | https://jun1okamura.medium.com/strategic-thinking-on-open-source-pdk-5fb8f7522122 |
| Semiconductor Costs Overview | https://github.com/jun1okamura/A-Qualitative-Overview-of-Semiconductor-Costs |
| Can You Vibe Your Way Through Chip Design? | https://www.viksnewsletter.com/p/can-you-vibe-your-way-through-chip-design |
| Antmicro – Auto Clock Gating in OpenROAD | https://antmicro.com/blog/2025/07/automatic-clock-gating-in-openroad/ |
| Promise of Open Source EDA (Video) | https://youtu.be/OmEbzRp_NGg |
| Putting the "You" in CPU | https://cpu.land/ |
| How is Data Stored | https://www.makingsoftware.com/chapters/how-is-data-stored |
| CHIP-8 Emulator Guide (C++) | https://austinmorlan.com/posts/chip8_emulator/ |
| Human Language to Analog Layout (ML-CAD 2024) | https://dl.acm.org/doi/10.1145/3670474.3685963 |
| Installing OSS IC Tools (Vik's Newsletter) | https://www.viksnewsletter.com/p/a-comprehensive-guide-to-installing-oss-tools-for-icdesign |
| Designing Silicluster (Electronic Design) | https://www.electronicdesign.com/technologies/analog/article/55302523/ |
| Understanding Deep Learning (Book) | https://udlbook.github.io/udlbook/ |
| λ-2D Drawing as Programming (MIT Media Lab) | https://www.media.mit.edu/projects/lambda-2d/ |
| FireBox – Warehouse-Scale Computer (USENIX) | https://www.usenix.org/conference/fast14/technical-sessions/presentation/firebox |
| El Correo Libre Issue 92 | https://elcorreolibre.com/ |
| ECG monitoring | https://bowald.com/ecg/ |
| Open Source Rotary Cellphone | https://www.justine-haupt.com/rotarycellphone/ |
| Velxio – Open-Source Arduino/Raspberry Pi/ESP32 Simulator (CNX Software) | https://www.cnx-software.com/2026/04/04/velxio-open-source-self-hosted-arduino-raspberry-pi-and-esp32-simulator/ |
| From Taylor Series to Silicon – ROM-less CORDIC | https://bitbangingbytes.substack.com/p/from-taylor-series-to-silicon-building?r=d0mv1&utm_campaign=post&utm_medium=web |
| Dissecting the Apple M1 GPU | https://alyssarosenzweig.ca/blog/asahi-gpu-part-n.html |
| Claude – Asynchronous I2C Circuit Implementation | https://qiita.com/jun1okamura/items/928e6e1464e75a68b394e6 |
| Advanced Skylake Deep Dive – Microarchitecture | https://www.janestreet.com/tech-talks/microarchitecture/ |
| Build a Tapeout-Ready Open-Source AMS Chip with one make Command | https://www.reddit.com/r/chipdesign/comments/1vf4fne/build_a_tapeoutready_opensource_ams_chip_with_one/?rdt=56261 |
| Tardigrade – ASIC Synthesis for the Age of AI-Driven Chip Design | https://www.zeroasic.com/blog/tardigrade_launch |
| Verilogで学ぶCPU自作入門 | https://speakerdeck.com/uyuki234/verilog-de-manabu-cpu-jisaku-nyuumon |
| Modern Microprocessors – A 90-Minute Guide | https://www.lighterra.com/papers/modernmicroprocessors/ |
| IOb-SoC-Linux – Open-Source Linux-Capable RISC-V SoC Template | https://www.preprints.org/manuscript/202609.1343 |
| A³ – Agentic Approaches to Architecture | https://agentic-arch.org/index.html |

---

<a id="cat-16"></a>
## 🔧 16. Dev Tools, Programming & Productivity

| Name | URL |
|------|-----|
| Git | https://git-scm.com/ |
| Oh My Git! (Interactive Git Tutorial) | https://ohmygit.org/ |
| A Grip on Git | https://agripongit.vincenttunru.com/ |
| Processing (Creative Coding) | https://processing.org/ |
| Geany IDE | https://www.geany.org/ |
| 21st.dev (AI Coding) | https://21st.dev/ |
| React Bits | https://reactbits.dev/ |
| OpenCode AI Coding Agent | https://opencode.ai/ |
| NVIDIA NIM (Llama 3.1 Nemotron) | https://build.nvidia.com/nvidia/llama-3_1-nemotron-70b-instruct |
| NVIDIA Nemotron | https://www.nvidia.com/en-us/ai/nemotron/ |
| n8n Workflows (Zie619) | https://github.com/Zie619/n8n-workflows |
| Awesome n8n Templates | https://github.com/enescingoz/awesome-n8n-templates |
| n8n Community Workflows | https://n8n.io/workflows/ |
| Anthropic Prompt Engineering Tutorial | https://github.com/anthropics/prompt-eng-interactive-tutorial |
| LeetCode Company-wise Problems | https://github.com/liquidslr/leetcode-company-wise-problems |
| Math & Science Video Lectures | https://github.com/Developer-Y/math-science-video-lectures |
| New Tools for Building Agents (OpenAI) | https://openai.com/index/new-tools-for-building-agents/ |
| autoresearch | https://github.com/karpathy/autoresearch |
| Microchip MPLAB XC Compilers & Machine Learning Development Suite | https://www.microchip.com/en-us/about/news-releases/products/microchip-expands-developer-access-with-free-mplab-xc-compilers-and-mplab-machine-learning-development-suite |

---

<a id="cat-17"></a>
## 🔩 17. Interesting DIY & Embedded Hardware Projects

| Name | URL |
|------|-----|
| Flipper One MCU Firmware | https://github.com/flipperdevices/flipperone-mcu-firmware |
| Tactility (ESP32 OS) | https://github.com/ByteWelder/Tactility |
| Mecha Comet (Open Linux Handheld) | https://www.kickstarter.com/projects/mecha-systems/mecha-comet |
| OpenEarable (Open AI Earphones) | https://www.openearable.de/ |
| Open Book E-Reader | https://github.com/joeycastillo/The-Open-Book |
| Xous Microkernel | https://github.com/betrusted-io/xous-core |
| PCIe3 Hub (Raspberry Pi 5) | https://github.com/will127534/PCIe3_Hub |
| Watchy (Open Source Smartwatch) | https://github.com/sqfmi/Watchy/ |
| Sonar Watch | https://github.com/drpykachu/Sonar-Watch |
| ECG PCB Business Card | https://github.com/SiBowald/ecg-pcb-business-card |
| Raspberry Pi Zero OpenClaw | https://github.com/sebastianvkl/pizero-openclaw |
| Pi Zero PCB | https://github.com/piecol/CM5_MINIMA_REV3 |
| RPI Dev (Sector07) | https://github.com/sector07-dev/RPI_DEV |
| SwordOfSecrets | https://github.com/gili-yankovitch/SwordOfSecrets |
| Flip Card | https://github.com/Nicholas-L-Johnson/flip-card |
| IKEA 3D Model Download Button | https://github.com/apinanaivot/IKEA-3D-Model-Download-Button |
| weathr (Weather App) | https://github.com/veirt/weathr |
| BoxLambda (FPGA SoC) | https://epsilon537.github.io/boxlambda/ |
| Montana Mini Computer MTMC-16 | https://mtmc.cs.montana.edu/ |
| CircuitMess | https://www.circuitmess.com/ |
| OpenRTX (Open Radio Firmware) | https://github.com/OpenRTX/OpenRTX |
| M17 libm17 | https://github.com/M17-Project/libm17 |
| M17 Nokia 3310 Design | https://github.com/M17-Project/M17_3310 |
| M17 3310 Firmware | https://github.com/M17-Project/M17_3310-fw |
| Panomicron | https://www.panomicron.com/ |
| Tangara Music Player | https://www.cooltech.zone/tangara |
| Tillitis Security Key | https://www.tillitis.se/ |
| Velxio (Open Source Arduino Sim) | https://velxio.com/ |
| macless-haystack | https://github.com/dchristl/macless-haystack |
| bitchat | https://github.com/jackjackbits/bitchat |
| OpenGhost | https://github.com/xanderchinxyz/OpenGhost |
| tensor.h (Tiny Tensor Lib in C) | https://github.com/apoorvnandan/tensor.h |
| WiFi DensePose | https://github.com/ruvnet/wifi-densepose |
| video2ascii | https://github.com/elijah0528/video2ascii |
| Takahe | https://github.com/Zaneham/takahe |
| Kode Dot – Programmable Pocket Device | https://kode.diy/ |

---

<a id="cat-18"></a>
## 💬 18. Forums & Community Support

| Name | URL |
|------|-----|
| EDAboard Forum | https://www.edaboard.com/ |
| Designer's Guide Community Forum | https://designers-guide.org/forum/ |
| Cadence Community Forum | https://community.cadence.com/ |
| FOSSi Element Chat | https://element.fossi-chat.org/ |
| Open On-Chip Debugger (OpenOCD) | https://openocd.org/ |
| ROHD (Intel Hardware in Dart) | https://intel.github.io/rohd-website/ |
| RISCV.org | https://riscv.org/ |
| libre-soc | https://libre-soc.org/ |
| Keystone Framework | https://keystone-enclave.org/ |

---

<a id="cat-19"></a>
## 🗃️ 19. Datasets & Research Data

| Name | URL |
|------|-----|
| SETH-TAMU FreeSet Dataset (HuggingFace) | https://huggingface.co/datasets/SETH-TAMU/FreeSet-V1.0-LabUse |
| Chipshub Free Courses & Textbooks | https://chipshub.io/ |
| ASIC Design Resources Notion | https://gold-barberry-def.notion.site/ |
| ML Practical Use Cases (650 Companies) | https://github.com/mallahyari/ml-practical-usecases |
| ADC Survey | https://www.adcsurvey.com/ |
| The Silicon Zoo | https://siliconzoo.org/ |
| CleanCadencePlots (Google Drive) | https://drive.google.com/drive/folders/CleanCadencePlots |
| Globus (Research Data Transfer) | https://www.globus.org/ |
| Hugging Face | https://huggingface.co/ |

---

- [▶️ 20. YouTube Playlists & Videos](#cat-20)

<a id="cat-20"></a>
## ▶️ 20. YouTube Playlists & Videos

### University Courses & Computer Science
| Name | URL |
|------|-----|
| 21-228 – Discrete Mathematics | https://youtube.com/playlist?list=PL0j-r-omG7i3P0o5RLy5yEh7WMe-l04SO |
| C++ Programming – Stanford | https://youtube.com/playlist?list=PLBBA9D02B544B48CB |
| Stanford Scientific Writing | https://youtube.com/playlist?list=PLGNyy-rO8GoM7uUxVfYJbccEO8eNFfr1M |
| The Fourier Transforms and Its Applications | https://youtube.com/playlist?list=PLB24BC7956EE040CD |
| Stanford CS149 – Parallel Computing | https://youtube.com/playlist?list=PLoROMvodv4rMp7MTFr4hQsDEcX7Bx6Odp |
| UC Berkeley CS10 – Beauty and Joy of Computing | https://youtube.com/playlist?list=PLA4F0F0CA4A3EE7F4 |
| Calculus 1 – Math 1A – UC Berkeley | https://youtube.com/playlist?list=PLShth7hrtLHPz41qo1XlGZRNl9pcVVTfj |
| EECS 70 – Discrete Mathematics and Probability Theory – UC Berkeley | https://youtube.com/playlist?list=PLu0nzW8Es1x0Ivn-757Za_ps090FJxOPd |
| STAT 2.2x – Probability – UC Berkeley | https://youtube.com/playlist?list=PL_Ig1a5kxu57qPZnHm-ie-D7vs9g7U-Cl |
| Math 55 – Discrete Mathematics – UC Berkeley | https://youtube.com/playlist?list=PLaVBOvvdB5ctaLM6AmkUaODhd4JhyP_zC |
| CS 61B – Data Structures – UC Berkeley | https://youtube.com/playlist?list=PLu0nzW8Es1x3TmpwQRLMQwCtulEd43ZY8 |
| CS 61C – Great Ideas in Computer Architecture – UC Berkeley | https://youtube.com/playlist?list=PLhMnuBfGeCDM8pXLpqib90mDFJI-e1lpk |
| Statistics 21 – UC Berkeley | https://youtube.com/playlist?list=PLk6Z3_JllTRwm6Td-S7VUDLQjrxaLLdzE |
| UC Berkeley CS10 – Beauty and Joy of Computing | https://youtube.com/playlist?list=PLECBD29A17AAF6EF9 |
| Embedded Systems | https://youtube.com/playlist?list=PL9IEJIKnBJjEcPAz6fss-Hx0TLytCOMVC |
| MIT 6.004 – Computation Structures | https://youtube.com/playlist?list=PLUl4u3cNGP62WVs95MNq3dQBqY2vGOtQ2 |

### Computer Architecture, CPU & RISC-V
| Name | URL |
|------|-----|
| Programming Heterogeneous Computing Systems with GPUs and Other Accelerators | https://youtube.com/playlist?list=PL5Q2soXY2Zi-qSKahS4ofaEwYl7_qp9mw |
| Introduction to Computer Architecture | https://youtube.com/playlist?list=PLxNPSjHT5qvti3DKL_ytbkNdWEcIFb4ku |
| Computer Architecture – Berkeley | https://youtube.com/playlist?list=PLHT49ZYxKjt1jBRl1qXI591cWqUolpnxb |
| Fall 2020 – Computer Architecture – ETH Zurich | https://youtube.com/playlist?list=PL5PHm2jkkXmh9whD2N-llDojSv8urEgIK |
| Fall 2021 – Computer Architecture – ETH Zurich | https://youtube.com/playlist?list=PL5PHm2jkkXmiSGtFXE8IKRQyIZ1wNFknx |
| Processor Architecture | https://youtube.com/playlist?list=PLNrZ57svi8FpW1ibXjM6gZnTN7UFGiMT3 |
| Processor Design | https://youtube.com/playlist?list=PL6kkmRk9W2twvvziFK43TkRrFB3blmA6X |
| RISC-V Processor Design Course | https://youtube.com/playlist?list=PLRDeZtyULZWgMGOpZxxIhsRzCFyqhQ_U8 |
| RISC-V Microarchitecture – David Harris & Sarah Harris | https://youtube.com/playlist?list=PLhA3DoZr6boVQy9Pz-aPZLH-rA6DvUidB |
| Building a CPU From Scratch | https://youtube.com/playlist?list=PLilenfQGj6CEG6iZ4TQJ10PI7pCWsy1AO |
| 8-Bit CPU | https://youtube.com/playlist?list=PLZlHzKk21aImqCiV71iE2I1dUE5LNejQk |
| RISC-V Single Cycle Core in Verilog | https://youtube.com/playlist?list=PL5AmAh9QoSK7Fwk9vOJu-3VqBng_HjGFc |
| Writing a 6502 in Verilog | https://youtube.com/playlist?list=PLGTIvEdBrUVnng1HLEQUlTR-3jaAZR2hH |
| An 8-Bit TTL CPU + GPU | https://youtube.com/playlist?list=PL75A1967B78B0D5A4 |
| FireSim and Chipyard Tutorial | https://youtube.com/playlist?list=PL-YKJjRMRb9xe1RP4uoM69CRyXZZFy2ta |

### Digital Design, Verilog & VLSI/ASIC
| Name | URL |
|------|-----|
| EE130 – Introduction to Integrated Circuit Devices – UC Berkeley | https://youtube.com/playlist?list=PLZHcIYJIAiQiw-2BsC79s96H_VCcKR8xu |
| Digital Integrated Circuits – UC Berkeley | https://youtube.com/playlist?list=PLOTpKcFOwiQSP6tqPjR7xXylPXTpiIOGD |
| ECE 3300 – Digital Circuit Design Using Verilog | https://youtube.com/playlist?list=PL-iIOnHwN7NXw01eBDR7wI8KzGK4mu8Sr |
| Digital VLSI IC Design | https://youtube.com/playlist?list=PLqDc5oN3Cb_nNtT2H-5_pNpzglkt25dEv |
| Digital Design in Cadence | https://youtube.com/playlist?list=PLOoMbgJWtq7bPVm6fuCsyOWsABMac45B5 |
| RTL-to-GDSII Flow – Hands-on with EDA Tools | https://youtube.com/playlist?list=PLC7JCwKQnjL5QPkGGEtO2TFAW9oW8c_W3 |
| Digital Integrated Circuits | https://youtube.com/playlist?list=PLZU5hLL_713yF0Lkwjj9O3ttVIuhPV-me |
| Digital VLSI Design (RTL to GDS) | https://youtube.com/playlist?list=PLZU5hLL_713x0_AV_rVbay0pWmED7992G |
| Digital ASIC Design with Verilog | https://youtube.com/playlist?list=PLfGJEQLQIDBN0VsXQ68_FEYyqcym8CTDN |
| Learn IC Design from Basics | https://youtube.com/playlist?list=PL0-xus8sJBCRXKoj2vLLnOK8KDWKpC_HH |
| SoC Physical Design | https://youtube.com/playlist?list=PL0-xus8sJBCTmG_gv4SHc5_3ofdjEZDDo |
| Advanced Process Technologies | https://youtube.com/playlist?list=PLZU5hLL_713x06MZ4OwMwnYGEeszuckZK |
| RTL2GDS Demos | https://youtube.com/playlist?list=PLZU5hLL_713zf_i38C7uLu5pUz5wTjKul |

### Analog & Mixed-Signal IC Design
| Name | URL |
|------|-----|
| Amplifiers and Op-Amps | https://youtube.com/playlist?list=PLXb3r5ny8_1VjKAyK_Zf-wFK6Z03zIytd |
| Circuits for Beginners | https://youtube.com/playlist?list=PLXb3r5ny8_1W47guxn4WBmzV1-yPneFpv |
| Transistors | https://youtube.com/playlist?list=PLXb3r5ny8_1X7Ph5vivwAmILwI42OVv94 |
| Foundations of Mixed-Signal IC Design | https://youtube.com/playlist?list=PL6J7NJyvo5nC8HLVLhgLxl38uHvxnT__Q |
| Razavi Electronics – All Lectures | https://youtube.com/playlist?list=PLyYrySVqmyVPzvVlPW-TTzHhNWg1J_0LU |
| EE610 – Analog VLSI Circuits | https://youtube.com/playlist?list=PLP-rjhz_nIi5rfzd_o7fantey3CSOixBi |
| EE698I – Mixed-Signal IC Design | https://youtube.com/playlist?list=PLP-rjhz_nIi4DYepQ5tNcEvpEs9rjUBko |
| Microelectronic Lab – IISc Bangalore | https://youtube.com/playlist?list=PLwxuOFKb1FOD9ocHiVeQdU_L_MbRD--VU |

### AI, ML, GPU & Hardware Acceleration
| Name | URL |
|------|-----|
| Neural Networks on FPGA | https://youtube.com/playlist?list=PLJePd8QU_LYKZwJnByZ8FHDg5l1rXtcIq |
| Applied Accelerated Artificial Intelligence | https://youtube.com/playlist?list=PLyqSpQzTE6M9LibNqhhCYLDvfVGhcRDN4 |
| CS285 – Deep Reinforcement Learning | https://youtube.com/playlist?list=PL_iWQOsE6TfVYGEGiAOMaOzzv41Jfm_Ps |
| CS285 – Deep Reinforcement Learning | https://youtube.com/playlist?list=PL_iWQOsE6TfXxKgI1GgyV1B_Xa0DxE5eH |
| LLM Agents MOOC | https://youtube.com/playlist?list=PLS01nW3RtgopsNLeM936V4TNSsvvVglLc |
| CS 194/294 – LLM Agents | https://youtube.com/playlist?list=PLGK6tAsp1smbj8Ga4JHcgzGNbXArity-c |
| HLS and Automated Compilation from Algorithms to Customized Accelerators | https://youtube.com/playlist?list=PLp5Yn4AjauyGjfrWFkKQlk8s9ABTB0TkW |
| Stanford CS198-126 – Modern Computer Vision | https://youtube.com/playlist?list=PLzWRmD0Vi2KVsrCqA4VnztE4t71KnTnP5 |
| Neural Networks: Zero to Hero | https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ |
| CUDA Programming | https://youtube.com/playlist?list=PLU0zjpa44nPXddA_hWV1U8oO7AevFgXnT |
| GPU MODE | https://youtube.com/@gpumode |

### FPGA, Embedded & Hardware Projects
| Name | URL |
|------|-----|
| 100 Days of FPGA | https://youtube.com/playlist?list=PL_eykaGiPP1HGc1qYqUdhdRKdJLooXKij |
| Prof. Bruce Land – FPGA Lectures | https://youtube.com/playlist?list=PLJ1LeUHJNHKhhKJQ-oFYcefHJ7e0TI8jn |
| Embedded Systems | https://youtube.com/playlist?list=PL9IEJIKnBJjEcPAz6fss-Hx0TLytCOMVC |
| Raspberry Pi Pico Lectures | https://youtube.com/playlist?list=PLDqMkB5cbBA5oDg8VXM110GKc-CmvUqEZ |
| Microcontrollers | https://youtube.com/playlist?list=PLxLxbi4e2mYFkOe5whDbd8IzBVd1opbMb |
| PCB Design | https://youtube.com/playlist?list=PLECCF3FBBE13BC85E |
| PCB Design Principles and Practices using Altium Designer | https://youtube.com/playlist?list=PL_UUr-UkFMWRXeJ2mKt5jidU5hId4-gwY |
| How to Design & Build Your Own Board | https://youtube.com/playlist?list=PLXvLToQzgzdea0sQXmpY8k4tfiXpkYIwO |

### Systems, Programming & Security
| Name | URL |
|------|-----|
| CS161 – Memory Safety, x86 Assembly and Call Stack | https://youtube.com/playlist?list=PLfBkt1-_BHX_R0dlFGLnAxOEJtWXahfdN |
| CppCon 2021 – Back to Basics | https://youtube.com/playlist?list=PLHTh1InhhwT4TJaHBVWzvBOYhp27UO7mI |
| Chill Kernel Hacking for Fun | https://youtube.com/playlist?list=PLOsF-OO4qVOT6qtNKd4vY3s1ugP_yAw-G |
| Hardware Security Tutorial | https://youtube.com/playlist?list=PLPokM2qEmTDClgPTX_GOLeMZkuf7o38yS |
| Engineer Ari Mahpour | https://youtube.com/playlist?list=PL3aaAq2OJU5EWPZa8aP6LIcT3znXEaS0i |

### Mathematics & Foundations
| Name | URL |
|------|-----|
| Differential & Integral Calculus – Math 31A – UCLA | https://youtube.com/playlist?list=PL1BE3027EF549C7D1 |
| Linear Algebra & Differential Equations – Math 54 – UC Berkeley | https://youtube.com/playlist?list=PLShth7hrtLHO2U1XkrI6ZgMyuPHDxRcob |
| Differential Equations – Professor Leonard | https://youtube.com/playlist?list=PLDesaqWTN6ESPaHy2QUKVaXNZuQNxkYQ_ |

### Chip Design Tutorials & Workshops
| Name | URL |
|------|-----|
| DDCA Problem-Solving Sessions | https://youtube.com/playlist?list=PL5Q2soXY2Zi-yo9kK-BKrq11ykNKkVEpd |
| Workshop on Open Source EDA Technologies (WOSET) | https://youtube.com/playlist?list=PLItVYhgea-kEV15gg-D_rm7VG8bg20_XV |
| RTL2GDS Demos | https://youtube.com/playlist?list=PLZU5hLL_713zf_i38C7uLu5pUz5wTjKul |
| RTL-to-GDSII Flow – Hands-on with EDA Tools | https://youtube.com/playlist?list=PLC7JCwKQnjL5QPkGGEtO2TFAW9oW8c_W3 |
| Digital VLSI Design (RTL to GDS) | https://youtube.com/playlist?list=PLZU5hLL_713x0_AV_rVbay0pWmED7992G |

### Additional Chip Design / Electronics Playlists
| Name | URL |
|------|-----|
| Atik – Transformer Accelerator Benchmark Videos | https://youtube.com/playlist?list=PL6v0daaIvQGvxYVnezbRdfBysHe-s8BjE |
| YouTube Playlist | https://youtube.com/playlist?list=PLmK06TkPUUKo-2LmZfhBpbcLTjFOxk2WJ |
| YouTube Playlist | https://youtube.com/playlist?list=PL3lzWpMir85md5miplzcRziTzs5D5p6EW |
| YouTube Playlist | https://youtube.com/playlist?list=PL6J7NJyvo5nDzRIWMMjW_xkMAZzi2SodD |
| YouTube Playlist | https://youtube.com/playlist?list=PL45ZEriClcTp79IptvZWJqUmhjypUz_44 |
| YouTube Playlist | https://youtube.com/playlist?list=PL3aaAq2OJU5ERrRd2I0LBaTdIy8DNAN2 |
| YouTube Playlist | https://youtube.com/playlist?list=PLtKLCgpXTDhA4u3rsWr-hVzvZcC-StJZe |
