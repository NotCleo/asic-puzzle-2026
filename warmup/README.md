Netlist Breakdown of 01_netlist.v : 

    (if we ignore the decap + tap cells)

<img width="881" height="538" alt="image" src="https://github.com/user-attachments/assets/c728cf09-e8a4-4c49-afed-52635f1f6214" />


If we looked at the def file, we can map the layer to the signal : 

<img width="1130" height="586" alt="image" src="https://github.com/user-attachments/assets/d0075620-2316-482d-a7ca-bbb12c5acfc9" />

If we had a module-wise breakdown :

<img width="1305" height="471" alt="image" src="https://github.com/user-attachments/assets/36295c79-67ec-4d81-9de3-953cf6a514d8" />

Regarding Data flow : 

    inputs on the left → registers → adder → comparator → output on the right.


GDS views : 


<img width="1870" height="1030" alt="image" src="https://github.com/user-attachments/assets/afb7fc35-8d49-47c8-8300-898069537bee" />



<img width="1870" height="1030" alt="image" src="https://github.com/user-attachments/assets/e1fa4c67-d4e7-4135-8a78-b3347faf09f7" />


<img width="1870" height="1030" alt="image" src="https://github.com/user-attachments/assets/f8ac3981-baee-4517-9036-15c8701dcb6c" />


<img width="1870" height="1030" alt="image" src="https://github.com/user-attachments/assets/49dbea39-d65c-4492-949e-0a96b6d100aa" />


GDS (Labelled) :


<img width="1800" height="1800" alt="image" src="https://github.com/user-attachments/assets/75e89082-e893-44cc-ba75-96c0da4e823e" />
