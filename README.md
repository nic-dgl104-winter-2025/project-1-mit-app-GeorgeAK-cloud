# EcoTrack – Environmental Awareness App

## Overview

EcoTrack is a mobile application designed to help users build eco-friendly habits by tracking their daily environmental impact. The app calculates a user’s carbon footprint based on selected activities and provides insights into how they can reduce their environmental impact. The goal is to educate users, encourage positive changes, and promote a greener lifestyle by making sustainability easy and accessible.

EcoTrack is ideal for individuals, students, and environmentally conscious communities who want to take small steps toward reducing their carbon footprint. Whether you're tracking your daily commute, electricity usage, or waste production, this app provides real-time feedback and helpful suggestions.

## Features

### Activity-Based Carbon Footprint Tracker
- Users can select daily activities such as transportation, electricity usage, and waste management.
- Based on the inputs, the app calculates the carbon footprint in kilograms of CO₂.

### Eco Tips & Challenges
- The app provides simple sustainability tips to encourage better environmental practices.
- Users can participate in eco-friendly challenges, like reducing water usage or switching to reusable bags.

### Local Environmental Initiatives
- The app connects users to nearby recycling centers, community clean-up events, and sustainability programs to encourage real-world action.

### Progress Dashboard
- Users can track their carbon footprint over time with visual progress updates.
- Helps motivate users to improve their eco-friendly habits and set personal sustainability goals.

### TinyDB Local Storage
- Saves user inputs locally, so they can review past activities and see how they are improving over time.
- Ensures that user data is stored securely on the device, even if the app is restarted.

## How It Works

Using EcoTrack is simple and intuitive.

1. Choose an activity from a predefined list (e.g., driving, electricity use, or waste disposal).
2. Enter the required details, such as the number of miles driven or energy consumed in kilowatt-hours.
3. Calculate the impact—the app multiplies the input value by a preset carbon footprint coefficient to determine the environmental impact.
4. View results and get recommendations on how to lower your impact.
5. Save your data to track progress over time using the TinyDB storage system.


## Design & Blocks Used

EcoTrack is built using MIT App Inventor, a visual programming tool that simplifies mobile app development. The app uses the following key blocks and components:

### UI Components
- **ListPicker**: Allows users to select activities like driving, electricity usage, or recycling.
- **TextBox**: Enables users to enter numerical values (e.g., distance, energy usage, or weight of waste).
- **Label Blocks**: Display results and eco-friendly messages based on user inputs.
- **Button Blocks**: Trigger calculations and save user data when clicked.

### Logic & Data Processing
- **Math Blocks**: Used to multiply user-entered values with carbon footprint coefficients for impact calculations.
- **Dictionary Block**: Stores predefined values for various activities (e.g., CO₂ emissions per mile for different vehicle types).
- **TinyDB**: Saves user inputs locally for future reference, allowing users to see past records.

### Workflow Example
When the user clicks the "Calculate Impact" button:
- The app checks if both an activity and a numerical value are entered.
- It then retrieves the corresponding carbon rate from the dictionary block.
- The app multiplies the user’s input by the correct rate to calculate the carbon footprint.
- Finally, it displays the impact and stores the data using TinyDB.


## Future Improvements & Ideas

- Cloud Storage Integration – Sync user progress across multiple devices using Firebase or Google Sheets.
- Location-Based Recommendations – Suggest nearby eco-friendly stores and recycling centers using GPS.
- Social Sharing – Allow users to share their sustainability achievements on social media.
- More Data Visualizations – Add graphs to show long-term carbon footprint trends.


## References

- **EPA Greenhouse Gas Equivalencies Calculator**  
  [https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator](https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator)

- **MIT App Inventor Documentation**  
  [https://appinventor.mit.edu/explore](https://appinventor.mit.edu/explore)

- **United Nations Sustainable Development Goals (SDGs)**  
  [https://sdgs.un.org/goals](https://sdgs.un.org/goals)

## Conclusion

EcoTrack is a simple app for raising environmental awareness and helping users track their carbon footprint. With its easy-to-use interface and informative feedback, the app empowers users to make more sustainable choices in their daily lives.

This project showcases the power of MIT App Inventor in creating impactful mobile applications. We hope that EcoTrack inspires users to take small steps toward a greener future.

