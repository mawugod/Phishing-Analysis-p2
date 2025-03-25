# Challenge - Phishing Analysis
**Source:** https://challenges.malwarecube.com/#/c/074e4448-e8d7-4122-86f2-36a4d7b2a18b

<picture>![image](https://github.com/user-attachments/assets/cfb0ce39-9aff-4b2b-9501-80de8d7fba30)</picture>

 **Email Content**
| Rendered | Plaintext |
| -------- | --------- |
| <picture>![image](https://github.com/user-attachments/assets/ec4030f7-3461-4971-a385-616d02150b64)</picture> |<picture> ![image](https://github.com/user-attachments/assets/592292a3-b270-4511-8a7a-0bc586135587)
 </picture> |

 
## Technical Analysis -Static and Dynamic Analysis


+ Both 'eioc.py' and Phishtool 'https://phishtool.com/' were used for this analysis  

I run the 'eioc.py tool to extract the fields as below.  
<picture>![image](https://github.com/user-attachments/assets/fda52dd2-7a49-40d4-84c2-ac9c84aa0ada)</picture>
  
Below is a snapshot of some parts of the analysis obtained from the Phishtool.

 a. Email Metadata

<picture>![image](https://github.com/user-attachments/assets/5c148b61-5d2f-42d1-bb11-454b677e33f3)</picture>
 
b. Associated URLs Analysis
   
| URL | Analysis | Verdict|
| -------- | --------- | --------- |
| https://www.dropbox.com/l/ABCIzswwTTJ9--CxR05fYXX35pPA-Y0m3PY/forgot_finish | <picture>![image](https://github.com/user-attachments/assets/e1382674-2792-4d71-b504-da1c09343017) </picture> | From the analysis, URL is genuine link |
| https://www.dropbox.com/l/AADQ493u2QLcZrv2kCW6C6i0Ac-mR0hUXxU/help/365 | <picture>![image](https://github.com/user-attachments/assets/40943063-f0ca-4b62-b343-f1ae5fd0f6c7) </picture>| From the analysis, URL is genuine link |
  
c. Sender IP Analysis  
  
The domaintool 'https://whois.domaintools.com/ was used to get us the information in the snapshot below.  
  
<picture>![image](https://github.com/user-attachments/assets/4c49fa89-f1d2-4ec9-a841-b4c41a12eb87)</picture>


### Answer to the Questions from the Challenge

<picture>![image](https://github.com/user-attachments/assets/dbadf7f4-daa0-47a2-8418-03385995d320)</picture>  
  
Answer was obtained from the use of the 'eioc.py' script  
  
<picture>![image](https://github.com/user-attachments/assets/288c11e3-6829-4f65-b456-e6a34f2ace5c)</picture>
###
<picture>![image](https://github.com/user-attachments/assets/f1d1a89f-3e93-41ec-8132-63eab4bcfb7a)</picture>  
<picture>![image](https://github.com/user-attachments/assets/8a312d61-d2eb-4534-9b8a-88dbfcd24cdc)</picture>  
<picture>![image](https://github.com/user-attachments/assets/64b68bf9-58cc-41e6-9ac8-7339d54ef679)</picture>  
<picture>![image](https://github.com/user-attachments/assets/ebbfa106-398a-48ac-a94f-3a7f3b1feb19)</picture>  
<picture>![image](https://github.com/user-attachments/assets/ab254fe0-1988-4f8c-a490-a98ee4273cc3)</picture>  
  
Answer obtained from the Phishtool.  
<picture>![image](https://github.com/user-attachments/assets/54de72da-009a-4ad1-840a-a1c1bf9847cf)</picture>  
<picture>![image](https://github.com/user-attachments/assets/b9c712a8-fa52-4bd8-a749-65ed7851c660)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/a98d29c9-7554-4eee-b50c-b0b79ec4c20f)
</picture>   
Using the whois domain tools 'https://whois.domaintools.com/' to obtain the resolved hostname   
  
<picture>![image](https://github.com/user-attachments/assets/81afb28d-ca3d-4df3-95fd-07de01e79f5e)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/e96ed304-9074-489c-81be-c1ab367590bb)
</picture>  
Using the whois domain tools 'https://whois.domaintools.com/' to obtain the  Autonomous System Number    
  
<picture>![image](https://github.com/user-attachments/assets/89e9b35a-7e67-4e4f-acc5-b668026793ce)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/0e0c49ae-4a2d-409d-863c-ad0e8c8ebad4)
</picture>     
Answer obtained from 'eioc.py'  and/or the Phishtool  
<picture>![image](https://github.com/user-attachments/assets/d3c378d9-2876-4702-b213-bffa5069bef8)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/463f14b4-eed6-4a44-960e-a7efc8dcd0d2)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/670b7344-a7f2-4737-8a33-9c7d082a32b6)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/463f14b4-eed6-4a44-960e-a7efc8dcd0d2)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/93733208-8e3e-4fac-83a5-75d44d641c5c)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/1e929522-330e-4ccb-bdc8-360398871d2f)
</picture>  
Answer was obtained from the Phishtool    
  
<picture>![image](https://github.com/user-attachments/assets/0b576312-f7bb-43dc-8b83-db691e10c136)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/e7e200a8-88c4-464e-852d-f861f5dc49a5)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/a64e71f5-70b0-4e4b-a999-f524d366c908)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/5814ad1f-8516-472c-bc07-9cae8c5f8cab)
</picture>  
Answer obtained from Cisco talos site 'https://talosintelligence.com/reputation_center/lookup?search=www.dropbox.com'  
<picture>![image](https://github.com/user-attachments/assets/2d3263ac-90b1-4ab3-95a5-688b5333138a)
</picture>  
<picture>![image](https://github.com/user-attachments/assets/983a25d2-6709-4584-b303-d58ecd81f91c)
</picture>  





