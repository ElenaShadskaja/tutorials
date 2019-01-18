---
title: code syntax httpcodes 2018 devms-167
description: devms 167 stor
tags: [products>sap-hana-cloud-platform, experience>advanced, topic>java]
primary_tag: tutorial:product/sapHana
time: 12
---





[ACCORDION-BEGIN [STEP 45](http test code)]
**7Example:http code** 
```http
@Injectable() 
class SearchService {
  apiRoot:string = 'https://itunes.apple.com/search';
  results:Object[];
  loading:boolean;

  constructor(private http:Http) { 
    this.results = [];
    this.loading = false;
  }

  search(term:string) {
  }
}
```
[ACCORDION-END]
 
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



[ACCORDION-BEGIN [STEP 14](cpp-c++ test code)]
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

[ACCORDION-BEGIN [STEP 14]( shell test code)]
***14Example:shell code** 
```shell
$ chmod a+x name.sh
$ ./name.sh Hans-Wolfgang Loidl
My first name is Hans-Wolfgang
My surname is Loidl
Total number of arguments is 2
```
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 14]( shell test code)]
***Example:unknown code** 
```basic
Sub Main()

On Error GoTo Failed

 

Dim app As Netica.Application

app = New Netica.Application

app.Visible = True

 

Dim net_file_name As String

net_file_name = System.AppDomain.CurrentDomain.BaseDirectory() & "..\..\..\ChestClinic.dne"

Dim net As Netica.Bnet

net = app.ReadBNet(app.NewStream(net_file_name))

net.Compile()

 
Dim TB As Netica.BNode

TB = net.Nodes.Item("Tuberculosis")

Dim belief As Double

belief = TB.GetBelief("present")

MsgBox("The probability of tuberculosis is " & belief)


 
```
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 14]( shell test code)]
***14Example:shell code** 
```shell
$ chmod a+x name.sh
$ ./name.sh Hans-Wolfgang Loidl
My first name is Hans-Wolfgang
My surname is Loidl
Total number of arguments is 2
```
[ACCORDION-END]
