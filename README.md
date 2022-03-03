# UE4 Virtual Controller

* This input sample shows how to interact with the axises, buttons, and touch available on the developer kit.

![image_1](images/image_1.png)

* This sample project was created in UE 4.21.2.

* The touch and button inputs are defined by the `Project Settings` in the `Action Mappings` section. Notice: `Gamepad_Touch` uses `Touch 1` to detect the tap event.

![image_2](images/image_2.png)

* The axis inputs are defined by the `Project Settings` in the `Axis Mappings` section.

![image_3](images/image_3.png)

* The sample level can be found at [Level01.umap](Content\Levels\Level01.umap).

* The UI Widget Blueprint defines the variables for the device images in [WidgetBP_Controller.uasset](Content/UI/WidgetBP_Controller.uasset).

* The level blueprint loads the UI widget.

![image_4](images/image_4.png)

* The level blueprint reacts to axis events and controls the visibility for overlay images.

![image_5](images/image_5.png)

* The level blueprint uses touch events to toggle image visibility.

![image_6](images/image_6.png)

* The level blueprint uses button events to toggle image visibility.

![image_7](images/image_7.png)

* Any button presses are printed to the screen for debugging.

![image_8](images/image_8.png)
