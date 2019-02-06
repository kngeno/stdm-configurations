**Social Tenure Domain Model**
==============================

### About STDM - Data Profiles (.stc)
A set of the respective STDM data profile customizations at the country level. See the topic on Creating and Customizing Data Profiles in the user manual https://www.stdm.gltn.net/docs/1_7/#t=Getting_Started.htm


### Project Structure

The project structure of the STDM data profiles are organized according to application contexts within countries i.e. Zambia has two application contexts namely: Customary Land  and Informal Settlement which are custom STDM  data profiles/configurations.

#### Country Data Profiles/ Application Contexts:
1. Uganda
	
	- Customary Land

2. Sudan

	- Darfur 

3. DRC
	
	- Social Economics

4. Zambia
	
	- Customary Land

	- Informal Settlement

5. Phillipines
	
	- Tenure Security

6. Kenya

### Prerequisites

1. A running version of STDM v1.7.4 or higher. The [Installation Guide](https://github.com/gltn/stdm)

	- During the setup, please keep in mind where you have created the STDM directory for your files.

	**Automatically it is created in the _Home_ directory as a _hidden directory_**
 

2. For advanced users, install git package

	- [Windows](https://www.atlassian.com/git/tutorials/install-git#windows)

	- [Ubuntu](https://www.atlassian.com/git/tutorials/install-git#linux)

	- [Mac](https://www.atlassian.com/git/tutorials/install-git#mac-os-x)


### Installation

STDM - configuration can be installed in two ways:

1. For beginners - download zip file from [gltn@github.com](https://github.com/gltn/stdm-configurations/archive/master.zip)
	
	1. Extract/ unzip the **master.zip** file.

	2. Select the application context implemented in a country and rename it to **configuration.stc**.

	3. Locate the stdm directory created during STDM v1.7.4 installation. 

		1. Check the _Home_ directory

		2. Unhide the files/ directories to locate the **.stdm** directory 

	4. Copy/ move the **configuration.stc** to the base directory of the stdm directory.

	5. Refresh your QGIS application.

	6. The STDM data profile/ configuration should be available for selection.


2. For advanced users - use git clone. The steps are:
		
	1. On the STDM - coniguration repository, clone or download the repo

    2. Rename the customized STDM - configuration to configuration.stc e.g. In the case for Uganda - **configuration.stc_Uganda_Customary_Ownership_UGANDA** to **configuration.stc**

    3. Copy/ move the customized STDM **configuration.stc** to the STDM **base** directory

	4. Start your QGIS application

	5. Follow the STDM Getting Started Tutorial https://www.stdm.gltn.net/docs/1_7/#t=Getting_Started.htm

	6. Once you login into STDM, the **LCC_Property_Ownership** will be available for selection as shown below

		<img src="./images/readme/lcc_zambia_config.png" alt="configuration wizard icon" style="margin-top: 10px;" />

### License

The STDM data profiles are free software; you can redistribute it and/or modify it under the terms of the GNU General Public License version 3 (GPL v3) as published by the Free Software Foundation. The full GNU General Public License is available in LICENSE.txt or [here](http://www.gnu.org/licenses/gpl-3.0.html).