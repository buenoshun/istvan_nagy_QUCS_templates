# istvan_nagy_QUCS_templates
Signal integrity related templates for the QUCS free circuit simulator

This is a collection of circuit simulator template files to be loaded into the QUCS free simulator. Their purpose is to help with advanced signal integrity simulations for leading-edge board designs.

To download: Click the zip file, on the next page click "view raw" to download it.

PDN Template 2019+
This new version allows PDN impedance simulation and decoupling network design using measured VRM model and simulated PCB power plane model. New: Rogue Waves estimation, and automated PDN design with Optimizer.

SERDES Channel Template 2019+
This template allows freq domain „channel simulation” using QUCS, for high-speed serial 10Gbps or faster multi-gig SERDES channels, by chaining S-parameter models and lossy Tlines together.

Delta-L Template 2022
This template allows us to extract a dB/in@f0 or loss per inch data from a set of two VNA measurements. One taken on a short trace and one on a long trace on the same test coupon board or SI test board. This helps characterizing PCB materials for 10Gbos or faster board designs.

Software Tools needed:
  QUCS circuit simulator with S-parameter support (freeware, open source)
  ASCO optimizer for QUCS, used by the PDN template.
  SonnetLite PCB 3D EM Simulator, use for pre-layout plane models (freeware)
  TNT MMTL trace impedance field solver for trace width-vs-impedance computation(freeware)


