# 📚 VLSI / Open-Source Chip Design — Complete Resource List

---

## 📑 Table of Contents

- [🧱 1. PDK & Process Technology](#1-pdk-process-technology)
- [🛠️ 2. EDA Tools & Design Flows](#2-eda-tools-design-flows)
- [⚙️ 3. RISC-V Cores & SoC Projects](#3-risc-v-cores-soc-projects)
- [🤖 4. AI/ML Accelerators & Hardware for AI](#4-aiml-accelerators-hardware-for-ai)
- [🔬 5. FPGA Tools, Boards & Projects](#5-fpga-tools-boards-projects)
- [📐 6. Analog, RF & Mixed-Signal Design](#6-analog-rf-mixed-signal-design)
- [🎓 7. University Courses & Curricula](#7-university-courses-curricula)
- [🏫 8. Online Courses & Learning Platforms](#8-online-courses-learning-platforms)
- [🧪 9. Hardware Description Languages (HDL) & High-Level Design](#9-hardware-description-languages-hdl-high-level-design)
- [🖥️ 10. Simulators, Applets & Visualizers](#10-simulators-applets-visualizers)
- [📦 11. Tapeout Programs & Fabrication Opportunities](#11-tapeout-programs-fabrication-opportunities)
- [🌐 12. Open Hardware Communities & Initiatives](#12-open-hardware-communities-initiatives)
- [📚 13. Research Groups & Academic Labs](#13-research-groups-academic-labs)
- [🗂️ 14. Curated Lists & Awesome Collections](#14-curated-lists-awesome-collections)
- [📖 15. Books, Articles & Blogs](#15-books-articles-blogs)
- [🔧 16. Dev Tools, Programming & Productivity](#16-dev-tools-programming-productivity)
- [🔩 17. Interesting DIY & Embedded Hardware Projects](#17-interesting-diy-embedded-hardware-projects)
- [💬 18. Forums & Community Support](#18-forums-community-support)
- [🗃️ 19. Datasets & Research Data](#19-datasets-research-data)

---

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
| OpenRAM Sky130 Fixes | https://github.com/carloscj03/openram-sky130-fixes |
| LELO Temp Sky130A Design | https://github.com/wulffern/lelo_temp_sky130a |
| LELO Temp Python Design Script | https://github.com/wulffern/lelo_temp_sky130a/blob/main/design/LELO_TEMP_SKY130A/LELOTEMP_CMP.py |

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

---

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

### EDA Wikis & Overviews
| Name | URL |
|------|-----|
| EDA Open Source & Free Tools Wiki (SemiWiki) | https://semiwiki.com/eda/ |
| Comprehensive Guide to Installing OSS IC Tools | https://www.viksnewsletter.com/p/a-comprehensive-guide-to-installing-oss-tools-for-icdesign |
| Open Source VLSI Resources | https://vlsiresources.com/opensourcevlsi/ |
| EDA Collection (pkuzjx) | https://github.com/pkuzjx/eda-collection |

---

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

---

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

---

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

---

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

---

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

### MIT
| Name | URL |
|------|-----|
| 6.375 Complex Digital Systems (2016) | https://csg.csail.mit.edu/6.375/6_375_2016_www/handouts.html |
| 6.375 Complex Digital Systems (2019) | https://csg.csail.mit.edu/6.375/ |
| Nand2Tetris | https://www.nand2tetris.org/ |
| Street-Fighting Mathematics (OCW) | https://ocw.mit.edu/courses/18-098-street-fighting-mathematics/ |

### Stanford
| Name | URL |
|------|-----|
| EE372 Design Projects in VLSI II | https://priyanka-raina.github.io/ee372-spring2022/ |
| CS 217: Hardware Accel. for ML | https://cs217.stanford.edu/ |
| Stanford VLSI Research Group | https://vlsi.stanford.edu/research |
| Stanford STORM Genie | https://storm.genie.stanford.edu/ |

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

---

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

---

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

---

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

---

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

---

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

---

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

---

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

---

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
