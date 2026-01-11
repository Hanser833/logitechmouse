function OnEvent(event, arg)

    -- Back button (Mouse Button 4)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 4 then
        PressAndReleaseKey("f9")
    end

    -- Forward button (Mouse Button 5)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 5 then
        PressAndReleaseKey("f2")
    end

    -- DPI button (thường là Button 6)
    if event == "MOUSE_BUTTON_PRESSED" and arg == 6 then
        PressKey("lctrl")
        PressAndReleaseKey("f12")
        ReleaseKey("lctrl")
    end

end
