# Extended-Cardiac-Action-Potential-Model-of-the-Human

This software code provides an extension of a model of the human cardiac action potential. This extension includes a model of patient's withheart failure (HF) as well as those in HF AND the pharmacological therapy of amiodorone (HF+AM) or d-sotalol (HF+DS); these models are described in [1] and represent an extension of the model of the 'normal' patient action potential described in [2]. The model code is written in CellML which is an open standard based on the XML markup language [2]. The model was derived from voltage clamp experimental data from canine ventricular myocytes/tissue under nearly identical and physiological conditions. This model of the human action potential is moderately complex with six currents and seven variables, including a novel phenomenological model of dynamic diastolic calcium concentration (CaiD). The model was calibrated using the following well-known and important electro-physiological phenomena measured from patients during programmed electrical stimulation (PES): 1) action potential duration; and 2) post-repolarization refractoriness. We constructed 8 AM model ‘variants’ by combining effects on various parameters due to the limited and disparate voltage clamp data regarding the effects of chronic AM. Reentrant activity was induced in all HF simulations but was prevented in 23 of 24 HF+AM models. Eliminating the AM-induced slowing of the recovery of inactivation of the sodium channel restored the ability to induce reentry. For more information about the model please refer to [2]. There are a variety of OpenSource Tools to run this CellML model (see [3]).

The code itself is provided in the following files:

Heart Failure: 			GrayFranzHumanModel2023_HF.cellml
Heart Failure + d-sotalol: 	GrayFranzHumanModel2023_HF_DS.cellml
Heart Failure + amiodarone:	GrayFranzHumanModel2023_HF_AMn.cellml
	where n=1 to 8 representing 8 variants to incorporate the
 	disparate voltage clamp results of chronic amiodarone

# Tool Reference
•	RST Reference Number: RST24CV17.01  
•	Date of Publication: 06/06/2024  
•	Recommended Citation: U.S. Food and Drug Administration. (2024). Extended Human Action Potential Model for Heart Failure (RST24CV17.01). https://cdrh-rst.fda.gov/extended-human-action-potential-model-heart-failure  

# Disclaimer
About the Catalog of Regulatory Science Tools  
The enclosed tool is part of the Catalog of Regulatory Science Tools, which provides a peer- reviewed resource for stakeholders to use where standards and qualified Medical Device Development Tools (MDDTs) do not yet exist. These tools do not replace FDA-recognized standards or MDDTs. This catalog collates a variety of regulatory science tools that the FDA's Center for Devices and Radiological Health's (CDRH) Office of Science and Engineering Labs (OSEL) developed. These tools use the most innovative science to support medical device development and patient access to safe and effective medical devices. If you are considering using a tool from this catalog in your marketing submissions, note that these tools have not been qualified as Medical Device Development Tools and the FDA has not evaluated the suitability of these tools within any specific context of use. You may request feedback or meetings for medical device submissions as part of the Q-Submission Program.  

For more information about the Catalog of Regulatory Science Tools, email OSEL_CDRH@fda.hhs.gov.  

This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

References

[1] Gray RA, Franz MR. Amiodarone Prevents Wave Front-Tail Interactions in Heart Failure Patients: An In-Silico Study. American Journal of Physiology

[2] Gray RA, Franz MR. A Model for Human Action Potential Dynamics In Vivo. American Journal of Physiology â€“ Heart and Circulatory Physiology, 2020: doi.org/10.1152/ajpheart.00557.2019. https://journals.physiology.org/doi/full/10.1152/ajpheart.00557.2019 & https://pubmed.ncbi.nlm.nih.gov/31951472/

[3] CellML.Org
