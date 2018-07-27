# NVG

## Performance

Three primary factos that influence NVG performance

1. Illumination
    1. Lunar Illum
        1. Moon Phase (lunar cycle)
        1. Moon Angle
        1. Lunar albedo (reflectance e.g. waxing vs waning)
        1. Earth-Moon distance
    1. Night Sky Illum (Air glow)
        1. Starlight provides about 0.0022 lux
    1. Solar Influence (Sky glow)
        1. Ideal operation time for NVGs is when the sun is 12&deg; below the horizon
        1. Roughly 45-60 min after sunset (EENT | End of Evening Nautical Twilight)
    1. Artificial Illum (Cultural lighting, vehicles, weapons, flares, etc.)
1. Terrain Contrast
    1. Reflectance of terrain
    1. Shadows formed by terrain and illumination
1. Atmospheric Obscuration
    1. Quality of NVG image worsens as humidity levels increase
    1. Scattering can occur when light strikes a particle and changes its path resulting in degraded NVG performance

## The System

1. Objective Lens
    1. Purpose: focus incoming rays of light onto Image Intensifier Tube
    1. Variable focus from 41cm to 150ft (optical infinity)
    1. Class B (minus blue) lens filtering facilitates cockpit lighting
        1. rejects < 665nm wavelength light
1. Image Intensifier (I<sup>2</sup>) Components
    1. Photocathode
        1. Purpose: converting incoming visible and near IR energy into electical energy (electrons)
        1. Made of Gallium Arsenide (GaAs)
        1. Peak sensitivity: 600-900nm (0.6-0.9 microns)
        1. Night sky spectral irradiance is x5-x7 brighter in 800-900nm range than in visible region near 500nm
        1. BSP (bright source protection): limits the number of electrons leaving the Photocathode by reducing the voltage between the Photocathode and the input side of the MCP (Microchannel Plate)
    1. Ion Barrier Film
        1. Aluminum Oxide film on the objective end of the MCP that absorbs positive ions emitted from the MCP. This extends tube life to MILSPEC 10,000 hours
    1. Microchannel Plate
        1. Purpose: Exponentially mulitply electrons from Photocathode
        1. 1mm, thin wafer of ~6 million tiny glass tubes (channels)
        1. Tubes tilted at 5&deg; bias angle to ensure first electron impacts near the channel entrance
        1. Tubes coated with material that causes secondary electron emission when passing electron strikes it
        1. ABC (Auto Brightness Control)
            1. Automatically adjusts MCP voltage to control exiting electrons to maintain preset image brightness (gain up or down according to light level)
            1. Will degain in the presense of an incompatible light source which results in decreased image contrast and detail
    1. Phosphor Screen
        1. Purpose: Convert electron beam energy to light
        1. Screen is charged with a positive potential IOT attract the negatively charged electrons exiting the MCP
        1. The screen emits light when electrons strike it
        1. Screen uses P43 Phosphor so the light is green (peak sensitivity of the human eye)
    1. Fiber Optic Inverter
        1. Purpose: Receives light emitted from Phosphor Screen and inverts the image by way of millions of microscopic light-transmitting fibers
        1. Removes the need for a second lens assembly
1. Eyepiece lens
    1. Purpose: focus the light from Fiber Optic Inverter onto the eye
    1. Allows image to be focused properly to the back of the retina
    1. Range: +2 to -6

## The Preflight

1. Helmet – Inspect as normal for unaided flight, then for fit (accounting for extra forward weight) also ensure the mounting brackets are free of debris.
1. Quick Don Block Mount – Inspect and ensure it’s not cracked, the contacts are clear and clean, and there is no damage to the wiring. Test all controls for smooth operation
1. Load battery pack and mount to helmet
    1. Prior to inserting batteries, power pack – OFF
    1. Ensure batteries are correctly inserted – point down
    1. Attach battery pack to helmet
    1. Connect battery back cable to helmet wiring by matching up red dots and applying fingertip pressure.
1. Binocular Assembly
    1. Check for obvious damage and debris
    1. Rotate controls to unsure freedom of movement (diopter controls are naturally sticky)
    1. Lenses
    1. Check for smudges, debris, scratches or other damage.
    1. For smudges only use approved lens paper (found in NVG bag)
    1. For all other damage see maintenance
1. Zero out NVGs
    1. Vertical – Center
    1. Tilt – Center
    1. Eye Relief Fore and Aft Adj – Full Forward (away from eye)
    1. IPD – Center for each binocular (about 60)
    1. Diopter – set zero
1. Don Helmet – Attach binoculars and recheck fit, add counter weights if req

## Alignment

1. Vertical
1. Tilt
1. Eye relief
1. IPD

## Focusing

Focus one monocular at a time

1. Objective lens (fore)
    1. coarse lines into focus of visual acuity chart
1. Eyepiece lens (aft)
    1. full couterclockwise then pause
    1. slowly clockwise until image comes into sharp focus then stop
        1. continuing past the initial sharp focus causes your eye to work harder to keep the image focused
    1. Can also bracket this setting
        1. full counterclockwise
        1. clockwise until sharp focus
        1. counterclockwise until slight degradation then nudge clockwise for optimal diopter setting
1. Objective lens (fore)
    1. Bring into focus as many grids as possible
1. Repeat for other monocular
