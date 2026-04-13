# 📚 VLSI / Open-Source Chip Design — Complete Resource List

---

## 📑 Table of Contents

- [🧱 1. PDK & Process Technology](#s1)
- [🛠️ 2. EDA Tools & Design Flows](#s2)
- [⚙️ 3. RISC-V Cores & SoC Projects](#s3)
- [🤖 4. AI/ML Accelerators & Hardware for AI](#s4)
- [🔬 5. FPGA Tools, Boards & Projects](#s5)
- [📐 6. Analog, RF & Mixed-Signal Design](#s6)
- [🎓 7. University Courses & Curricula](#s7)
- [🏫 8. Online Courses & Learning Platforms](#s8)
- [🧪 9. Hardware Description Languages (HDL) & High-Level Design](#s9)
- [🖥️ 10. Simulators, Applets & Visualizers](#s10)
- [📦 11. Tapeout Programs & Fabrication Opportunities](#s11)
- [🌐 12. Open Hardware Communities & Initiatives](#s12)
- [📚 13. Research Groups & Academic Labs](#s13)
- [🗂️ 14. Curated Lists & Awesome Collections](#s14)
- [📖 15. Books, Articles & Blogs](#s15)
- [🔧 16. Dev Tools, Programming & Productivity](#s16)
- [🔩 17. Interesting DIY & Embedded Hardware Projects](#s17)
- [💬 18. Forums & Community Support](#s18)
- [🗃️ 19. Datasets & Research Data](#s19)

---

<a name="s1"></a>
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

<a name="s2"></a>
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

<a name="s3"></a>
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

<a name="s4"></a>
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

<a name="s5"></a>
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

<a name="s6"></a>
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

<a name="s7"></a>
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

<a name="s8"></a>
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

<a name="s9"></a>
## 🧪 9. Hardware Description Languages (HDL) & High-Level Design

| Name | URL |
|------|-----|
| SpinalHDL | https://github.com/SpinalHDL/SpinalHDL |
| MyHDL | https://www.myhdl.org/ |
| Spade HDL | https://spade-lang.org/ |
| TL-Verilog Projects (TL-X org) | https://github.com/TL-X-org/TL-V_Projects |
| ROHD (Intel – Dart-based HDL) | https://intel.
