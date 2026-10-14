# Awesome-HVAC-Operational-Efficiency-Optimization

# Top HVAC Operational Efficiency Optimization Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Building Climate Control, Occupancy-Aware Scheduling & Energy Savings*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **HVAC Operational Efficiency Optimization**. These tools enable building operators to tailor climate patterns to match localized usage—reducing energy waste by aligning heating and cooling with actual occupancy, weather forecasts, and thermal dynamics.

**Examples** include BrainBox AI, 75F, Augury, Siemens Desigo CC, Johnson Controls Metasys, Schneider Electric EcoStruxure, Turntide Technologies, Carrier Abound, Honeywell Forge, and Daikin One Cloud (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, model predictive control, and open building energy management—ideal for facility managers, building engineers, and developers seeking transparent, vendor-independent HVAC optimization.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Schneider Electric EcoStruxure Building Activate](https://www.se.com/uk/en/about-us/newsroom/news/press-releases/schneider-electric-introduces-ecostruxure%E2%84%A2-building-activate-simplifying-automated-management-for-small-and-mid-size-buildings-674df5f8886e15832a0cc1b7/)**  
  Cloud-based SaaS for small and mid-size buildings (>10k sqm). Features energy management (reduce demand up to 48%), sustainability management (reduce operational carbon up to 60%), and operations management (manage 90% of issues remotely) . Historic 4-star hotel Grand Monarque saw **15% energy reduction** in a 600-year-old building with **payback in under 12 months** . Open platform integrates HVAC, lighting, and refrigeration with a user-friendly web and mobile interface .

- **[Trane Cloud](https://www.facilitiesdive.com/news/trane-launches-digital-hub-to-unify-building-data-applications/811717/)**  
  Digital hub unifying building data and applications for autonomous control, asset management, and energy optimization . Features **AI Control and ARIA AI** for building management—reducing heating and cooling up to **25%** and carbon emissions up to **40%** . Emporia State University achieved **$10.2 million in energy cost savings**; Bullitt County Public Schools saw **13% energy reduction**; Hyatt achieved **916 million tons of CO2 reduction** .

- **[ABB Ability BuildingPro Suites](https://new.abb.com/news/detail/134002/abb-launches-ability-buildingpro-suites-to-unify-building-and-iot-systems-for-data-driven-performance)**  
  Modular software platform unifying building, energy, HVAC, and automation data into one intelligent, cybersecure environment . Six domain-focused suites covering energy, operations, comfort, asset health, space, and grid interaction . Built on an open semantic data model, AI-ready by design, deployable on-premises at the edge or in the cloud . Supports BACnet, KNX, Modbus, M-Bus, OPC UA, MQTT, and more .

- **[BrainBox AI](https://brainboxai.com/)**  
  Autonomous AI for HVAC optimization. Uses deep learning to predict building thermal dynamics and optimize HVAC setpoints in real time.

- **[75F](https://www.75f.io/)**  
  IoT-based building management system for small and mid-size commercial buildings. Features wireless sensors, cloud analytics, and automated HVAC control.

- **[Honeywell Forge](https://www.honeywell.com/)**  
  Enterprise performance management platform with building optimization, energy analytics, and predictive maintenance.

- **[Johnson Controls OpenBlue](https://www.johnsoncontrols.com/)**  
  Digital platform connecting legacy building systems to AI-based energy optimization and sustainability management .

- **[Siemens Building X](https://www.siemens.com/)**  
  Unified building operations platform preserving building knowledge from design through operations, with energy optimization and AI-driven analytics .

- **[Carrier Abound](https://www.carrier.com/)**  
  Cloud intelligence built on a foundation in controls and equipment, providing building performance optimization .

- **[Daikin One Cloud](https://www.daikin.com/)**  
  Cloud platform for HVAC equipment monitoring, control, and energy optimization.

## Open-Source GitHub Projects

- **[Modelica Buildings Library](https://github.com/lbl-srg/modelica-buildings)**  
  **The most comprehensive open-source library for building energy and control system simulation** (BSD-3-Clause, Lawrence Berkeley National Laboratory) . Features dynamic simulation models for **HVAC systems, energy storage, controls (including ASHRAE Standard 231P reference implementation), heat transfer, multizone airflow, and electrical systems** . Used by **Spawn of EnergyPlus, OpenBuildingControl, IBPSA Project 1, and BOPTEST** . Export digital twins to support operation for functional testing, verification of control sequences, and energy-minimizing controls . **The foundational modeling library for open-source building control research.**

- **[BEMServer](https://github.com/HIT2GAP-EU-PROJECT/bemserver)**  
  **Open-source platform for building energy management** (European HIT2GAP project) . Acts as an intermediary layer centralizing heterogeneous data from BMS, sensors, weather services, and occupancy monitoring . Features **semantic model** for consistent data representation and **API interfaces** for monitoring, analytics, forecasting, anomaly detection, and energy performance indicators . Modules include **Fault Detection & Diagnosis (PCA and ML), Load Forecasting, Renewable Energy Simulation, Indoor Environmental Quality, and Human Behaviour Management** . Deployed on four pilot sites with demonstrated energy performance gap reduction . **The most mature open-source BEM platform for operational deployment.**

- **[BEMOSS](https://github.com/VOLTTRON/volttron-pnnl-aems)**  
  **Building Energy Management Open-Source Software** (open-source, Virginia Tech) . Low-cost platform for monitoring and controlling **HVAC, lighting, plug loads, solar PV, and energy storage** in commercial buildings . Leverages **machine learning** to draw insights from historical operating data and occupant preferences to save energy while increasing comfort . Supports **demand response** via OpenADR . **The most accessible open-source BEM platform for small and medium commercial buildings.**

- **[VOLTTRON AEMS](https://github.com/VOLTTRON/volttron-pnnl-aems)**  
  **Autonomous Energy Management Software** (Apache-2.0, Pacific Northwest National Laboratory) . Continuously optimizes operations of distributed energy resources in small and medium commercial buildings . Manages **rooftop air conditioners and heat pumps**, extensible to water heaters, storage, EV charging, and solar PV . Supports both energy efficiency and grid service features . **The most DOE-backed open-source autonomous HVAC optimization framework.**

- **[ACTIVE](https://github.com/SmithRWORNL/ACTIVE)**  
  **Automated Control Testbed for Integration, Verification, and Emulation** (BSD-3-Clause, Oak Ridge National Laboratory) . Enables development, testing, and validation of **AI-based, rule-based, and model-based control strategies** . Facilitates seamless transition from simulation-based evaluation to real-world field validation and deployment . Supports full building management lifecycle: data acquisition, monitoring, optimized control, adaptive learning, device dispatch, and analytics . **The most comprehensive open-source testbed for HVAC control strategy validation.**

- **[OpenStudio Analysis Framework (OSAF)](https://github.com/NREL/OpenStudio-analysis)**  
  **Open-source framework for optimization and parametric analysis of building energy models** (open-source, NREL) . Makes large-scale building energy modeling accessible to architects, engineers, and policymakers . Features **multi-objective optimization, sensitivity analysis, uncertainty quantification, and model calibration** . Deployable on high-performance computing systems, cloud infrastructure, or laptops . **The most scalable open-source framework for building energy model optimization.**

- **[ACAI (Air Conditioning Artificial Intelligence)](https://github.com/BangyStudios/ACAI)**  
  **Open-source AI suite for air conditioning systems** (open-source) . Aims to minimize power use while maintaining comfort . Features **proportional controller** to adjust set temperature per AC unit, **room volume-based airflow calculation**, and **solar system integration** for switching on/off and temperature optimization based on solar energy . **The most focused open-source project for residential/small commercial AC optimization.**

- **[MyEMS](https://gitee.com/myems/myems)**  
  **Open-source energy management system for buildings, factories, malls, hospitals, and campuses** (open-source) . Features **energy data collection, analysis, and reporting** for electricity, water, and gas . Optional modules include **PV, energy storage, charging piles, microgrid, device control, fault diagnosis, work order management, and AI optimization** . Includes **space energy category analysis** for building-level energy breakdown . **The most feature-complete open-source EMS for multi-site portfolios.**

- **[RL-EmsPy / RL-BCA](https://github.com/mechyai/RL-EmsPy)**  
  **API for reinforcement learning algorithm design and testing of Building Control Agents on EnergyPlus** (open-source) . Wraps EnergyPlus EMS Python API for RL-based HVAC control research . **The most accessible open-source bridge between RL research and building energy simulation.**

- **[beobench](https://github.com/rdnfn/beobench)**  
  **Toolkit providing unified access to building control environments for reinforcement learning** (open-source, 41 GitHub stars) . Note: No longer actively maintained . **The most comprehensive benchmark suite for RL-based building control.**

### Additional Strong Open-Source Options

- **[ESP-r](https://github.com/esp-r/esp-r)** — Advanced simulation tool for building energy and environmental performance, integrating heat, air, moisture, and light (open-source, University of Strathclyde) . **The most rigorous open-source simulation engine for detailed building physics.**
- **[eQUEST](https://www.doe2.com/equest/)** — Open-source building energy simulation tool rooted in DOE-2 engine (open-source, LBNL) . Features **8,760-hour dynamic simulation** integrating envelope, HVAC, lighting, and occupancy factors . Used for ASHRAE 90.1 and LEED compliance .
- **[CACTUS Energy Suite](https://cordis.europa.eu/project/id/855096)** — Open-source AI software for energy efficiency in large buildings and infrastructure (open-source, EU-funded) . Features **ISO 50001 support, data collection, virtual meters, and AI-based optimization** . Deployable as SaaS or locally .
- **[Online Comfort-Constrained HVAC Control](https://github.com/sustainable-computing/ocft)** — Code for feature-transfer RL policy for HVAC systems (open-source) . Achieves **81.28% reduction in thermal comfort violations** with only **11.23% increase in energy usage** across 19 climate locations .
- **[Decision-Focused Learning for HVAC](https://github.com/PSMRB/dfl_hvac_management)** — Code for DFL-based HVAC scheduling optimization (MIT) . Learns ML proxy for building thermal dynamics as constraint in day-ahead scheduling .
- Community **n8n** workflows for HVAC alert routing and occupancy-based control automation.

**Frameworks for building custom systems**: Combine **Modelica Buildings Library** for high-fidelity HVAC modeling with **BEMServer** for operational data integration and fault detection, **VOLTTRON AEMS** for autonomous control, **ACTIVE** for control strategy validation, and **MyEMS** for multi-site energy management—creating a fully self-hosted, enterprise-grade HVAC optimization platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- HVAC optimization systems controlling building climate must comply with building codes, ASHRAE standards, and occupant comfort requirements.
- **Open-source HVAC optimization is mature and production-ready.** Modelica Buildings Library is the foundational modeling library used by multiple DOE projects . BEMServer has been deployed on four pilot sites with demonstrated energy performance gap reduction . VOLTTRON AEMS is DOE-backed for autonomous control . **These are genuine alternatives to commercial platforms.**
- **Occupancy-aware scheduling is the highest-impact lever.** SeerOS demonstrates that combining HVAC control with IoT presence sensors achieves **8-25% energy savings** by lowering air volume when occupancy is low and switching off lights in unused spaces . Exergenics optimizes chiller plants—typically **25% of commercial building electricity**—with **6.32% verified energy savings** .
- **Model-based control enables pre-commissioning validation.** Modelica Buildings Library exports digital twins for functional testing, verification of control sequences, and energy-minimizing controls before field deployment . ACTIVE bridges simulation to real-world validation .
- **AI and ML are converging with physics-based models.** RL-EmsPy and RL-BCA provide bridges between reinforcement learning and EnergyPlus . The Online Comfort-Constrained HVAC Control paper achieves **81% reduction in comfort violations** with only **11% energy increase**—demonstrating that AI can prioritize comfort alongside efficiency .
- Self-hosted open-source solutions require proper security hardening, BMS integration, and ongoing maintenance. HVAC systems are critical infrastructure—failures can impact occupant health and safety.

---

**Made for facility managers, building engineers, and developers building transparent HVAC optimization solutions.**  
Let's make HVAC Operational Efficiency more open, data-driven, and occupancy-aware.
