# World-Bank-API-in-KNIME
Use World Bank API to access and select sources and indicators , pivot into countries and visualise line charts. You can select up to 4 sources

![alt text](https://github.com/ryanchuabowen-ops/World-Bank-API-in-KNIME/blob/main/World_bank_API_select_upto_4_sources.svg)

The name of nodes explains the purpose of the nodes. Make sure to choose your sources' and indicators' id before selecting them. Some of the indicators and sources are removed, archived, empty or uncontactable. Hence, there might be error in GET request node in the form of the new 'body' column with xml showing an error message titled: "The indicator was not found. It may have been deleted or archived." 

This is quite common, especially in old databases world bank left. Some recent and frequently updated databases also have this problems. There is no way to know the availability of the indicators unlike sources. Even in sources, the availability column is sometimes misleading.

You have to find a new indicator in this situation.
