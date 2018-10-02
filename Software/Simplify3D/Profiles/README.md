# PRINT PROFILES
This directory contains tested instructions, parameters, and profiles (factory files) for the printing of several materials using the CR10S printers

---
### HARDWARE UPGRADES
To ensure performance and reliability, the following **hardware upgrades** are recommended;
* [BuildTak](https://www.buildtak.com/product/buildtak-3d-printing-surface/)
* [MicroSwiss Hot-End](https://store.micro-swiss.com/collections/creality-cr-10/products/all-metal-hotend-kit-for-cr-10)
* [Capricorn PTFE Tubing](https://store.micro-swiss.com/collections/creality-cr-10/products/capricorn-xs-bowden-tubing)

---
### ABS
#### Recommended
* Supplier/Brand              = [HatchBox](https://www.amazon.com/HATCHBOX-3D-Filament-Dimensional-Accuracy/dp/B00J0H8EWA)
* Tool Temperature            = 245C
* Bed Temperature             =  80C **(BuildTak Surface is Essential!!!)**
* Printing Speeds             = Normal Speeds/Half Speeds for Quality

### CARBON-FIBER NYLON
#### Recommended
* Supplier/Brand               = [MatterHackers](https://www.matterhackers.com/store/3d-printer-filament/nylonx-carbon-fiber-nylon-filament-1.75mm)
* Tool Temperature             = 260   C
* Bed Temperature              =  65   C **(BuildTak Surface is Essential!!!)**
* Printing Speeds              = Half of Default Speeds
  * Default Printing Speed     = 1200  mm/min
  * X/Y Axis Movement Speed    = 2400  mm/min
  * Z Axis Movement Speed      = 500   mm/min
* Additional Comments          = Build platform **adherance** is extremely hard for the Carbon Fiber Nylon material. The separation distance between nozzle and platform should be below 0.15 mm. May require the use of another build platform or surface material like [garolite](https://www.matterhackers.com/articles/3d-printer-anatomy-print-surfaces?utm_source=MatterHackers+Newsletter&utm_campaign=758abb8e16-EMAIL_CAMPAIGN_2018_09_11_06_30&utm_medium=email&utm_term=0_dccd3cdce8-758abb8e16-127829101)

### PETG
#### Recommended
* Supplier/Brand               = [HatchBox](https://www.amazon.com/HATCHBOX-3D-Filament-Dimensional-Accuracy/dp/B07GH684RC/ref=sr_1_2?s=industrial&ie=UTF8&qid=1538155625&sr=1-2&keywords=hatchbox+petg)
* Tool Temperature             = 245   C
* Bed Temperature              =  75   C **(BuildTak Surface is Essential!!!)**
* Printing Speeds              = Normal Speeds (similar to PLA)
* Additional Comments          = Used raft for best adhesion and reduced the "layer separation" parameter to 0 mm (this is for very tall   parts)
* References                   = [Thomas Sanladerer](https://www.youtube.com/watch?v=8_adY2K-YIc)

### TPU95A
#### Recommended
* Supplier/Brand               = [eSUN](https://www.amazon.com/eSUN-1-75mm-Flexible-Printer-Filament/dp/B07B5LPTGD/ref=pd_sbs_328_2?_encoding=UTF8&pd_rd_i=B07B5LPTGD&pd_rd_r=81bbefb4-c654-11e8-a4c0-59194f455d2c&pd_rd_w=UM9hg&pd_rd_wg=74arQ&pf_rd_i=desktop-dp-sims&pf_rd_m=ATVPDKIKX0DER&pf_rd_p=0bb14103-7f67-4c21-9b0b-31f42dc047e7&pf_rd_r=MYZKYGG7K0QNGSSHCB68&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=MYZKYGG7K0QNGSSHCB68)
* Tool Temperature             = 230   C
* Bed Temperature              =  65   C **(Nice finish on glass!!!)**
* Printing Speeds              = Normal Speeds (similar to PLA) --Need to test slower sppeds
