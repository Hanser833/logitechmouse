function OnEvent(event, arg)
    if event == "MOUSE_BUTTON_PRESSED" then
        if arg == 4 then 
            OutputLogMessage("Tăng DPI\n")
            PressAndReleaseKey("F1")
        elseif arg == 5 then 
            OutputLogMessage("Giảm DPI\n")
            PressAndReleaseKey("F9")
        elseif arg == 6 then -- 
            OutputLogMessage("Tắt DPI\n")
            PressKey("LCtrl")
            PressAndReleaseKey("F12")
            ReleaseKey("LCtrl")
        end
    end
end
