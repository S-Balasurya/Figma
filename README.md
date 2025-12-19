# Ex09 Event Registration Web Application
## Date:19.12.2025
## Name: Balasurya S
## Register No:25000944

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
~~~

page 1

import React from "react";
import image from "./image.svg";
import logo from "./logo.png";
import textOnAPath2 from "./text-on-a-path-2.svg";
import textOnAPath3 from "./text-on-a-path-3.svg";
import textOnAPath4 from "./text-on-a-path-4.svg";
import textOnAPath from "./text-on-a-path.svg";

export const AndroidMedium = () => {
  return (
    <div className="bg-[#c31e91] overflow-hidden w-full min-w-[824px] min-h-[1544px] relative">
      <img
        className="absolute top-6 left-3.5 w-[810px] h-[122px] aspect-[6.65] object-cover"
        alt="Logo"
        src={logo}
      />

      <div className="absolute top-[278px] left-10 w-[346px] [font-family:'Inter-Regular',Helvetica] font-normal text-[#1a1717] text-5xl tracking-[0] leading-[normal]">
        {""}
      </div>

      <img
        className="absolute top-[1584px] left-[-450px] w-[715px] h-[133px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <div className="top-[403px] left-[55px] w-[700px] h-[124px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[431px] left-[78px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        {""}
      </div>

      <div className="top-[431px] left-[72px] w-[490px] h-[76px] absolute bg-[#d9d9d9]" />

      <img
        className="absolute top-[1610px] left-[-340px] w-[484px] h-[87px]"
        alt="Text on a path"
        src={image}
      />

      <img
        className="absolute top-[1870px] left-[-329px] w-[473px] h-[121px]"
        alt="Text on a path"
        src={textOnAPath2}
      />

      <img
        className="absolute top-[1858px] left-[-329px] w-[450px] h-[104px]"
        alt="Text on a path"
        src={textOnAPath3}
      />

      <img
        className="absolute top-[1858px] left-[-300px] w-[421px] h-[133px]"
        alt="Text on a path"
        src={textOnAPath4}
      />

      <div className="top-[651px] left-[228px] w-[334px] h-[121px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[688px] left-[311px] w-[188px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal] whitespace-nowrap">
        LOGIN
      </div>

      <div className="top-[893px] left-[190px] w-[421px] h-[138px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[931px] left-[225px] w-[354px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        &nbsp;&nbsp;&nbsp;&nbsp;REGISTER
      </div>

      <div className="absolute top-[432px] left-[161px] w-[502px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal] whitespace-nowrap">
        &nbsp;&nbsp; EVENT&nbsp;&nbsp;REGISTER
      </div>
    </div>
  );
};

page 2

import React from "react";

export const AndroidMedium = () => {
  return (
    <div className="bg-[#3df418] w-full min-w-[781px] min-h-[1521px] flex flex-col">
      <div className="ml-[60px] w-[583px] h-28 mt-[239px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        &nbsp;&nbsp;&nbsp;&nbsp;EVENTS :
      </div>

      <div className="ml-[121px] w-[496px] h-[104px] mt-8 [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        {" "}
        TYPES OF EVENTS
      </div>

      <p className="ml-[55px] w-[530px] h-[893px] mt-[46px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        SOLO SINGING
        <br />
        DANCE
        <br />
        GROUP DANCE
        <br />
        MIMICS
        <br />
        DUMSHARACKS
        <br />
        DRAMAS
      </p>
    </div>
  );
};

page 3

import React from "react";
import image from "./image.svg";
import textOnAPath2 from "./text-on-a-path-2.svg";
import textOnAPath3 from "./text-on-a-path-3.svg";
import textOnAPath4 from "./text-on-a-path-4.svg";
import textOnAPath5 from "./text-on-a-path-5.svg";
import textOnAPath6 from "./text-on-a-path-6.svg";
import textOnAPath7 from "./text-on-a-path-7.svg";
import textOnAPath from "./text-on-a-path.svg";

export const AndroidMedium = () => {
  return (
    <div className="bg-[#ff1b1b] overflow-hidden w-full min-w-[735px] min-h-[1521px] relative">
      <div className="absolute top-[129px] left-[67px] w-[596px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-5xl tracking-[0] leading-[normal]">
        {" "}
        Event Register Form
      </div>

      <img
        className="absolute top-[1481px] left-[-2288px] w-[634px] h-[106px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <img
        className="absolute top-[1682px] left-[-2294px] w-[614px] h-[110px]"
        alt="Text on a path"
        src={image}
      />

      <img
        className="absolute top-[1645px] left-[-2288px] w-[623px] h-[127px]"
        alt="Text on a path"
        src={textOnAPath2}
      />

      <img
        className="absolute top-[1682px] left-[-2285px] w-[620px] h-[110px]"
        alt="Text on a path"
        src={textOnAPath3}
      />

      <img
        className="absolute top-[1657px] left-[-2285px] w-[620px] h-[115px]"
        alt="Text on a path"
        src={textOnAPath4}
      />

      <div className="top-[642px] left-[55px] w-[623px] h-[118px] absolute bg-[#d9d9d9]" />

      <img
        className="absolute top-[2014px] left-[-2273px] w-[608px] h-[118px]"
        alt="Text on a path"
        src={textOnAPath5}
      />

      <div className="top-[1017px] left-[38px] w-[548px] h-[98px] absolute bg-[#d9d9d9]" />

      <img
        className="absolute top-[2366px] left-[-2296px] w-[539px] h-[103px]"
        alt="Text on a path"
        src={textOnAPath6}
      />

      <div className="top-[1363px] left-[356px] w-[351px] h-[98px] absolute bg-[#d9d9d9]" />

      <div className="top-[481px] left-[52px] w-[626px] h-[101px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[663px] left-[87px] w-[548px] [font-family:'Inter-Regular',Helvetica] font-normal text-[#0e0d0d] text-5xl tracking-[0] leading-[normal]">
        age
      </div>

      <div className="top-[838px] left-[47px] w-[631px] h-[104px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[870px] left-[90px] w-[513px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal] whitespace-nowrap">
        department
      </div>

      <div className="absolute top-[1023px] left-[47px] w-[485px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        mobile number
      </div>

      <div className="top-[1184px] left-[55px] w-[548px] h-[116px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[1227px] left-[90px] w-[442px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal] whitespace-nowrap">
        {" "}
        Events To Register
      </div>

      <div className="absolute top-[1377px] left-[368px] w-[321px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        submit
      </div>

      <img
        className="absolute top-[1498px] left-[-2305px] w-[640px] h-[104px]"
        alt="Text on a path"
        src={textOnAPath7}
      />

      <div className="top-[305px] left-[49px] w-[614px] h-[107px] absolute bg-[#d9d9d9]" />

      <div className="absolute top-[337px] left-[70px] w-[516px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        name
      </div>

      <div className="absolute top-[481px] left-[58px] w-[591px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-5xl tracking-[0] leading-[normal]">
        gender
      </div>
    </div>
  );
};

~~~

## OUTPUT:
<img width="1920" height="963" alt="Screenshot 2025-12-19 085013" src="https://github.com/user-attachments/assets/20226f0d-bcfe-4e8d-b6c8-cb7d9d378c18" />
<img width="1920" height="968" alt="Screenshot 2025-12-19 085835" src="https://github.com/user-attachments/assets/2e8d8a85-6db5-40c5-99ef-096a2b848139" />
<img width="1920" height="960" alt="Screenshot 2025-12-19 090830" src="https://github.com/user-attachments/assets/02ded1f6-fd74-431c-840c-5566feaf7909" />




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
