# MiniProject_Ramki_CovidVacc

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/2ad6800429fb42e6aba22439c4833b2a)](https://www.codacy.com/gh/Ramki17/MiniProject_Ramki_CovidVacc/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Ramki17/MiniProject_Ramki_CovidVacc&amp;utm_campaign=Badge_Grade)
![Code inspector CodeQuality](https://api.codiga.io/project/29929/score/svg)
![Code inspector CodeQuality](https://api.codiga.io/project/29929/status/svg)

[![CI](https://github.com/Ramki17/MiniProject_Ramki_CovidVacc/actions/workflows/main.yml/badge.svg)](https://github.com/Ramki17/MiniProject_Ramki_CovidVacc/actions/workflows/main.yml)

**Introduction**

The deployment of covid-19 vaccines in India was done in a sudden burst and thus the tracking became very complicated. Due to multiple input and output commands on the server, it resulted in several slow running issues and crashes. The Aadhar details were used to allot the vaccines and hence it operated on a central server. To avoid the use of central server for all commmands, a local server will be loaded with the vaccine-registered data. Local verification and completion of vaccination data will be processed locally and will be loaded back to the main server by the end of day. Each vaccine centre will operate locally to register and allot vaccines. The basic registration can be done online and schedules are set as desired by the patient. Assuming a vaccination centre can vaccinate around 100 people in a day. The data handling for online basic registration will be mostly done in the day time and the data acquired by the local centres of vaccinated people can be handled in the night. The local server must store the data of around 100 people where the allocated online registration data will be loaded onto the local server of that local centre. Verification of the data is done based on the details provided by the patient. Once completed, the data of the vaccinated will be sent back for future use and reference.
