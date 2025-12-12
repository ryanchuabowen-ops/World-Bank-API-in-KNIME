# World-Bank-API-in-KNIME
Use World Bank API to access and select sources and indicators , pivot into countries and visualise line charts. You can select up to 4 sources

![alt text](https://github.com/ryanchuabowen-ops/World-Bank-API-in-KNIME/blob/main/World_bank_API_select_upto_4_sources.svg)

The name of nodes explains the purpose of the nodes. Make sure to choose your sources' and indicators' id before selecting them. Some of the indicators and sources are removed, archived, empty or uncontactable. Hence, there might be error in GET request node in the form of the new 'body' column with xml showing an error message titled: "The indicator was not found. It may have been deleted or archived." 

This is quite common, especially in old databases world bank left. Some recent and frequently updated databases also have this problems. There is no way to know the availability of the indicators unlike sources. Even in sources, the availability column is sometimes misleading.

You have to find a new indicator in this situation.


Singapore Copyright Act 2021:
https://sso.agc.gov.sg/Act/CA2021

Does the creator need to register the literary work, source code, programme, etc with authorities in Singapore?
https://ask.gov.sg/ipos/questions/clhersmdj0002mu0827iemc5a

Copyright-Refers to protection of literary works (for example: books, drawings, music, website):
Copyright protects literary works like novels, plays, drawings, paintings, sheet music, computer programme, websites. Generally, the author of a copyright work has the right to reproduce, publish, perform, communicate and adapt his work. 
These different exclusive rights form the bundle of rights that we call copyright.  An author automatically enjoys copyright protection as soon as he creates and expresses his original work in a tangible form, such as in a recording or writing. Originality simply means that there is a degree of independent effort in the creation of the work. 

In Singapore, there is no need to file for registration to get copyright protection.  However, there are a number of ways that you could preserve your interests.  You may,
Deposited a copy of your work with your lawyers or in a depository
Sent a copy of your work to yourself by post leaving the envelope unopened so that the date stamp and the unopened work could establish the date of the work’s existence
Made a declaration before a Commissioner of Oaths stating the facts of ownership and the date of creation

As the copyright owner, you will enjoy the exclusive rights to :
reproduce the work;
publish the work if the work is unpublished;
perform the work in public;
communicate the work to the public; and
make an adaptation of the work
