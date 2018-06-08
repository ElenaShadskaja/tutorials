---
title: code syntax httpcodes 2018 devms-167
description: devms 167 stor
tags: [products>sap-hana-cloud-platform, topic>cloud, topic>java]
primary_tag: tutorial:product/sapHana
---

 
[ACCORDION-BEGIN [STEP 0]( now html)]

  **Example:code** 
  
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

[ACCORDION-END]



[ACCORDION-BEGIN [STEP 14](cpp test code)]
***14Example:shell code** 
```cpp
  // Initialize the MQQMPROPS structure.  
  qmprops.cProp = cPropId;                            // Number of properties  
  qmprops.aPropID = aQMPropId;                        // IDs of the properties  
  qmprops.aPropVar = aQMPropVar;                      // Values of the properties  
  qmprops.aStatus = aQMStatus;                        // Error reports  
  
  // Call MQGetMachineProperties to retrieve the   
  // GUID of the computer where the queue is registered.  
  hr = MQGetMachineProperties(NULL,  
                              NULL,  
                              &qmprops);  
  if (FAILED(hr))  
  {  
     fprintf(stderr, "An error occurred in MQGetMachineProperties (error: 0x%x).\n",hr);  
     return hr;  
  }  
  
  // Construct the format name of the private qu
```
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 12]( python test code)]
***12Example: w/o code** 
```
  // Initialize the MQQMPROPS structure.  
  qmprops.cProp = cPropId;                            // Number of properties  
  qmprops.aPropID = aQMPropId;                        // IDs of the properties  
  qmprops.aPropVar = aQMPropVar;                      // Values of the properties  
  qmprops.aStatus = aQMStatus;                        // Error reports  
  
  // Call MQGetMachineProperties to retrieve the   
  // GUID of the computer where the queue is registered.  
  hr = MQGetMachineProperties(NULL,  
                              NULL,  
                              &qmprops);  
  if (FAILED(hr))  
  {  
     fprintf(stderr, "An error occurred in MQGetMachineProperties (error: 0x%x).\n",hr);  
     return hr;  
  }  
  
  // Construct the format name of the private qu
"""This is a 
multiline docstring."""
print("Hello, World!")
```
[ACCORDION-END]