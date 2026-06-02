
   
    -- Back button (Mouse Button 4)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 4 then
        PressAndReleaseKey("f9")
    end

    -- Forward button (Mouse Button 5)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 5 then
        PressAndReleaseKey("f2")
    end

    -- DPI button (Mouse Button 3 cho G304)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 3 then
        PressAndReleaseKey("lctrl", "f12")  -- đồng thời Ctrl + F12
    end
end
