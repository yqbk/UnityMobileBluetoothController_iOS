Bluetooth Mobile Controller Unity
=======================

Add Bluetooth Mobile Controller based on iCade support to your Unity iOS project.


Usage
-----
1. In your Xcode project, add the files that begin with iCade to the Classes folder. 
2. Open AppController.mm from this repo, and copy/paste the lines of code to the correct places in the UnityAppController.mm in the Classes folder.

Key mapping:
```
        // right
        if (Input.GetKeyDown(KeyCode.JoystickButton0))
            Debug.Log("JoystickButton0");
        
        // right release
        if (Input.GetKeyDown(KeyCode.JoystickButton1))
            Debug.Log("JoystickButton1");
        
        // top
        if (Input.GetKeyDown(KeyCode.JoystickButton2))
            Debug.Log("JoystickButton2");

        // top release
        if (Input.GetKeyDown(KeyCode.JoystickButton3))
            Debug.Log("JoystickButton3");
        
        // bottom
        if (Input.GetKeyDown(KeyCode.JoystickButton4))
            Debug.Log("JoystickButton4");
        
        // bottom release
        if (Input.GetKeyDown(KeyCode.JoystickButton5))
            Debug.Log("JoystickButton5");
        
        // left 
        if (Input.GetKeyDown(KeyCode.JoystickButton6))
            Debug.Log("JoystickButton6");
        
        // C
        if (Input.GetKeyDown(KeyCode.JoystickButton7))
            Debug.Log("JoystickButton7");
        
        // A
        if (Input.GetKeyDown(KeyCode.JoystickButton8))
            Debug.Log("JoystickButton8");

        // A release 
        if (Input.GetKeyDown(KeyCode.JoystickButton9))
            Debug.Log("JoystickButton9");
        
        // B
        if (Input.GetKeyDown(KeyCode.JoystickButton10))
            Debug.Log("JoystickButton10");
        
        // B release
        if (Input.GetKeyDown(KeyCode.JoystickButton11))
            Debug.Log("JoystickButton11");
        
        // left release
        if (Input.GetKeyDown(KeyCode.JoystickButton12))
            Debug.Log("JoystickButton12");
        
        // C release
        if (Input.GetKeyDown(KeyCode.JoystickButton13))
            Debug.Log("JoystickButton13");
        
        // D
        if (Input.GetKeyDown(KeyCode.JoystickButton14))
            Debug.Log("JoystickButton14");
        
        // D release
        if (Input.GetKeyDown(KeyCode.JoystickButton15))
            Debug.Log("JoystickButton15");
```

This prject is a modified version of mattfox12's iCade-Unity https://github.com/mattfox12/iCade-Unity 
to work with the bluetooth mobile controller who comes with VR Box https://www.youtube.com/watch?v=SJ5S4Sk1lVM

----

iCadeReaderView.h, iCadeReaderView.m and iCadeState.h slightly modified (retains/releases delegate) from https://github.com/scarnie/iCade-iOS

