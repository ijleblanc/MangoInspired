# MangoInspired
*RTSS "MangoHud"-Inspired Overlays*

This is a collection of 4 custom RTSS overlays inspired by Flightlessmango's MangoHud, used in gaming Linux distros like SteamOS, Bazzite, ChimeraOS, and others.

These overlays aim to bring a similar style and functionality to Windows users via RivaTuner Statistics Server (RTSS).

## 📂 Included Overlays

    MangoHUD v1.ovl
    Simple, squared, and minimalist. Displays current FPS, frametime graph, and frametime delay.

    MangoHUD v2.ovl
    A horizontal layout inspired by MangoHud. Includes:

        FPS, frametime delay & graph

        1% lows

        GPU usage, temperature, VRAM, and power

        CPU usage, temperature, and power

        RAM usage

        Render API, screen resolution

        Date and 12-hour clock

    MangoHUD v3.ovl
    An expanded version of v1 with everything from v2, plus 0.1% lows.

    MangoHUD v4.ovl
    A modified version of v2 that includes all metrics from v3, but laid out more clearly. This overlay is taller, providing better readability — though it may be a bit intrusive in some games.

    ℹ️ These overlays are optimized for 2K resolution, but you can scale them up or down using the HotkeyHandler plugin in RTSS.

## 🖼️ Screenshots (Coming Soon)

## 🎨 Customization Notes

    Each overlay includes a semi-transparent black background (25% opacity). You can change this by editing the background tile in OverlayEditor.

    The CPU/GPU labels in v2 and v4 are placeholders — you can replace them with your actual hardware names. Just note that longer names might mess up the spacing.

## 📦 Requirements

    RTSS (RivaTuner Statistics Server)

    RTSS plugins:

        OverlayEditor.dll

        HotkeyHandler.dll
        (Both included in RTSS)

## 📥 Installation

    Open RTSS (from the Windows system tray).

    Click the "SETUP" button (next to "Reset").

    In the settings window, configure the options as shown below (I'll provide images soon).

    Go to the Plugins tab, and double-click OverlayEditor.dll.

    In OverlayEditor:

        Click Layouts > Load or press Ctrl+L

        Select any of the .ovl files from this pack

    To save changes, go to Layouts > Save or press Ctrl+S

    ✅ Done! The overlay should now be visible in-game.

## ❓ FAQ

Q: Can I customize names, fonts, colors, or element positions?
A: Yes! RTSS's OverlayEditor gives you full control.

Q: Does this work on Linux?
A: No — RTSS is Windows-only. But these overlays are based on MangoHud, which works on Linux. You can tweak MangoHud via tools like GOverlay.

Q: Can I change the CPU and GPU names?
A: Absolutely. Just edit the text in OverlayEditor. Be mindful of text length — longer names might overlap with other elements.

Q: Can I rearrange the elements or add new ones?
A: Yes. Everything can be moved, resized, or replaced. RTSS gives you a lot of freedom (within its own limits).

Q: Why is RAM and VRAM shown in MB instead of GB?
A: Since I’m not using external tools like HWiNFO, AIDA64, or HWMonitor, I'm limited to what MSI Afterburner can report — which is usually in MB. I'm looking into solutions, but haven’t found a workaround yet.

Q: I have a question. Who can I ask?
A: Feel free to reach out on Discord: Metallforest#5836


    I’ll upload preview images of each overlay so you can see what they look like before using them.

You can upload images using GitHub’s drag-and-drop interface or host them in a folder like /images/overlay1.png.
📝 License

These overlays are free to use, modify, and share. Attribution is appreciated but not required.
