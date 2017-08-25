
[![Project Status](http://opensource.box.com/badges/active.svg)](http://opensource.box.com/badges)

Acumatica Portal Customization 
==================================

Customization Implements below features:

* Catalog (SP700000) will list inventories for which customer has a specific price defined rather including inventories with no price and which cannot be added to cart.

* Order will be placed using shipping branch of the customer. Portal branch (SP800000) will be used only if customer shipping branch is not specified.

* User can specify Customer Order # during Check Out (SP700002)

* Finance -> My Documents (SP402000) : Listing will include AR documents from all branches rather filtering on Portal branch (SP800000). 

* Finance -> My Documents -> Aging Report (SP402000) : Report data will include information from all branches rather filtering on Portal branch (SP800000).


### Prerequisites
* Acumatica 6.10 or higher

Quick Start
-----------

### Installation

##### Install the customization deployment package
1. Download PXPortalCustomizationExtPkg.zip from this repository
2. In your Acumatica Portal instance, navigate to System -> Customization -> Customization Projects (SM204505), import PXPortalCustomizationExtPkg.zip as a customization project
3. Publish the customization project.

Known Issues
------------
None at the moment

## Copyright and License

Copyright © `2017` `Acumatica`

This component is licensed under the MIT License, a copy of which is available online [here](LICENSE.md)
