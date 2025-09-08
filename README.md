<<<<<<< HEAD
# Family Stress Simulator

This is a static site for the Family Stress Simulator.

How to publish on GitHub Pages:

- Create a new GitHub repository (public).

- Upload the contents of this folder (index.html and assets).

- Go to Settings -> Pages -> Source, and select main branch / root, then Save.

- Your site will be available at https://<your-username>.github.io/<repo-name>/.

=======
# Family Stress System Simulator

      ## Overview
      This is a web-based simulator for modeling stress levels in a family system. It uses an interconnected tanks metaphor to represent stress dynamics among family members (Father, Mother, and three Sons). The simulation allows users to adjust various parameters and visualize how stress propagates through the system over time.

      ## Features
      - **Real-time Simulation**: Start, pause, step, reset, or zero out variables.
      - **Adjustable Parameters**:
        - External Stress Inflow (0-100) for each family member.
        - Healthy Coping Outflow (0-100) for each family member.
        - Interconnections (0-100%) between family members.
        - Tank Dimensions (Width and Height) affecting stress flow rates.
      - **Day Types**: Normal, Calm (reduces stress by 50%), or Stormy (increases stress by 50%), with temporary effects.
      - **Interactive Chart**: Visualizes stress levels over time using Plotly.js.
      - **Speed Control**: Adjust simulation speed (10-200 ms per step).

      ## How to Use
      1. Open the `family_stress_sim_VF_2.0.html` file in a modern web browser.
      2. Adjust sliders for external stress, coping, interconnections, and tank dimensions.
      3. Select a day type to apply modifiers.
      4. Click "Start" to run the simulation, "Pause" to stop, "Step" for single iterations, "Reset" to restart, or "Zero" to set most variables to 0.
      5. Observe the chart updating in real-time.

      ## Dependencies
      - [Plotly.js](https://cdn.plot.ly/plotly-2.27.0.min.js) (loaded via CDN)

      ## Technical Details
      - Built with HTML, CSS, and JavaScript.
      - Uses Plotly for charting.
      - Simulation logic based on differential equations for stress accumulation and flow.
      - Responsive design with a dark theme.

      ## License
      Copyright: SF/SP (Advisory: LM). All rights reserved.
>>>>>>> origin/main
