**ASUS PRIME A520M-A II Hackintosh Guide**

### **PC Specifications:**
- **Motherboard:** ASUS Prime A520M-A II  
- **Processor:** AMD Ryzen 5 5600 (6-Core, 3.5GHz)  
- **GPU:** Gigabyte Radeon RX Vega 56 (8GB)  
- **RAM:** 32GB DDR4 3200MHz  
- **Storage:** 256GB KingSpec NVMe PCIe Gen3x4  

### **What Works:**
- **Graphics Acceleration (QE/CI)**  
- **DRM (Digital Rights Management)**  
- **Sleep/Wake Functionality**  
- **Network Interface Card (NIC)**  
- **Power Management**  
- **HDMI Audio** (Still being tested)  

### **Untested Features:**
- Messages (iMessage)  
- FaceTime  

### **Currently Running macOS Version:**
- **macOS Big Sur** (I won't upgrade as long as web browsers remain supported.)

---

### **BIOS Settings Configuration:**
#### **Enable the Following:**
- **SVM (Secure Virtual Machine Mode)**  
- **XHCI Handoff**  
- **Above 4G Decoding**  
- **OS Type:** Set to **Other OS** in the **Boot** tab  
- **SATA Mode:** Set to **AHCI**  

#### **Disable the Following:**
- **CSM (Compatibility Support Module)**  
- **Fast Boot**  
- **Secure Boot**  
- **Serial/COM/Parallel Ports**  
- **IOMMU (Input-Output Memory Management Unit)**  
- **TPM/fTPM MacOS Don't need that
- **USB Legacy - like khronokernel said everything legacy feature in bios is bunch of crap, just disable any legacy settings you found in the bios and enjoy pure UEFI mode.
---

### **Issues Encountered During Installation:**
- **Latest NVMeFix.kext caused a reboot loop.**  
  **Solution:** Use an older version of NVMeFix.kext.  
- **Latest Realtek8111.kext did not work.**  
  **Solution:** Use an older version of Realtek8111.kext.  

### **Post-Installation Issues & Fixes:**
- **Memory misconfiguration notifications.**  
  **Solution:** Follow the Dortania Post-Install Guide.  
- **(Cosmetic Issue) Processor recognized as "Unknown."**  
  **Solution:** Follow EliteMacx86’s video tutorial on YouTube.  

---

### **Additional Notes:**
- If you have different hardware, consult appropriate guides, forums, or community discussions for support.  
- To modify USB ports (activate more or change configuration), use the **USB Mapping Tool** from the OpenCore guide and rebuild accordingly.  


