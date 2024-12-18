# FlatKit - Outline Settings Controller

This Unity script allows you to control the outline thickness using FlatKit during runtime. It requires a button and slider to reset the pipeline and change the outline thickness.

## Setup Instructions

1. **Attach the Script**:
   - Attach the `OutlineSettingsController` script to any GameObject in your scene where you want to control the outline settings.

2. **UI Elements Setup**:
   - You will need a **Slider** and **TextMeshProUGUI** to control and display the outline thickness. Apply them to the OutlineSettingsController

3. **Quality Setting Requirement**:
   - Ensure that your Unity project has a **Quality setting** higher than the default setting in **Project Settings > Quality**.
   - For example, if using the **Performant** setting at array 1, create a new custom quality level above it at array 0.

4. **Adjusting the Outline**:
   - Use the **Slider** to change the outline thickness. The setting is saved automatically using PlayerPrefs.

5. **Reset the Pipeline**:
   - Click the button to reset the pipeline and apply the updated quality settings. Changing the quality settings was the only way I was able to apply the change at runtime.

## Notes

- This script requires **FlatKit** to be installed in your Unity project.
- The outline thickness setting is saved using **PlayerPrefs**, so changes persist between sessions.

## License

This project is licensed under the **MIT License**.

---

For more information, visit the [FlatKit website](https://flatkit.dustyroom.com/additional-scripts/).

