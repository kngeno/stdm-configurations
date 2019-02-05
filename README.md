**Social Tenure Domain Model**
==============================

### About STDM - Configurations (.stc)
A set of the respective STDM data profile customizations at the country level. See the topic on Creating and Customizing Data Profiles in the user manual https://www.stdm.gltn.net/docs/1_7/#t=Getting_Started.htm


### Project Structure

The project structure of the STDM - configurations are based by country and themes within the country i.e. Uganda has a theme like Customary Ownership

#### Country Profiles:
1. Uganda
	
	-Customary Ownership

2. Sudan

	-Darfur 

3. DRC
	
	-CLUP

	-PCFP Socio Econss


4. Zambia
	
	-Lusaka City Council (LCC) Property Ownership


5. Phillipines
	
	-SALarBukidnon

6. Kenya

### Prerequisites

For advanced users, install git package

-[Windows](https://www.atlassian.com/git/tutorials/install-git#windows)

-[Ubuntu](https://www.atlassian.com/git/tutorials/install-git#linux)

-[Mac](https://www.atlassian.com/git/tutorials/install-git#mac-os-x)

### Installation

STDM - configuration can be installed in two ways:

1. For beginners - download zip file from the website [gltn@github.com](https://github.com/gltn/stdm-configurations/archive/master.zip)

2. For advanced users - use git clone. The steps are:
		
	1. On the STDM - coniguration repository, clone or download the repo

    2. Rename the customized STDM - configuration to configuration.stc e.g. In the case for Uganda - **configuration.stc_Uganda_Customary_Ownership_UGANDA** to **configuration.stc**

    3. Copy/ move the customized STDM **configuration.stc** to the STDM **base** directory

	4. Start your QGIS application

	5. Follow the STDM Getting Started Tutorial https://www.stdm.gltn.net/docs/1_7/#t=Getting_Started.htm

	6. Once you login into STDM, the **LCC_Property_Ownership** will be available for selection as shown below

		<img src="./images/readme/lcc_zambia_config.png" alt="configuration wizard icon" style="margin-top: 10px;" />

### How to Participate

-   For more information, please visit [www.stdm.gltn.net](http://www.stdm.gltn.net/) or subscribe to: [lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-user](http://lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-user)

-   To receive important news and updates around STDM in general, subscribe to: [lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-announce](http://lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-announce)

-   If you find an issue working with STDM, please report it so that developers can check and fix it. To report a bug, subscribe to: [lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-dev](http://lists.osgeo.org/cgi-bin/mailman/listinfo/stdm-dev) or post it in GitHub at: <https://github.com/gltn/stdm/issues>

-   To browse the source codes or extend the core platform, access the repository here: <https://github.com/gltn/stdm>

[![Join the chat at https://gitter.im/gltn-stdm](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gltn-stdm)


### License

STDM is a free software; you can redistribute it and/or modify it under the terms of the GNU General Public License version 2 (GPL v2) as published by the Free Software Foundation. The full GNU General Public License is available in LICENSE.txt or [here](http://www.gnu.org/licenses/gpl-2.0.html).3.