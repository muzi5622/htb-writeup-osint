<img src='assets/osint.png' style='zoom: 80%;' align=left /> <font size='10'>Geo OSINT </font>  

22<sup>nd</sup> August 2025  

Prepared By: `M. Muzamil`  

Challenge Author(s): `M. Muzamil`  

Difficulty: <font color='orange'>MEDIUM</font>  



# Synopsis (!)

- The objective was to determine the **city** and the **company** visible on the left side of the provided image using OSINT techniques.

---

## Description (!)

- The image contained a bus with the front display showing **151 STE-ROSE**.  
- By searching this bus route online, we found its service information, then mapped the route to identify the exact location.  
- Finally, Street View confirmed both the city and the company.

---

## Skills Required (!)

- OSINT & Reconnaissance  
- Google Search Skills  
- Map & Route Analysis  
- Street View Verification  

---

## Skills Learned (!)

- How to identify **cities via public transport routes**.  
- Using **official transit websites** as OSINT resources.  
- How to confirm an **exact spot on Google Maps**.  
- Recognizing logos and buildings as location markers.  

---

# Enumeration (!)

- Observed the bus with route number:

```

151 STE-ROSE

```

- A quick Google search for *“151 STE-ROSE bus route”* led to a **public transit website** showing route details.  
- This confirmed that the bus operates in **Laval, Quebec, Canada**.  

---

## Analyzing the Image (*)

- Visible elements:  
  1. Bus with **151 STE-ROSE** route.  
  2. A **petrol station logo** on the left.  

---

# Solution (!)

## Step 1 – Researching the Route

- Google search → Found the official **bus schedule/route site** for **151 STE-ROSE**.  
- The website described the path the bus takes across **Laval**.  

---

## Step 2 – Mapping the Route

- Opened **Google Maps**.  
- Followed the **151 STE-ROSE** route exactly as described on the transit website.  
- Carefully cross-checked landmarks and intersections.  

---

## Step 3 – Verification with Street View

- Used **Street View** to navigate along the path.  
- After careful comparison, found the **exact same spot** as in the given image.  

---

## Step 4 – Identifying the Company

- On the **left side of the image**, Street View revealed a **Shell petrol station**.  
- Full company name: **Royal Dutch Shell (Shell Petroleum)**.  

---

### Getting the Flag (!)

Final Results:  

1. **City:** HTB{Laval}
2. **Company on the left:** HTB{Shell_Plc}

---

## Recap (!)

- **Clue observed:** Route 151 STE-ROSE.  
- **Step 1:** Google search → transit website with route details.  
- **Step 2:** Opened same route on Google Maps.  
- **Step 3:** Verified exact spot with Street View.  
- **Step 4:** Identified Shell petrol station on the left.  

