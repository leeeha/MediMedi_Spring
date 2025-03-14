# 💊 2022 Solution Challenge: MediMedi 💊

## Service Introduction
This service is launced to solve [UN SGDs](https://sdgs.un.org/) **10. Reduced Inequalities**, especially a visual impairment. It is addressed to solve blind pill box distinguishing problem. Especially in the case of household medicines, they distinguished those pill boxes by remembering the shape of box and torn part. Currently, in South Korea, only few number of drugs marked with Braille. And even if Braille is written, it is faint or inaccurate, so that makes reading difficult.
To solve this problem, we developed a mobile application that could **automatically take a picture of a pill box, reads letters on the boxes, and provides the information about it from the database**.  
The application UI is designed carefully for the blind. The application supports TTS and high-constrast. and has larger UI elements than modern UI standard, large buttons and large lists, for ease of tapping the display without the vision. Also, it supports various tap gestures such as single tapping, double tapping, and holding for feature selection.  
Our ultimate goal is to help blind people distinguish and take drugs without any help of their guardians.


## Service Results
화면 녹화 

<BR>
<BR>

## Main Features
- **Searching by picture**
    - The application recognizes the pill box and captures it automatically. The captured box image is sent to server, then, DL model detects and recognizes texts on the pill box. Server uses those recognized texts to search medicine information. User can listen or read the searched information from the application.
- **History archiving**
    - Searched history is archived automatically. User can always look up the medicine information he/she searched. 
- **Medication Alarm**
   - User can set medicine taking alarm easily. 

## Demo Video
![image](https://user-images.githubusercontent.com/68603692/160271404-5b7e6ad4-419c-4a5d-b188-a9aec0fe1c30.png)


<BR>
<BR>


## Architecture
![image](https://user-images.githubusercontent.com/68603692/160264275-af4b2159-2c4f-420f-9a70-71e7aaf4a2b9.png)
[Andorid Repository](https://github.com/gdsc-seoultech/MediMedi_Android) | [Backend Repository](https://github.com/gdsc-seoultech/MediMedi_Spring) | [Deep Learning Repository](https://github.com/gdsc-seoultech/MediMedi_DL)

<BR>
<BR>
    
## 👨‍👩‍👧‍👦 Team Member
From [GDSC Seoultech](https://gdsc-seoultech.github.io/)

<table aligh="center">
   <tr>
      <td colspan="2" align="center"><strong>Front-End Developer</strong></td>
      <td colspan="1" align="center"><strong>Back-End Developer</strong></td>
      <td colspan="1" align="center"><strong>Deep Learning Developer</strong></td>
   </tr>
  <tr>
    <td align="center">
    <a href="https://github.com/leeeha"><img src="https://avatars.githubusercontent.com/u/68090939?v=4" width="150px;" alt="Haeun Lee"/><br /><sub><b>Haeun Lee</b></sub></a><br />
    </td>
     <td align="center">
        <a href="https://github.com/yoon-H"><img src="https://avatars.githubusercontent.com/u/71068767?v=4" width="150px" alt="Yunjae Ha"/><br /><sub><b>Yunjae Ha</b></sub></a>
     </td>
     <td align="center">
        <a href="https://github.com/twinklesu"><img src="https://avatars.githubusercontent.com/u/68603692?v=4" width="150px" alt="Subin Park"/><br /><sub><b>Subin Park</b></sub></a>
     </td>
         <td align="center">
        <a href="https://github.com/goldtan"><img src="https://avatars.githubusercontent.com/u/83542989?v=4" width="150px" alt="Minchan Kim"/><br /><sub><b>Minchan Kim</b></sub></a>
     </td>
  </tr>
</table>
