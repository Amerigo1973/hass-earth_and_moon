
### The Earth and Moon System

This project is an interactive 3D space simulation created with the **Three.js** JavaScript library. The simulation displays the Earth, the Moon, and a field of stars, synchronizing Earth's rotation with the local time to accurately show the position of day and night.

---

### Project Goal

My objective with this project was not only to create a visual simulation but also to learn the basics of web programming and 3D graphics in JavaScript. I have very limited programming knowledge, which is why I decided to use an artificial intelligence as a support and learning tool.

---

### Acknowledgment to Artificial Intelligence

I want to thank the AI for guiding me during the creation of this project. It played a fundamental role by helping me write the code, understand complex Three.js concepts, and solve the various synchronization and lighting issues I encountered. Without its help, this project would not have been possible.

I hope you enjoy this simulation and can appreciate it as an example of how artificial intelligence can be used as a powerful tool for learning and creation.

---

### How to Run the Simulation

To run the simulation on Home Assistant, follow these steps:

1.  Ensure your Home Assistant server is running.
2.  In the main directory of your Home Assistant configuration (where `configuration.yaml` is located), look for the `www` folder. If it does not exist, create it.
3.  Inside the `www` folder, create a new folder called **`earth_and_moon`**.
4.  Download all project files (`earth_and_moon.html`, `three.min.js`, `OrbitControls.js`, and the three texture images) and place all of them inside the `earth_and_moon` folder.
5.  In your Home Assistant dashboard, add a new card and choose the **`Webpage (iframe)`** type.
6.  In the `URL` field, enter the file path: `/local/earth_and_moon/earth_and_moon.html`.
7.  Save the card. The simulation should appear on your dashboard. Use your mouse or touchscreen gestures to interact with it.

[Home Assistant How To - Panel iFrame component](https://www.youtube.com/watch?v=k6gRagYTBU8)
This video provides a tutorial on how to use the `panel_iframe` component in Home Assistant, which is similar to the `iframe` card.
