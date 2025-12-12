# Ex09 Event Registration Web Application
## Date:

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
```
import React from 'react';
import { motion } from 'framer-motion';

// Default export React component. Replace `logo.png` with your college logo path.
export default function SaveethaMockup() {
  return (
    <div className="min-h-screen bg-gray-100 p-6 flex items-start justify-center">
      <div className="max-w-6xl w-full grid grid-cols-1 md:grid-cols-3 gap-6">
        {/* Left Panel */}
        <motion.section
          initial={{ opacity: 0, y: 10 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.35 }}
          className="flex flex-col items-center justify-start p-8 bg-[#4f0e0e] rounded-lg shadow-md text-white"
        >
          <h2 className="text-xl font-medium mb-6">Saveetha Engineering Collage</h2>
          <div className="w-full border-t border-white/30 mb-6" />

          <img src="/logo.png" alt="Saveetha logo" className="w-28 h-28 object-contain my-4 bg-white p-2 rounded" />

          <div className="mt-8 text-center space-y-4">
            <p>Affilated To Anna University</p>
            <p>NIRF Ranked</p>
            <p>Autonomous Institute</p>
          </div>

          <button className="mt-8 bg-[#1ed22b] text-white px-8 py-3 rounded-md font-medium hover:shadow-lg">LOGIN</button>
        </motion.section>

        {/* Middle Panel (Login) */}
        <motion.section
          initial={{ opacity: 0, y: 10 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.45 }}
          className="flex flex-col items-center justify-start p-6 bg-[#9b8323] rounded-lg shadow-md text-white"
        >
          <h3 className="text-lg mb-4">Saveetha Engineering Collage</h3>

          <img src="/logo.png" alt="Saveetha logo" className="w-24 h-24 object-contain my-3 bg-white p-2 rounded" />

          <label className="self-start text-pink-700 mt-6">Username</label>
          <input className="w-full md:w-72 h-10 my-2 px-3 rounded-sm" placeholder="Enter username" />

          <label className="self-start text-blue-800 mt-4">Password</label>
          <input type="password" className="w-full md:w-72 h-10 my-2 px-3 rounded-sm" placeholder="Enter password" />

          <button className="mt-6 bg-[#1ed22b] text-white px-6 py-2 rounded-md font-medium hover:shadow">SUBMIT</button>
        </motion.section>

        {/* Right Panel */}
        <motion.section
          initial={{ opacity: 0, y: 10 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.55 }}
          className="flex flex-col items-center justify-start p-8 bg-[#b32b6a] rounded-lg shadow-md text-white"
        >
          <h4 className="text-lg mb-4">Saveetha Engineering Collage</h4>

          <img src="/logo.png" alt="Saveetha logo" className="w-20 h-20 object-contain my-3 bg-white p-2 rounded" />

          <div className="mt-8 text-center space-y-6 text-white">
            <p className="uppercase tracking-wide">Departments</p>
            <ul className="space-y-4">
              <li className="text-2xl font-light">AI -DS</li>
              <li className="text-2xl font-light">AI - ML</li>
              <li className="text-2xl font-light">IOT</li>
              <li className="text-2xl font-light">CC</li>
            </ul>
          </div>
        </motion.section>
      </div>
    </div>
  );
}



```


## OUTPUT:

<img width="304" height="573" alt="Screenshot 2025-12-12 091536" src="https://github.com/user-attachments/assets/2e5d4a73-11a4-4e12-9de2-a89d3fce1dc3" />

<img width="318" height="566" alt="Screenshot 2025-12-12 091546" src="https://github.com/user-attachments/assets/5a3fc0fd-b636-4e74-ba6c-ddabb68583a0" />

<img width="318" height="559" alt="Screenshot 2025-12-12 091555" src="https://github.com/user-attachments/assets/6b40e807-190d-46ac-92b0-0370ad0c8e5d" />




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
