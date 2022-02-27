# Battering-Ram-Microactuator-POLYMUMPs

![image](https://user-images.githubusercontent.com/89353805/155899040-0838bc94-416b-47ac-9f01-7479f7b60b7d.png) ![image](https://user-images.githubusercontent.com/89353805/155899066-be443a46-84e1-4278-b1e7-5ae5fa264d13.png)

Material Layer	Thickness (µm)	Lithography Level Name
Nitride	          0.6	                    --
Poly 0	           0.5	              POLY0 (HOLE0)
First Oxide	      2.0	                  DIMPLE
                                        ANCHOR1
Poly 1	           2.0	              POLY1 (HOLE1)
Second Oxide	     0.75	            POLY1_POLY2_VIA
                                        ANCHOR2
Poly 2	           1.5	              POLY2 (HOLE2)
Metal	            0.5	              METAL (HOLEM)


The PolyMUMPs process is a three-layer polysilicon surface micromachining process derived from work performed at the Berkeley Sensors and Actuators Center (BSAC) at the University of California in the late 80’s and early 90’s. Several modifications and enhancements have been made to increase the flexibility and versatility of the process for the multi-user environment. The process flow described below is designed to introduce inexperienced users to polysilicon micromachining. The text is supplemented by detailed drawings that show the process flow in the context of building a typical micromotor.

The process begins with 100 mm n-type (100) silicon wafers of 1-2 Ohm-cm resistivity. The surface of the wafers are first heavily doped with phosphorus in a standard diffusion furnace using POCl 3 as the dopant source. This helps to reduce or prevent charge feedthrough to the substrate from electrostatic devices on the surface. Next, a 600 nm low-stress LPCVD (low pressure chemical vapor deposition) silicon nitride layer is deposited on the wafers as an electrical isolation layer. This is followed directly by the deposition of a 500 nm LPCVD polysilicon film–Poly 0. Poly 0 is then patterned by photolithography, a process that includes the coating of the wafers with photoresist, exposure of the photoresist with the appropriate mask and developing the exposed photoresist to
 
create the desired etch mask for subsequent pattern transfer into the underlying layer (Figure 1.3). After patterning the photoresist, the Poly 0 layer is then etched in an RIE (Reactive Ion Etch) system. A 2.0 µm phosphosilicate glass (PSG) sacrificial layer is then deposited by LPCVD and annealed @1050°C for 1 hour in argon. This layer of PSG, known as First Oxide, is removed at the end of the process to free the first mechanical layer of polysilicon. The sacrificial layer is lithographically patterned with the DIMPLES mask and the dimples are transferred into the sacrificial PSG layer by RIE. The nominal depth of the dimples is 750 nm. The wafers are then patterned with the third mask layer, ANCHOR1, and reactive ion etched. This step provides anchor holes that will be filled by the Poly 1 layer.

After etching ANCHOR1, the first structural layer of polysilicon (Poly 1) is deposited at a thickness of 2.0 µm. A thin (200 nm) layer of PSG is deposited over the polysilicon and the wafer is annealed at 1050°C for 1 hour. The anneal dopes the polysilicon with phosphorus from the PSG layers both above and below it. The anneal also serves to significantly reduce the net stress in the Poly 1 layer. The polysilicon (and its PSG masking layer) is lithographically patterned using a mask designed to form the first structural layer POLY1. The PSG layer is etched to produce a hard mask for the subsequent polysilicon etch. The hard mask is more resistant to the polysilicon etch chemistry than the photoresist and ensures better transfer of the pattern into the polysilicon. After etching the polysilicon, the photoresist is stripped and the remaining oxide hard mask is removed by RIE.

After Poly 1 is etched, a second PSG layer (Second Oxide) is deposited and annealed. The Second Oxide is patterned using two different etch masks with different objectives. The POLY1_POLY2_VIA level provides for etch holes in the Second Oxide down to the Poly 1 layer. This provide a mechanical and electrical connection between the Poly 1 and Poly 2 layers. The POLY1_POLY2_VIA layer is lithographically patterned and etched by RIE. The ANCHOR2 level is provided to etch both the First and Second Oxide layers in one step, thereby eliminating any misalignment between separately etched holes. More importantly, the ANCHOR2 etch eliminates the need to make a cut in First Oxide unrelated to anchoring a Poly 1 structure, which needlessly exposes the substrate to subsequent processing that can damage either Poly 0 or Nitride. The ANCHOR2 layer is lithographically patterned and etched by RIE in the same way as POLY1_POLY2_VIA.

The second structural layer, Poly 2, is then deposited (1.5 µm thick) followed by the deposition of 200 nm PSG. As with Poly 1, the thin PSG layer acts as both an etch mask and dopant source for Poly 2. The wafer is annealed for one hour at 1050 C to dope the polysilicon and reduce the residual film stress. The Poly 2 layer is lithographically patterned with the seventh mask (POLY2) and the PSG and polysilicon layers are etched by RIE using the same processing conditions as for Poly 1. The photoresist then is stripped and the masking oxide is removed.

The final deposited layer in the PolyMUMPs process is a 0.5 µm metal layer that provides for probing, bonding, electrical routing and highly reflective mirror surfaces. The wafer is patterned lithographically with the eighth mask (METAL) and the metal is deposited and patterned using lift-off. The final, unreleased structure is shown in Figure 1.15. The wafers are diced, sorted and shipped to the PolyMUMPs user for sacrificial release and test. Figure 1.16 shows the device after sacrificial oxide release. The release is performed by immersing the chip in a bath of 49% HF (room temperature) for 1.5-2 minutes. This is followed by several minutes in DI water and then alcohol to reduce stiction followed by at least 10 minutes in an oven at 110C.

 
