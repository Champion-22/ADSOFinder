# Advanced DSO Finder: User Guide

Welcome to the Advanced DSO Finder! This guide explains all features and helps you get the most out of your astronomical observation nights.

---

### Table of Contents

1.  [**Core Features at a Glance**](#-core-features-at-a-glance)
2.  [**Understanding the User Interface**](#-understanding-the-user-interface)
    *   [The Sidebar: Your Control Center](#the-sidebar-your-control-center)
    *   [The Main Area: Results and Tools](#the-main-area-results-and-tools)
3.  [**Step-by-Step: Planning an Observation Night**](#-step-by-step-planning-an-observation-night)
4.  [**The Tools in Detail**](#-the-tools-in-detail)
    *   [Manual Target Entry & Plotting](#manual-target-entry--plotting)
    *   [Redshift Calculator](#redshift-calculator)
    *   [Sun Times Calculator](#sun-times-calculator)
5.  [**Tips for the Best Results**](#-tips-for-the-best-results)

---

### 🌟 Core Features at a Glance

*   **Intelligent Object Search:** Finds the best galaxies, nebulae, and star clusters for your specific location and time.
*   **Precision Filters:** Narrow down your search by sky quality (Bortle), object altitude, size, and moon brightness to see only relevant targets.
*   **Automatic Location:** Finds your location automatically or lets you search for places manually.
*   **Interactive Result Cards:** Each found object is presented with all essential data, including magnitude, size, culmination time, and constellation.
*   **Visual Aids:** A graphical representation of the moon phase and illumination percentage helps with planning.
*   **Integrated Astro Tools:** Calculators for sun times, redshift, and manual target analysis are built right into the app.
*   **Data Export:** Save your result list as a CSV file for use with other software.

---

### 🖥️ Understanding the User Interface

#### The Sidebar: Your Control Center

The left-hand sidebar is where you configure all the parameters for your search.

1.  **Location:**
    *   **Latitude/Longitude/Elevation:** Enter your precise coordinates.
    *   **City/Place Name:** Type a name and click "Search" to automatically fill in the coordinates.
    *   **Auto-detect:** Lets the app attempt to find your current location.

2.  **Time Settings:**
    *   **Now (Tonight):** Calculates visibility for the upcoming night (from astronomical dusk to dawn).
    *   **Specific Night:** Use the calendar to select any date in the future or past.

3.  **Filters:**
    *   **Bortle Scale:** Specifies the darkness of your sky (1 = excellent, 9 = city center). This affects how faint of an object can be found.
    *   **Min/Max Altitude:** Sets the range of altitude above the horizon where objects should be displayed. (Tip: A minimum of 30° reduces the impact of horizon haze).
    *   **Max Moon Illum.:** Excludes nights when the moon is brighter than the set percentage.
    *   **Min/Max Size:** Filters objects by their apparent size in the sky (in arcminutes).
    *   **Cardinal Direction:** Shows only objects that reach their highest point in the selected direction.

4.  **Object Types:**
    *   Use the collapsible menus to select exactly which types of objects you want to find (e.g., only galaxies and planetary nebulae).

5.  **Start Search:**
    *   The large "Search" button at the bottom of the sidebar starts the calculation with your settings.

#### The Main Area: Results and Tools

The large area on the right is organized into tabs.

*   **"Results" Tab:** This is where found objects appear after a successful search.
    *   Each object is an **expandable card**. Click it to reveal full details like constellation, size, and the best observation time.
    *   Above the list, you can **change the sorting** (by brightness or by optimal visibility).
    *   The **"Export" button** saves the current list as a CSV file.
    *   The **moon graphic** shows you the current phase for the selected night.

*   **"Tools" Tab:** Here you will find additional useful calculators.

---

### 🚀 Step-by-Step: Planning an Observation Night

1.  **Set Your Location:** Enter your coordinates or use the location search.
2.  **Choose a Date:** Leave it on "Now (Tonight)" or select a date in the calendar.
3.  **Adjust Filters:** Set the Bortle scale for your location and adjust other filters as desired.
4.  **Select Object Types:** Decide what you want to see. For starters, star clusters (open and globular) are often the easiest targets.
5.  **Start the Search:** Click the large button at the bottom of the sidebar.
6.  **Analyze the Results:** Browse the result list. Click on interesting objects to learn more.
7.  **(Optional) View Plots:** In a result card, click "Altitude Profile" or "Sky Path" to get a graphical representation for the object.
8.  **(Optional) Export:** Save your list to take with you outside.

---

### 🛠️ The Tools in Detail

#### Manual Target Entry & Plotting
Have a specific object in mind that doesn't appear in the search?

1.  Switch to the **Tools -> Manual Target Input** tab.
2.  Enter the object's name and/or its RA/Dec coordinates.
3.  Click **"Calculate"**. The app will compute the visibility for that specific target and display a result card.
4.  From here, you can also use the **plot functions**.

#### Redshift Calculator
A scientific tool for advanced users. Enter a redshift (z) and cosmological parameters to calculate values like lookback time and distances in the universe.

#### Sun Times Calculator
A handy utility for any day:
1.  Make sure your location is set correctly in the sidebar.
2.  Switch to the **Tools -> Sun Times Calculator** tab.
3.  Click **"Calculate Sun Times"**.
4.  The app will show you the sunrise, sunset, day length, solar noon, current local time (as a live clock), and the season for your location.

---

### ✅ Tips for the Best Results

*   **Be realistic with the Bortle scale.** An honest assessment of your sky quality will lead to the best and most visible targets.
*   **Start with a higher minimum altitude.** Objects near the horizon are often difficult to see. A value of 25-30° is a good starting point.
*   **Use the moon filter.** When the moon is bright (above 50%), faint nebulae and galaxies are nearly impossible to see. On such nights, focus on bright star clusters or planetary nebulae.
*   **Experiment!** Every night is different. Play with the filters and discover what the night sky has to offer.

---

### 🐞 Found a Bug or Have an Idea?

Feedback is always welcome! If you find a bug or have an idea for a new feature, the best way to share it is by creating an "Issue" on GitHub.

*   **[Click here to report a bug or suggest a feature](https://github.com/YOUR_USERNAME/YOUR_REPO/issues)**

Please describe the problem in as much detail as possible:
*   What did you do?
*   What did you expect to happen?
*   What happened instead? (including screenshots, if helpful)

This is a huge help in continuously improving the application.
